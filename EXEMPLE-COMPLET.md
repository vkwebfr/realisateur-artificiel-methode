# Exemple complet : Lancement d'un restaurant parisien

Ce document montre un projet entier passant par les 9 actes de la méthode, du premier brief jusqu'à la vidéo finale. Tu peux le lire avant de commencer ton propre projet, ou t'en servir comme référence de qualité pendant ta création.

Le cas pris en exemple est volontairement universel : la promotion d'un nouveau restaurant parisien. La méthode et la structure démontrées ici s'appliquent à n'importe quelle niche — parfum, immobilier, mode, SaaS, formation, fitness, voyage. Seuls le sujet et l'esthétique changent.

**Point clé à observer dans cet exemple** : chaque frame est visuellement unique. Aucun frame n'est la copie ou la quasi-copie d'un autre. La continuité narrative se fait par le changement d'angle, de cadrage et de moment dans l'action — jamais par la répétition d'image.

---

## Le brief initial du client

L'utilisateur écrit à Claude :

> *Je lance un nouveau bistrot contemporain à Paris appelé L'ATELIER. Cuisine française moderne, produits de saison, ambiance feutrée. Positionnement : entre bistrot et gastronomique, ticket moyen 65€. Audience : urbains 30-50 ans, foodies parisiens. Je veux une vidéo de 20 secondes pour Instagram Reels et TikTok pour annoncer l'ouverture.*

À partir de cette phrase, Claude produit les 9 actes suivants.

---

## Acte 01 — Brief créatif

### Concept

**Le savoir-faire à hauteur d'assiette.** L'ATELIER ne se vend pas par sa carte. Il se vend par les gestes qui précèdent l'assiette : la main qui dresse, la lumière sur l'ingrédient, le silence de la salle juste avant le service.

### Ambiance et tonalité

Précision artisanale, chaleur feutrée, intimité parisienne. On filme comme on filme un atelier de joaillier : gros plans, gestes lents, matériaux nobles. Pas de musique festive, pas de table qui rigole. Le restaurant comme atelier d'artisan, le chef comme artisan.

### Style visuel

Référence cinéma : *The Bear* (FX, 2022) pour les gros plans cuisine, *The Hundred-Foot Journey* pour la lumière, *Burnt* (2015) pour la précision des gestes. Photographie : Mikkel Karlsson pour la macro food, Andrew Montgomery pour les intérieurs de restaurants.

Pas de photo prise de table avec téléphone. Pas de plats vus du dessus en flat lay Pinterest. Pas de chef qui sourit face caméra.

### Durée recommandée

**20 secondes**, découpé en 5 plans de 3 à 5 secondes chacun.

### Message clé

*Ouverture le 15 octobre. La table dont Paris parlera cet automne.*

### Audience cible

Parisien 30-50 ans, vit dans le 3e, 9e, 10e ou 11e arrondissement, lit *Le Fooding* ou *Atabula*, suit des comptes Instagram de gastronomie, considère le dîner au restaurant comme une sortie culturelle, pas une simple obligation alimentaire.

**Question de contrôle** : *Ce brief décrit bien la vidéo que tu veux faire ?*

---

## Acte 02 — Références visuelles et ancres de cohérence

### Références à rassembler

- Photo de la façade du restaurant à différentes heures (jour, crépuscule, nuit)
- Logo L'ATELIER en typographie (PNG transparent)
- Photo du chef en uniforme (3/4 dos, pas de visage complet)
- Photo de la salle vide et de la salle pleine
- 3 photos de plats signature

### Mood board esthétique

- *The Bear* — gros plans cuisine, mouvements rapides, intensité
- Andrew Montgomery — intérieurs de restaurants Londoniens, lumière chaude
- Mikkel Karlsson — macro food avec depth of field extrême
- Photos de chez Septime (Paris) — référence locale d'ambiance
- Textures : bois brut, lin écru, cuivre martelé, ardoise, herbes fraîches

### Palette couleurs

