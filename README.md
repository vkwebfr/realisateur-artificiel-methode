# Le Réalisateur Artificiel

> Crée des vidéos IA cinématographiques comme un réalisateur : un plan court et contrôlé à la fois.

Au lieu de demander à l'IA de générer une longue vidéo d'un seul coup, tu vas :

1. Écrire un brief créatif
2. Rassembler des références visuelles
3. Découper la vidéo en plans courts
4. Générer le premier et le dernier frame de chaque plan
5. Générer la transition vidéo entre ces frames
6. Assembler tous les clips en vidéo finale

C'est toute la méthode.

---

## Le processus visuel

Cycle complet en un seul schéma :

```
Brief → Références → Liste des plans → Prompts images →
→ Frames storyboard → Prompts vidéo → Clips de transition →
→ Montage → Livrable final
```

Neuf actes. Chaque acte produit un livrable validé qui devient la matière première de l'acte suivant.

---

## Pour qui ce repository

Cette méthode est conçue pour les créateurs de contenu, solopreneurs et marketeurs qui veulent un système répétable pour produire des vidéos IA de qualité professionnelle.

Idéal pour :

- Publicités de produits
- Vidéos démo pour SaaS
- Vidéos avec personnages et narration
- Contenus cinématographiques pour les réseaux sociaux
- Vidéos de lancement, tutoriels, Reels et TikToks

Pas besoin d'être réalisateur ni de connaître le cinéma. Le repository t'indique exactement quoi faire à chaque étape.

---

## Pourquoi cette méthode marche

Les IA vidéo actuelles (Sora, Veo, Seedance, Kling) sont remarquables sur **5 secondes** de mouvement contrôlé. Au-delà, elles dérivent : le visage change, le produit se déforme, la lumière saute, le décor mute.

La solution n'est pas d'écrire un prompt plus long. La solution est de **ne jamais demander à l'IA de générer plus de 5 secondes à la fois**.

Cette méthode utilise trois principes :

**Principe 1 — Découpage en plans courts**
Une vidéo de 20 secondes = 5 à 7 plans de 3 à 5 secondes. Chaque plan est généré séparément, validé séparément, contrôlé séparément.

**Principe 2 — Ancres first-frame / last-frame**
Pour chaque plan, on génère d'abord le **premier frame** et le **dernier frame** comme images statiques. La vidéo est ensuite générée *entre* ces deux frames fixes. L'IA ne décide plus du début et de la fin, elle se contente d'interpoler.

**Principe 3 — Raccord par image partagée**
Le dernier frame du plan N devient le premier frame du plan N+1. Le spectateur ne voit pas la coupe : il voit une seule vidéo continue.

Le résultat : tu obtiens 20 secondes parfaitement cohérentes, alors que tu n'as jamais demandé à l'IA de générer plus de 5 secondes d'affilée.

---

## Pré-requis

Pour utiliser cette méthode, il te faut :

