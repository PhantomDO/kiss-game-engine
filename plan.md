# 🌳 Arbre de compétences – “Moteur KISS”

(Golden Path + quêtes secondaires avec priorité)

## Niveau 1 – Fondations visuelles

🎯 Objectif : Voir quelque chose à l’écran le plus vite possible.

### Compétence principale :

[Core Rendu] (Golden Path) → Initialiser l’API, afficher un triangle, puis un cube.

### Branches secondaires :
- 1️⃣ Charger un modèle 3D simple (ex. GLTF) – Priorité Haute
- 2️⃣ Matériaux simples (couleur, texture) – Priorité Haute
- 3️⃣ Ombres simples – Priorité Basse (car tu peux jouer sans ombres au début)

## Niveau 2 – Organisation des objets

🎯 Objectif : Pouvoir créer une scène structurée.

### Compétence principale :

[Gestion de Scène] (Golden Path) → Stocker, charger et manipuler les entités d’une scène.

### Branches secondaires :
- 1️⃣ Arbre hiérarchique parent/enfant – Priorité Haute
- 2️⃣ Multi-scènes – Priorité Moyenne
- 3️⃣ Chargement d’assets automatique – Priorité Basse

## Niveau 3 – Structure interne

🎯 Objectif : Avoir une architecture flexible et réutilisable.

### Compétence principale :

[ECS] (Golden Path) → Entités + composants + systèmes.

### Branches secondaires :
- 1️⃣ Inspecteur de composants – Priorité Haute (utile pour debug très vite)
- 2️⃣ Composants dynamiques (ajout/retrait à runtime) – Priorité Moyenne

## Niveau 4 – Vie et ambiance

🎯 Objectif : Donner vie à la scène avec son et physique.

### Compétences principales :

[Audio] (Golden Path) → Jouer sons/musiques.

[Physique] (Golden Path) → Gravité et collisions simples.

### Branches secondaires Audio :
- 1️⃣ Sons spatialisés 3D – Priorité Moyenne
- 2️⃣ Musique en streaming – Priorité Basse

### Branches secondaires Physique :
- 1️⃣ Triggers pour gameplay – Priorité Haute
- 2️⃣ Collisions avancées (mesh) – Priorité Basse

## Niveau 5 – Interaction et contrôle

🎯 Objectif : Permettre de voir et manipuler facilement les données.

### Compétence principale :

[UI] (Golden Path) → Afficher texte et boutons.

### Branches secondaires :
- 1️⃣ Système de layout – Priorité Moyenne
- 2️⃣ Skins personnalisés – Priorité Basse

## Niveau 6 – Création de gameplay

🎯 Objectif : Ajouter de la logique sans recompiler.

### Compétence principale :

[Scripting] (Golden Path) → Intégrer Lua ou Python.

### Branches secondaires :
- 1️⃣ Hot-reload de scripts – Priorité Haute
- 2️⃣ API scripting documentée – Priorité Moyenne

## Niveau 7 – Productivité

🎯 Objectif : Manipuler la scène visuellement.

### Compétence principale :

[Éditeur] (Golden Path) → Interface de placement et modification des entités.

### Branches secondaires :
- 1️⃣ Gizmos (déplacer/rotater/scaler) – Priorité Haute
- 2️⃣ Vue multi-fenêtres – Priorité Moyenne

## Niveau 8 – Multi

🎯 Objectif : Faire communiquer plusieurs instances.

### Compétence principale :

[Réseau] (Golden Path) → Client/serveur simple.

### Branches secondaires :
- 1️⃣ Prediction & interpolation – Priorité Moyenne
- 2️⃣ Chat in-game – Priorité Basse

---

## 📜 Golden Path Résumé

- Core Rendu
- Gestion de Scène
- ECS
- Audio + Physique
- UI
- Scripting
- Éditeur
- Réseau

Les quêtes secondaires hautes priorité sont faciles à intégrer au moment où tu débloques la compétence principale. Les autres peuvent attendre.