| Couleur | Code hex | Utilisation |
|---------|----------|-------------|
| Brun chaud | `#3d2f24` | Bois, fond, ombres |
| Cuivre patiné | `#a16b3a` | Lumière chaude, accents |
| Crème lin | `#e8dfd0` | Nappes, mur, textures |
| Vert sauge | `#7a8a6f` | Herbes, plantes, accents |
| Noir profond | `#1c1812` | Ardoise, contraste |

### Consistency tokens à répéter dans tous les prompts

Sur tous les plans sans exception :

1. **Restaurant** : Parisian bistrot interior, warm low-key lighting, wood tones, copper accents, candle ambiance, intimate atmosphere
2. **Chef** : European male chef, mid-40s, three-day stubble, white pristine chef coat, dark apron, never showing full face
3. **Éclairage** : warm tungsten lighting from above and side, deep shadows preserved, candlelight glow visible
4. **Esthétique** : cinematic food photography style, soft natural depth of field

Ces tokens se répètent **mot pour mot** dans chaque prompt — c'est ce qui garantit que tous les plans appartiennent au même restaurant.

**Question de contrôle** : *Ce sont les bonnes ancres de cohérence à fixer ?*

---

## Acte 03 — Découpage en 5 plans visuellement uniques

**Règle d'or de ce découpage** : chaque plan propose un cadrage, un angle et un moment d'action différents. Aucune redite, aucune image quasi-identique entre les plans.

### Plan 01 — La façade qui s'allume (3s)

- **Type de plan** : extérieur, plan large statique
- **Cadrage** : façade du restaurant vue depuis le trottoir d'en face, rue parisienne au crépuscule
- **First frame** : façade éteinte, encore deux passants qui marchent, ciel bleu profond
- **Last frame** : lumière intérieure qui vient de s'allumer derrière les vitres, façade chaude, trottoir vide
- **Émotion** : promesse, ouverture, attente
- **Notes** : composition urbaine, beaucoup d'air, contraste entre extérieur froid et intérieur chaud

### Plan 02 — La main du chef à l'ouvrage (4s)

- **Type de plan** : intérieur cuisine, gros plan macro
- **Cadrage** : vue du dessus à 45°, focale macro sur les mains du chef
- **First frame** : mains du chef qui posent une lamelle de truffe noire sur une assiette presque finie
- **Last frame** : pince qui ajoute la dernière feuille d'herbe, assiette terminée à 90%
- **Émotion** : précision, art, savoir-faire
- **Notes** : composition complètement différente du plan 01 — on est passé de l'extérieur urbain à la macro intime

### Plan 03 — Le plat qui arrive en salle (4s)

- **Type de plan** : intérieur salle, plan moyen, contre-plongée légère
- **Cadrage** : bras du serveur (sans visage) qui apporte l'assiette, vue depuis la table du client
- **First frame** : assiette à 50cm de la table, encore en mouvement, fond flou de la salle
- **Last frame** : assiette posée devant le client, fumée encore visible, autres tables en fond bokeh
- **Émotion** : anticipation, service
- **Notes** : angle bas qui donne de la noblesse au plat, profondeur de champ qui isole l'assiette

### Plan 04 — L'instant de plaisir (4s)

- **Type de plan** : intérieur salle, gros plan visage partiel
- **Cadrage** : profil d'une cliente (mi-trentaine), uniquement bouche et mâchoire, sans yeux
- **First frame** : fourchette qui s'approche des lèvres, première bouchée
- **Last frame** : expression imperceptible de plaisir, fourchette baissée, candlelight sur la peau
- **Émotion** : satisfaction silencieuse
- **Notes** : on ne voit jamais les yeux — éthique du "fragment" pour préserver le mystère

### Plan 05 — Le restaurant dans son ensemble + logo (5s)

- **Type de plan** : intérieur, plan d'ensemble en plongée légère
- **Cadrage** : vue d'ensemble de la salle en pleine activité, depuis l'entrée
- **First frame** : salle pleine, tables servies, ambiance chaleureuse, lumière chaude partout
- **Last frame** : logo L'ATELIER apparu en bas de l'image en serif élégant, baseline "Ouverture le 15 octobre · Paris 11e"
- **Émotion** : aboutissement, invitation
- **Notes** : composition complètement différente des plans précédents — on prend de la hauteur et de la distance pour conclure