- **Un abonnement Claude Pro** ([claude.ai](https://claude.ai)) — pour utiliser la fonction Projects
- **Un compte Higgsfield** ([higgsfield.ai](https://higgsfield.ai)) — pour la génération d'images et de vidéos
- **Un logiciel de montage** — CapCut (gratuit), DaVinci Resolve (gratuit), Premiere ou Final Cut

Aucune compétence technique au-delà : pas de code, pas de terminal, pas de GitHub à maîtriser. Tu copies des liens, tu écris du texte.

---

## Démarrage rapide

### Étape 1 — Crée un nouveau projet dans Claude

Va sur [claude.ai](https://claude.ai), ouvre la section **Projects** dans le menu de gauche, clique sur **New Project**.

Donne-lui un nom (par exemple « Mon projet vidéo »), puis **Create Project**.

### Étape 2 — Charge les deux repositories

Dans la section **Project Knowledge**, ajoute deux URLs GitHub :

**URL n°1 — La méthode universelle (obligatoire) :**

```
https://github.com/[ton-username]/realisateur-artificiel-methode
```

**URL n°2 — Le fichier de ta niche (choisis UN seul selon ton activité) :**

| Ton activité | Repository à ajouter |
|--------------|---------------------|
| Parfum, beauté, cosmétique | `realisateur-niche-parfum` |
| Restaurant, gastronomie | `realisateur-niche-restaurant` |
| Immobilier de prestige | `realisateur-niche-immobilier` |
| Mode, lookbook, défilé | `realisateur-niche-mode` |
| SaaS, tech, démo logiciel | `realisateur-niche-saas` |
| Formation, coaching | `realisateur-niche-formation` |
| Fitness, wellness | `realisateur-niche-fitness` |
| Marque personnelle | `realisateur-niche-marque-perso` |
| Automobile | `realisateur-niche-auto` |
| Voyage, hôtellerie, lifestyle | `realisateur-niche-voyage` |

Cette double-architecture est volontaire : un repo contient la méthodologie universelle, l'autre contient des prompts prêts à l'emploi pour ton secteur. Claude ne charge pas les 9 autres niches dont tu n'as pas besoin. Le contexte reste propre et focalisé.

### Étape 3 — Lance ta première demande

Une fois les deux repositories chargés, copie le prompt de la section ci-dessous et envoie-le à Claude.

---

## La règle d'or : first-frame / last-frame

Le secret pour passer d'un slideshow à une vraie vidéo cinéma :

**Le dernier frame du plan N doit être identique (ou très proche) au premier frame du plan N+1.**

```
Plan 01 :  [Frame A] ──────→ [Frame B]
                                  │
Plan 02 :  [Frame B] ──────→ [Frame C]
                                  │
Plan 03 :  [Frame C] ──────→ [Frame D]
                                  │
Plan 04 :  [Frame D] ──────→ [Frame E]
```

Cette technique crée l'illusion d'une vidéo continue alors que tu n'as généré que des clips courts indépendants. C'est ce qui sépare les vidéos IA amateurs des productions de niveau agence.

---

## Système approved / refused

Chaque acte produit plusieurs essais. Pour éviter le chaos, on classe :

```
attempts/       — tous les brouillons s'accumulent ici
approved/       — les fichiers validés sont fixés ici
disapproved/    — les rejetés sont gardés ici en archive
```

L'acte suivant se construit **uniquement** à partir du dossier `approved/`.

Cette règle protège le projet et économise tes crédits Higgsfield : tu ne génères jamais de vidéo à partir d'un frame médiocre.

---

## Le prompt à copier dans Claude

Une fois les deux repositories chargés dans ton Project, colle ce texte en premier message :

```
Je crée une vidéo IA selon la méthode du Réalisateur Artificiel.

Tu es directeur créatif d'une agence française de publicité 
cinématographique haut de gamme. Tu m'accompagnes de l'idée 
à la vidéo finale en suivant strictement le workflow en 9 actes 
décrit dans ce repository.

Règles de travail :

1. Tu suis les 9 actes dans l'ordre, sans en sauter aucun.
2. Après chaque acte, tu me demandes validation avant de passer 
   au suivant : "Cet acte te convient ? On valide ou on retravaille ?"
3. Les prompts pour les images et les vidéos sont toujours en 
   anglais, dans des blocs de code.
4. Le reste de la conversation reste en français, tutoiement.
5. Tu utilises les modèles et exemples de mon fichier de niche 
   en priorité quand il est disponible.
6. Tu appliques la règle first-frame / last-frame pour assurer 
   la continuité visuelle entre plans.
7. Tu termines chaque prompt image par cette signature stylistique :
   "cinematic still, shot on Arri Alexa, 35mm lens, shallow depth 
   of field, color graded".
8. Tu maintiens la cohérence du personnage/produit/éclairage en 
   répétant les détails-clés dans chaque prompt.

Commence par me poser une seule question :
"Quelle est l'idée de ta vidéo en une phrase ?"
```

Garde ce prompt sous la main : c'est lui qui configure Claude correctement pour tous tes projets.

---

## Processus pas à pas

### Acte 01 — Brief créatif

Tu décris en une phrase ou un paragraphe ce que tu veux raconter. Claude transforme cette idée en brief structuré :

- Concept central (une phrase forte)
- Ambiance et tonalité émotionnelle
- Style visuel avec références cinéma/photo précises
- Durée recommandée
- Message clé
- Audience cible

**Question de contrôle** : *Ce brief décrit bien la vidéo que tu veux faire ?*

### Acte 02 — Références

Claude liste tout ce qu'il faut rassembler avant de générer les images :

- Photos du produit ou du sujet
- Logo et identité de marque
- Mood board esthétique
- Palette couleurs (avec codes hex)
- Références cinéma précises (réalisateurs, films)
- Règles de cohérence à respecter sur tous les plans

**Question de contrôle** : *Ce sont les bonnes références à fixer ?*

### Acte 03 — Découpage (liste des plans)

Claude découpe ta vidéo en 5 à 7 plans courts. Pour chaque plan :

- Durée (3 à 5 secondes)
- Type de plan (gros plan, plan large, contre-plongée, travelling)
- Description visuelle
- First frame (image de départ)
- Last frame (image de fin)
- Émotion à transmettre

Exemple :

```
Plan 01 — Le flacon dans la pénombre
- Durée : 3s
- Type : gros plan fixe
- First frame : flacon sur marbre noir, lumière rasante dorée
- Last frame : main féminine entrant dans le cadre, doigts à 5cm 
  du flacon
- Émotion : désir naissant
```

**Question de contrôle** : *C'est la bonne séquence avant d'écrire les prompts ?*

### Acte 04 — Prompts pour les images

Claude écrit en **anglais** les prompts pour générer le first frame et le last frame de chaque plan.

Exemple :

```
### Plan 01 — First frame
Crystal perfume bottle on black marble surface, golden rim 
light from the left, deep shadows, mystery atmosphere, 
cinematic still, shot on Arri Alexa, 35mm lens, shallow 
depth of field, color graded, 9:16 aspect ratio.

### Plan 01 — Last frame  
Same crystal perfume bottle on same black marble surface, 
same golden rim light, female hand with manicured nails 
entering frame from the right, fingers approaching bottle, 
cinematic still, shot on Arri Alexa, 35mm lens, shallow 
depth of field, color graded, 9:16 aspect ratio.
```

Note les détails-clés répétés entre les deux prompts : c'est ce qui garantit la cohérence visuelle.

**Question de contrôle** : *Ces prompts sont prêts pour la génération ?*

### Acte 05 — Frames storyboard

Tu copies les prompts dans **Higgsfield** (Nano Banana Pro pour les images cinématographiques, Higgsfield Soul si tu as besoin d'un visage cohérent).

Tu génères plusieurs variantes, tu gardes les meilleures dans `approved/`, tu archives le reste dans `disapproved/`.

Pour chaque plan, tu crées un dossier avec deux fichiers :

```
shot-01/
  first-frame.png
  last-frame.png
```

**Question de contrôle** : *Ces frames sont suffisamment cohérents pour servir d'ancres vidéo ?*

### Acte 06 — Prompts pour les vidéos

Claude écrit en anglais les prompts vidéo pour la transition du first frame au last frame :

```
### Plan 01 — Video prompt
Duration: 3s
Use first-frame.png as start frame, last-frame.png as end frame.

Camera: static.
Motion: female hand slowly enters frame from the right, 
fingers approaching the bottle but not touching it.
Lighting: same golden rim light throughout.
Style: cinematic, 24fps, film grain, color graded.
```

**Question de contrôle** : *Ces prompts vidéo sont prêts à lancer ?*

### Acte 07 — Clips de transition

Tu copies chaque prompt dans le modèle vidéo de ton choix :

- **Seedance 2.0** : qualité agence, le plus cher
- **Kling 3.0** : excellent rapport qualité/prix, polyvalent
- **Veo 3** : parfait pour personnages qui parlent + audio natif

Tu fournis les frames first/last comme ancres. Tu valides ou tu rejettes.

**Question de contrôle** : *Ce clip enchaîne correctement du first frame au last frame ?*

### Acte 08 — Montage

Claude te donne les consignes de montage : ordre des plans, transitions entre clips, suggestions de musique, sound design, color grading, ajout du logo et du texte final.

Tu assembles dans le logiciel de ton choix (CapCut, DaVinci Resolve, Premiere). Tu vérifies les coutures (raccords) entre les plans.

**Question de contrôle** : *Ça ressemble à une seule vidéo continue ?*

### Acte 09 — Livrable final

Export final aux bonnes spécifications selon la plateforme :

- **TikTok / Reels / Shorts** : 9:16, H.264, 30 Mbps minimum
- **YouTube** : 16:9, H.264, 35 Mbps minimum
- **Stories Instagram** : 9:16, 15 secondes max
- **LinkedIn Ad** : 1:1 ou 16:9, 30 secondes max

---

## Exemple complet : Parfum boisé pour homme

Pour voir un projet entier qui passe par les 9 actes — du brief initial jusqu'à la vidéo finale — consulte :

[`EXEMPLE-COMPLET.md`](EXEMPLE-COMPLET.md)

Tu y trouveras :

- Le brief créatif validé
- La liste complète des références
- Le découpage en 5 plans
- Tous les prompts images en anglais
- Tous les prompts vidéo en anglais
- Les frames générés
- Les notes de montage final
- La vidéo finale

C'est le meilleur point de départ pour comprendre la méthode dans son ensemble avant de te lancer.

---

## Quel modèle utiliser pour quoi

| Besoin | Modèle | Pourquoi |
|--------|--------|----------|
| Image cinéma haute qualité | Nano Banana Pro| Meilleur rendu cinématographique du marché |
| Image avec personnage cohérent | Higgsfield Soul | Conserve le même visage sur toutes les images |
| Image générique / brouillon | Nano Banana / Nano Banana 2 | Plus rapide, moins cher |
| Vidéo qualité agence | Seedance 2.0 | Niveau cinéma, mais cher en crédits |
| Vidéo rapport qualité/prix | Kling 3.0 | Polyvalent, abordable, bon partout |
| Vidéo avec dialogue parlé | Veo 3 | Lip-sync naturel et audio natif |

Tous ces modèles sont accessibles via Higgsfield avec un seul abonnement.

---

## Conseils essentiels

- Ne génère jamais la vidéo directement. Toujours les frames d'abord.
- Ne valide pas un frame qui te semble "presque bon". En vidéo, ce sera pire.
- Si un visage, un logo ou un produit est crucial, utilise une référence visuelle dédiée dans tous les prompts.
- Garde tes essais ratés dans `disapproved/`. Ils montrent ce qu'il faut éviter sur les générations suivantes.
- Les clips courts (3 à 5 secondes) sont infiniment plus contrôlables que les longs.
- Une vidéo finale réussie, c'est la somme de nombreuses petites validations, pas un coup de génie.
- Si Claude dévie du workflow, rappelle-lui : « Reviens à l'Acte en cours et demande-moi validation. »

---

## Structure du repository

| Fichier | Rôle |
|---------|------|
| `README.md` | Ce document — la méthode universelle |
| `CLAUDE-INSTRUCTIONS.md` | Les règles précises que Claude doit suivre |
| `EXEMPLE-COMPLET.md` | Un projet complet du brief à la vidéo finale |

Tous ces fichiers sont automatiquement lus par Claude quand tu colles l'URL du repository dans Project Knowledge.

---

## Quels outils sont compatibles

Cette méthode n'est attachée à aucun outil en particulier.

Tu peux utiliser :

- N'importe quelle LLM pour les briefs et prompts (Claude, ChatGPT, Gemini, Mistral)
- N'importe quel générateur d'images (Nano Banana, DALL-E, Midjourney, Flux)
- N'importe quel générateur vidéo (Seedance, Kling, Runway, Pika, Veo, Sora)
- N'importe quel logiciel de montage (CapCut, DaVinci Resolve, Premiere, Final Cut)

L'outil compte moins que le processus.

**Brief → Références → Frames → Prompts → Transitions → Montage → Final.**

---

## Licence

MIT — utilise, copie, modifie, redistribue librement.

Si cette méthode t'aide à produire une vidéo dont tu es fier, partage ton résultat avec moi sur YouTube, Instagram ou par email. C'est ma seule récompense.

---

*Créé pour rendre la création vidéo IA aussi rigoureuse qu'un vrai tournage cinéma.*
