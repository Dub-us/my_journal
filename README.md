# my_journal
Nom du projet : SRP (nom temporaire)

Description du concept :

SRP est une application-jeu mobile à visée introspective et artistique. L’objectif est de transformer les ressentis et événements quotidiens d’un·e utilisateur·rice en une image visuelle unique, construite autour d’une maison et de son jardin.

Le jeu ne comporte qu’un seul écran principal : une scène illustrée extérieure montrant une maison et son environnement immédiat (ciel, sol, plantes, objets, etc.). Cette scène est personnalisée à chaque session selon les choix de l’utilisateur·rice.

Fonctionnement général :

1. L’utilisateur sélectionne plusieurs éléments à partir de différentes catégories :
   - Émotions ressenties (ex : joie, fatigue, angoisse)
   - Activités réalisées (ex : sport, lecture, travail)
   - Interactions sociales (ex : solitude, rencontre importante)
   - Événements de la journée (ex : facture, cadeau, dispute)
   - Ressenti énergétique (ex : vidé, plein d’énergie)
   - Météo intérieure ou ambiance (ex : nuageux, clair, orageux)

2. À partir de ces choix, le jeu affiche une scène visuelle où :
   - Des objets ou effets visuels s’ajoutent ou se modifient dans la scène (pluie, papillons, cœur dans le ciel, herbe sèche, boîte aux lettres pleine, etc.)
   - L’ensemble est pensé pour être cohérent, beau et harmonieux visuellement, dans un style graphique défini.

Spécificités artistiques :

- Toutes les illustrations et objets (maison, plantes, décor, effets météo...) sont **créés manuellement par la créatrice du jeu**, dans un style visuel esthétique, doux et stylisé. Les images sont ensuite intégrées dans le projet (format PNG recommandé pour la transparence).
- Le but est de produire une **image finale belle, poétique et expressive**, comme une carte postale émotionnelle de la journée.

⚙️ Technologies recommandées pour ce projet :

- **HTML5 + JavaScript** avec l'API **Canvas** pour gérer facilement les images, les animations légères (ex : pluie qui tombe doucement), et les interactions simples.
- Utilisation possible de **Vanilla JavaScript** pour garder un projet léger et facile à comprendre.
- Compatible avec **GitHub Copilot**, qui pourra générer automatiquement le code pour :  
  - Afficher les images selon les catégories choisies  
  - Gérer la superposition (couches) des objets  
  - Ajouter de petites animations (gouttes de pluie, brume, etc.)  
  - Générer une capture de l’image finale (avec `canvas.toDataURL()` par exemple)

🗂 Structure attendue du projet :
- `/assets/` → dossier contenant toutes les images créées manuellement (PNG transparents)
- `/js/` → scripts pour afficher les scènes et gérer les interactions
- `index.html` → page principale du jeu
- `style.css` → pour le style minimal de l’interface
- `README.md` → pour documenter le fonctionnement

Objectif principal :

Créer une expérience visuelle simple, introspective et artistique, qui valorise les ressentis quotidiens par l’image plutôt que par le texte. Une sorte de “journal émotionnel illustré” généré en quelques clics, pour favoriser la reconnexion à soi et le calme.