### Vérification de l'unicité des frames

Les 10 frames de ce projet sont visuellement très différents les uns des autres :

| Frame | Composition |
|-------|-------------|
| Plan 01 first | Extérieur urbain crépuscule, façade éteinte |
| Plan 01 last | Extérieur urbain crépuscule, façade allumée |
| Plan 02 first | Macro vue 45° sur mains du chef, truffe noire |
| Plan 02 last | Macro vue 45° sur mains du chef, herbe finale |
| Plan 03 first | Plan moyen contre-plongée, assiette en l'air |
| Plan 03 last | Plan moyen contre-plongée, assiette posée |
| Plan 04 first | Gros plan profil cliente, fourchette qui monte |
| Plan 04 last | Gros plan profil cliente, fourchette redescendue |
| Plan 05 first | Plan d'ensemble plongée, salle en activité |
| Plan 05 last | Plan d'ensemble plongée, logo apparu |

Aucun frame n'est la copie d'un autre. Chaque pair (first / last d'un même plan) montre une **évolution claire** de l'action en 3-5 secondes, pas une image identique.

### Continuité narrative entre plans

Le raccord se fait par le **récit**, pas par l'image :

```
Plan 01 (extérieur s'allume)
    ↓ on entre dans le restaurant
Plan 02 (gros plan cuisine)
    ↓ le plat finit, part en salle
Plan 03 (plat arrive en salle)
    ↓ le client commence à manger
Plan 04 (bouche du client)
    ↓ on prend du recul
Plan 05 (vue d'ensemble + logo)
```

Chaque plan continue logiquement le précédent, mais avec un cadrage radicalement différent. C'est ce qu'on appelle le **découpage analytique** en cinéma : varier les échelles de plan pour raconter une action.

**Question de contrôle** : *C'est la bonne séquence avant d'écrire les prompts ?*

---

## Acte 04 — Prompts pour les images

Tous les prompts sont en anglais avec signature stylistique adaptée à la niche restaurant : `cinematic food photography, shot on Hasselblad, 100mm macro lens, soft natural light, color graded`.

Pour les plans larges (01, 03, 05), la signature s'adapte : `cinematic interior photography, shot on Sony A7R, 24mm lens, deep depth of field, color graded`.

### Plan 01 — First frame

```
Parisian bistrot facade at dusk, street view from across the 
sidewalk, restaurant lights still off behind glass windows, two 
passersby walking in the foreground, deep blue sky, urban Paris 
11th arrondissement atmosphere, warm wood signage barely visible, 
cinematic interior photography, shot on Sony A7R, 24mm lens, 
deep depth of field, color graded, 9:16 aspect ratio.
```

### Plan 01 — Last frame

```
Same Parisian bistrot facade at dusk, same street view from 
across the sidewalk, now warm interior lights just turned on 
glowing through glass windows, empty sidewalk, deep blue sky 
transitioning to night, urban Paris 11th arrondissement 
atmosphere, copper details on facade now visible, cinematic 
interior photography, shot on Sony A7R, 24mm lens, deep depth 
of field, color graded, 9:16 aspect ratio.
```

### Plan 02 — First frame

```
Overhead 45-degree angle, extreme close-up macro shot, European 
male chef hands mid-40s with three-day stubble visible at edge, 
white pristine chef coat sleeve, precisely placing a black 
truffle slice on a nearly finished gourmet plate, dark slate 
plate base, garnishes already arranged, warm tungsten lighting 
from above and side, deep shadows preserved, Parisian bistrot 
kitchen atmosphere, cinematic food photography, shot on 
Hasselblad, 100mm macro lens, soft natural light, color graded, 
9:16 aspect ratio.
```

### Plan 02 — Last frame

```
Same overhead 45-degree angle, extreme close-up macro shot, 
same European male chef hands with white pristine chef coat 
sleeve, now using delicate tweezers to add the final fresh herb 
leaf on the plate, same dark slate plate now 90% complete with 
truffle slice and garnishes visible, same warm tungsten lighting 
from above and side, deep shadows, Parisian bistrot kitchen 
atmosphere, cinematic food photography, shot on Hasselblad, 
100mm macro lens, soft natural light, color graded, 9:16 aspect 
ratio.
```

### Plan 03 — First frame

```
Medium shot, low-angle slight upward tilt from customer 
perspective, server's arm in white shirt sleeve carrying a 
gourmet plate, plate approximately 50cm above table surface in 
motion, faceless server, dark wood table in foreground, 
out-of-focus warm Parisian bistrot interior in background with 
candlelight bokeh, cinematic food photography, shot on 
Hasselblad, 100mm macro lens, soft natural light, color graded, 
9:16 aspect ratio.
```

### Plan 03 — Last frame

```
Same medium shot, same low-angle from customer perspective, 
same server's arm now retreating slightly, gourmet plate just 
placed on the dark wood table in foreground, subtle steam still 
visible rising from the dish, same out-of-focus warm Parisian 
bistrot interior in background with candlelight bokeh, other 
diners barely visible in deep bokeh, cinematic food photography, 
shot on Hasselblad, 100mm macro lens, soft natural light, color 
graded, 9:16 aspect ratio.
```

### Plan 04 — First frame

```
Extreme close-up profile shot, woman in her mid-30s, only mouth 
and jawline visible, never showing eyes, fork approaching lips 
holding a small bite of food, candlelight glow on skin from the 
right, warm tungsten interior lighting, blurred Parisian bistrot 
background, intimate atmosphere, cinematic editorial 
photography, shot on Canon R5, 50mm lens, shallow depth of 
field, color graded, 9:16 aspect ratio.
```

### Plan 04 — Last frame

```
Same extreme close-up profile shot, same woman mid-30s, same 
mouth and jawline visible no eyes, fork now lowered slightly 
away from lips after first bite, subtle imperceptible 
expression of pleasure, same candlelight glow on skin from the 
right, same warm tungsten interior lighting, blurred Parisian 
bistrot background, intimate atmosphere, cinematic editorial 
photography, shot on Canon R5, 50mm lens, shallow depth of 
field, color graded, 9:16 aspect ratio.
```

### Plan 05 — First frame

```
Wide establishing shot, slight high-angle from restaurant 
entrance, full view of busy Parisian bistrot interior, multiple 
tables with diners eating, warm tungsten lighting throughout, 
candles on every table, wood and copper details, bustling but 
intimate atmosphere, no specific person highlighted, cinematic 
interior photography, shot on Sony A7R, 24mm lens, deep depth 
of field, color graded, 9:16 aspect ratio.
```

### Plan 05 — Last frame

```
Same wide establishing shot, same slight high-angle from 
restaurant entrance, same full view of busy Parisian bistrot 
interior, same diners and lighting, L'ATELIER logo now appearing 
in lower third in elegant gold serif typography, baseline text 
"Ouverture le 15 octobre · Paris 11e" in smaller serif beneath 
logo, cinematic interior photography, shot on Sony A7R, 24mm 
lens, deep depth of field, color graded, 9:16 aspect ratio.
```

### Observation importante

Note que dans chaque plan, le first frame et le last frame se ressemblent **en composition** (même angle, même cadrage), mais montrent **une évolution claire** de l'action (lumière qui s'allume, geste qui progresse, plat qui est posé, fourchette qui descend, logo qui apparaît).

Note aussi que d'un plan à l'autre, les compositions sont **radicalement différentes** : extérieur urbain → macro cuisine → plan moyen salle → gros plan visage → plan large d'ensemble.

C'est exactement ce qu'il faut produire. Cohérence dans le style, variété dans les cadrages.

**Question de contrôle** : *Ces prompts sont prêts pour la génération dans Higgsfield ?*

---

## Acte 05 — Génération des frames

L'utilisateur copie les 10 prompts dans Higgsfield :

- **Nano Banana Pro** pour les plans 01, 03, 05 (interieurs, ambiance)
- **Hasselblad-style food prompts** pour le plan 02 (macro cuisine)
- **Higgsfield Soul** uniquement si l'utilisateur a fourni des photos réelles du chef et de la cliente

### Processus pour chaque frame

1. Générer 4 variantes par prompt en text-to-image pur, sans image de référence
2. Évaluer chaque variante selon ces critères :
   - L'esthétique correspond-elle aux consistency tokens définis à l'Acte 02 ?
   - Le cadrage et l'angle correspondent-ils au découpage ?
   - L'éclairage est-il cohérent avec les autres frames ?
   - Le frame est-il différent des autres frames du projet ?
3. Sélectionner la meilleure variante → `approved/`
4. Archiver les autres → `disapproved/`
5. Si aucune ne convient, regénérer en ajustant le prompt

### Règle critique

**Ne jamais passer un job_id précédent comme référence dans le paramètre `medias` de Higgsfield**, sauf si l'utilisateur utilise explicitement Higgsfield Soul avec un personnage entraîné. Chaque frame se génère en text-to-image pur pour garantir la diversité visuelle.

### Statistiques moyennes pour ce type de projet

| Frame | Tentatives moyennes | Difficulté |
|-------|---------------------|------------|
| Plan 01 first/last | 4-6 par frame | Moyenne — façade et lumière |
| Plan 02 first/last | 8-12 par frame | Élevée — macro et gestes précis |
| Plan 03 first/last | 6-8 par frame | Moyenne — fumée difficile |
| Plan 04 first/last | 10-14 par frame | Élevée — profil sans yeux, expression subtile |
| Plan 05 first/last | 6-8 par frame | Moyenne — composition d'ensemble |

**Total** : environ 70-90 générations pour 10 frames validés. C'est normal.

### Structure finale du dossier `approved/`

```
05-storyboard-frames/approved/
  shot-01/
    first-frame.png
    last-frame.png
  shot-02/
    first-frame.png
    last-frame.png
  shot-03/
    first-frame.png
    last-frame.png
  shot-04/
    first-frame.png
    last-frame.png
  shot-05/
    first-frame.png
    last-frame.png
```

**Question de contrôle** : *Ces frames sont suffisamment cohérents pour servir d'ancres vidéo ?*

---

## Acte 06 — Prompts pour les vidéos

### Plan 01 — Video prompt

```
Duration: 3s
Use first-frame.png as start frame, last-frame.png as end frame.

Camera: static.
Motion: interior lights turn on smoothly behind the windows, 
warm glow appearing progressively. The two passersby walk out 
of frame to the left during the first second. Light gradually 
intensifies.
Lighting: transition from cold exterior dusk to warm interior 
glow.
Style: cinematic, 24fps, film grain, color graded.
```

### Plan 02 — Video prompt

```
Duration: 4s
Use first-frame.png as start frame, last-frame.png as end frame.

Camera: static, slight micro-movement.
Motion: chef hands move with precision, placing the truffle 
slice firmly, then picking up tweezers and adding the herb 
leaf at the end. Movements are deliberate and slow.
Lighting: consistent warm tungsten throughout.
Style: cinematic, 24fps, slow controlled movements, film grain, 
color graded.
```

### Plan 03 — Video prompt

```
Duration: 4s
Use first-frame.png as start frame, last-frame.png as end frame.

Camera: slight tilt down from 5 degrees high to neutral.
Motion: server's arm completes the descent of the plate to the 
table surface in 2 seconds, then retreats slightly. Steam rises 
from the plate. Background bokeh remains soft.
Lighting: consistent warm tungsten.
Style: cinematic, 24fps, film grain, color graded.
```

### Plan 04 — Video prompt

```
Duration: 4s
Use first-frame.png as start frame, last-frame.png as end frame.

Camera: static.
Motion: fork approaches lips, slight pause as she takes the 
bite, then fork lowers slowly. Her expression shifts almost 
imperceptibly to satisfaction at the very end.
Lighting: candlelight glow remains constant on skin.
Style: cinematic, 24fps, intimate slow motion at 90% speed, 
film grain, color graded.
```

### Plan 05 — Video prompt

```
Duration: 5s
Use first-frame.png as start frame, last-frame.png as end frame.

Camera: very slow push in (5% over 5 seconds).
Motion: diners in the restaurant continue their meals with 
subtle natural movements. After 3 seconds, L'ATELIER logo fades 
in at the bottom third of the frame with elegant timing. 1 
second later, baseline text appears.
Lighting: consistent warm tungsten throughout.
Style: cinematic, 24fps, film grain, color graded.
```

**Question de contrôle** : *Ces prompts vidéo sont prêts à lancer ?*

---

## Acte 07 — Génération des clips

### Choix des modèles par plan

| Plan | Modèle | Raison |
|------|--------|--------|
| Plan 01 | Kling 3.0 | Mouvement simple (lumière qui s'allume), économie de crédits |
| Plan 02 | Seedance 2.0 | Gestes humains précis, qualité critique pour macro food |
| Plan 03 | Seedance 2.0 | Fumée et bokeh complexes, besoin de qualité maximale |
| Plan 04 | Seedance 2.0 | Expression faciale subtile, sensibilité maximale |
| Plan 05 | Kling 3.0 | Plan d'ensemble simple, économie sur le pack-shot |

**Total estimé** : environ 55-70 crédits Higgsfield pour les 5 clips.

### Critères de validation pour chaque clip

- Le first frame correspond exactement à l'image générée à l'Acte 05
- Le last frame correspond exactement à l'image générée à l'Acte 05
- Le mouvement entre les deux est fluide, sans artefacts
- Pas de morphing du chef, de la cliente ou du décor
- Le timing correspond à la durée prévue

**Question de contrôle** : *Ces clips fonctionnent narrativement entre eux ?*

---

## Acte 08 — Montage et sound design

### Ordre des plans

Identique au découpage : Plan 01 → 02 → 03 → 04 → 05.

### Transitions entre plans

| Transition | Type | Raison |
|-----------|------|--------|
| Plan 01 → 02 | Cut sec avec match cut sur la chaleur | De l'extérieur chaud aux mains du chef chaud |
| Plan 02 → 03 | Cut sec | L'assiette quitte la cuisine, arrive en salle |
| Plan 03 → 04 | Match cut sur le plat | De l'assiette posée à la première bouchée |
| Plan 04 → 05 | Slow pull back (6 frames) | Du gros plan à l'ensemble |

Aucun fondu, aucun effet kitsch. La beauté est dans le découpage.

### Musique

Genre : **piano contemporain et cordes minimalistes**
BPM : 80-90 (calme mais avec énergie sous-jacente)
Référence sonore : *Max Richter - On The Nature of Daylight*, *Nils Frahm*, ou compositions de Nicholas Britell

Structure musicale :
- 0:00 - 0:03 : silence ambiant, ambiance urbaine
- 0:03 : entrée du piano en douceur au moment où la lumière s'allume
- 0:03 - 0:13 : montée progressive, cordes qui s'ajoutent
- 0:13 - 0:16 : moment de respiration sonore (Plan 04 : seule la rumeur du restaurant)
- 0:16 - 0:20 : retour du thème, fade-out sur les 2 dernières secondes

### Sound design par plan

- Plan 01 : ambiance urbaine lointaine, clic discret de l'allumage
- Plan 02 : son du poseur de truffe (très léger), souffle du chef à peine audible
- Plan 03 : pas du serveur, son léger de la porcelaine sur le bois, fumée silencieuse
- Plan 04 : ambiance restaurant en fond (conversations floues), tinte de la fourchette
- Plan 05 : retour à l'ambiance complète du restaurant, fade vers la musique seule

### Color grading final

- **Highlights** : tirés vers l'or chaud (+10% saturation jaune)
- **Shadows** : profondes mais avec détail, légèrement tirées vers le brun
- **Midtones** : peau et nourriture en tons chauds saturés
- **Black point** : crushed à -5 pour profondeur cinéma
- **Saturation globale** : conservée, légèrement boostée sur les rouges (vin, viandes)
- **Grain** : 35mm film grain à 6% d'intensité

### Texte et branding

- Logo L'ATELIER : apparition au Plan 05 à t = 17 secondes
- Baseline *"Ouverture le 15 octobre · Paris 11e"* : apparition à t = 18 secondes
- Réservation Instagram en bio uniquement, pas dans la vidéo

**Question de contrôle** : *Ça ressemble à une seule vidéo continue ?*

---

## Acte 09 — Livrable final

### Spécifications d'export

| Paramètre | Valeur |
|-----------|--------|
| Format conteneur | MP4 |
| Codec vidéo | H.264 |
| Ratio | 9:16 |
| Résolution | 1080 × 1920 |
| Frame rate | 24 fps |
| Bitrate vidéo | 35 Mbps |
| Codec audio | AAC |
| Bitrate audio | 320 kbps |
| Espace colorimétrique | Rec. 709 |

### Plateformes cibles

| Plateforme | Format | Notes |
|-----------|--------|-------|
| Instagram Reels | 9:16, 1080×1920 | Publier J-7 avant l'ouverture |
| TikTok | 9:16, 1080×1920 | Reposter J-5 |
| Stories Instagram | 9:16, 15s | Couper le Plan 04 pour rentrer |
| YouTube Shorts | 9:16, 1080×1920 | Publier J-3 |

### Métriques à suivre après publication

- Vue moyenne — objectif : 14 secondes minimum sur 20
- Save rate — métrique la plus importante (intention de venir)
- Profile visit rate après vidéo — objectif 5% minimum
- Conversion vers la réservation (Instagram bio link)

**Question de contrôle** : *L'export final est aux bonnes spécifications pour ta plateforme ?*

---

## Récapitulatif du projet

| Élément | Valeur |
|---------|--------|
| Durée totale | 20 secondes |
| Nombre de plans | 5 plans visuellement uniques |
| Frames générés | 10 (5 first + 5 last) — chacun unique |
| Clips vidéo | 5 |
| Temps de travail estimé | 4 à 6 heures |
| Crédits Higgsfield | ~70-100 |
| Coût en euros | environ 25 à 35€ |

### Comparaison avec une production traditionnelle

- Tournage avec équipe (réalisateur, directeur photo, chef, client modèle, serveur, ingénieur son) : 2 jours
- Post-production (montage, étalonnage, sound design) : 2 jours
- Budget total : **6 000 à 12 000€** pour ce niveau de qualité

La méthode du Réalisateur Artificiel produit un résultat comparable pour **environ 0,4% du coût** et **5% du temps**.

---

## Leçons à retenir de cet exemple

1. **Chaque frame est visuellement unique.** Aucune image n'est la copie d'une autre.
2. **La cohérence vient du texte des prompts, pas d'une image de référence.** Les consistency tokens (chef, restaurant, éclairage) se répètent mot pour mot.
3. **Les cadrages varient d'un plan à l'autre.** Extérieur, macro, plan moyen, gros plan, plan d'ensemble — c'est le découpage analytique du cinéma.
4. **Le first frame et le last frame d'un plan montrent une évolution claire** de l'action, pas une image identique.
5. **La signature stylistique s'adapte à la niche.** Restaurant = Hasselblad food photography. Pour le parfum ou la mode, ça serait différent.

Ces principes s'appliquent à n'importe quelle niche. Le sujet change, la méthode reste.

---

## À toi de jouer

Tu as maintenant vu un projet complet du début à la fin. Tu sais à quoi t'attendre, quelle qualité viser, et combien de temps prévoir.

Retourne dans ton Claude Project, et commence par lui dire ton idée en une phrase. La méthode prendra le relais.

---

*Document de référence pour la méthode du Réalisateur Artificiel.*
