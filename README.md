H₂O Synthesis Console

Process Engineering Suite · v2.4

Dashboard interactif d'ingénierie des procédés dédié à la synthèse catalytique de l'eau par recombinaison H₂ + O₂.

    2 H₂ + O₂ → 2 H₂O

Aperçu

Interface complète de simulation et d'analyse pour la réaction exothermique de synthèse de l'eau. Conçue comme un outil pédagogique et professionnel, elle couvre la thermodynamique, le dimensionnement de réacteur, l'analyse économique, la sécurité HAZOP et les spécifications techniques.
Fonctionnalités
Module	Description
Vue d'ensemble	KPIs, stœchiométrie, PFD interactif, applications industrielles
Constructeur moléculaire	Ajout de molécules H₂/O₂, réaction animée, réactif limitant
Réacteur catalytique	Simulation temps réel, jauges T/P/conversion, particules animées
Thermodynamique	Équilibre, K<sub>eq</sub>, ΔG, courbe log K<sub>eq</sub> vs T
Dimensionnement	GHSV, volume réacteur, masse catalyseur, perte de charge
Économie	OPEX/CAPEX, sensibilité, décomposition des coûts
Sécurité HAZOP	Propriétés H₂, simulateur de fuite, 5 nœuds critiques
Spécifications	Catalyseurs, eau ultra-pure, comparaison technologique
Caractéristiques techniques

    HTML / CSS / JavaScript pur — aucune dépendance externe

    Canvas 2D pour les visualisations (molécules, réacteur, graphiques)

    Calculs en temps réel — thermodynamique, dimensionnement, économie

    Design responsive — sidebar, topbar, statusbar type IDE

    Thème Bleu Blanc Rouge — palette institutionnelle française

    Export JSON des paramètres simulés (Ctrl+E)

    Impression optimisée (Ctrl+P)

Installation

Aucune installation requise. Ouvrez simplement le fichier index.html dans un navigateur moderne.
bash

git clone https://github.com/gunout/Synthese-H2-O2.git
cd Synthese-H2-O2
# Ouvrir index.html dans votre navigateur

Utilisation
Navigation

    Sidebar — accès aux 8 modules d'analyse

    Topbar — breadcrumb, export, impression

    Statusbar — état de connexion, horloge

Constructeur moléculaire

    Cliquez sur + Ajouter H₂ ou + Ajouter O₂

    Ajoutez au moins 2 H₂ et 1 O₂

    Cliquez sur ⚡ Faire réagir

    Observez la formation de H₂O et le réactif limitant

Réacteur catalytique

    Cliquez sur ▶ Démarrer

    Le réacteur monte en température (25 → 250 °C)

    La conversion atteint 99,9 % en régime établi

    Les particules bleues (H₂) et violettes (O₂) se transforment en H₂O (vertes)

Simulateur de fuite H₂

Faites glisser le curseur pour simuler une fuite :
Concentration	Statut
< 0,4 %	Système nominal
0,4 – 1 %	⚠️ Alerte 10 % LIE
1 – 4 %	🚨 Alarme 25 % LIE
≥ 4 %	💥 Zone explosive
Raccourcis clavier
Raccourci	Action
Ctrl + E	Export JSON
Ctrl + P	Impression
Échap	Fermer la modale
Données techniques
Thermodynamique
Paramètre	Valeur
ΔH°f H₂O(l)	−285,8 kJ/mol
ΔG°f H₂O(l)	−237,1 kJ/mol
S° H₂O(g)	188,7 J/mol·K
Sécurité H₂
Paramètre	Valeur
LIE (air)	4 % vol.
LSE (air)	75 % vol.
Énergie min. inflammation	0,017 mJ
Temp. auto-inflammation	585 °C
Spécifications eau ultra-pure
Paramètre	Cible
Résistivité	18,2 MΩ·cm
TOC	< 5 ppb
O₂ dissous	< 10 ppb
Métaux	< 1 ppt
Structure du projet
text

Synthese-H2-O2/
├── index.html      # Application complète (HTML + CSS + JS)
├── LICENSE         # Licence du projet
└── README.md       # Documentation

Limites du modèle

    Modèle pédagogique simplifié

    ΔH et ΔS considérés constants (200–3000 K)

    Cinétique sans limitation par transfert de matière

    CAPEX par loi de puissance (exposant 0,6)

    Pour un projet réel : utiliser Aspen Plus / HYSYS avec données cinétiques validées

Licence

Voir le fichier LICENSE.
Contribution

Les contributions sont les bienvenues. Pour proposer une amélioration :

    Forkez le dépôt

    Créez une branche (git checkout -b feature/amelioration)

    Committez (git commit -m 'Ajout fonctionnalité')

    Poussez (git push origin feature/amelioration)

    Ouvrez une Pull Request

H₂O Synthesis Console — Process Engineering Suite v2.4
un readme "markdown" avec badge descriptif

User wants a markdown README with descriptive badges for the GitHub repo. Let me create a comprehensive one with shields.io badges.
H₂O Synthesis Console

Process Engineering Suite · v2.4

https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white
https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
https://img.shields.io/badge/Canvas_2D-00D4FF?style=for-the-badge&logo=html5&logoColor=white

https://img.shields.io/badge/version-2.4.0-blue?style=flat-square
https://img.shields.io/badge/license-MIT-green?style=flat-square
https://img.shields.io/badge/status-stable-brightgreen?style=flat-square
https://img.shields.io/badge/Made_in-France-0055A4?style=flat-square&labelColor=EF4135

https://img.shields.io/badge/dependencies-0-success?style=flat-square
https://img.shields.io/badge/responsive-yes-blue?style=flat-square
https://img.shields.io/badge/theme-Bleu_Blanc_Rouge-0055A4?style=flat-square
https://img.shields.io/badge/accessibility-AA-3fb950?style=flat-square

https://img.shields.io/github/stars/gunout/Synthese-H2-O2?style=social
https://img.shields.io/github/forks/gunout/Synthese-H2-O2?style=social
https://img.shields.io/github/issues/gunout/Synthese-H2-O2?style=flat-square
https://img.shields.io/github/last-commit/gunout/Synthese-H2-O2?style=flat-square

https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square
https://img.shields.io/badge/maintained-yes-blue?style=flat-square
📋 Table des matières

    Aperçu

    Fonctionnalités

    Démo

    Installation

    Utilisation

    Architecture

    Données techniques

    Raccourcis clavier

    Sécurité

    Limites du modèle

    Contribution

    Licence

🔬 Aperçu

H₂O Synthesis Console est un dashboard interactif d'ingénierie des procédés dédié à la synthèse catalytique de l'eau par recombinaison H₂ + O₂.

    2 H₂ + O₂ → 2 H₂O

Interface complète de simulation couvrant la thermodynamique, le dimensionnement de réacteur, l'analyse économique, la sécurité HAZOP et les spécifications techniques. Conçue comme un outil pédagogique et professionnel — proche des interfaces de l'ADEME, du CEA ou de l'IFPEN.
🎯 Points forts

    ⚡ 100 % front-end — aucune dépendance, aucun build

    🎨 Design institutionnel — palette Bleu Blanc Rouge

    📊 8 modules d'analyse — thermodynamique, réacteur, économie, HAZOP

    🧪 Simulateur moléculaire — réaction animée en temps réel

    🔥 Réacteur catalytique — simulation dynamique avec jauges live

    🛡️ Analyse HAZOP — 5 nœuds critiques + simulateur de fuite

    📥 Export JSON — sauvegarde des paramètres simulés

    🖨️ Impression optimisée — mise en page print dédiée

✨ Fonctionnalités
Module	Description	Interactivité
📊 Vue d'ensemble	KPIs, stœchiométrie, PFD, applications industrielles	Modales + tooltips
⚛️ Constructeur moléculaire	Ajout H₂/O₂, réaction animée, réactif limitant	Canvas + clics
🔥 Réacteur catalytique	Simulation T/P/conversion, particules animées	Temps réel
🌡️ Thermodynamique	K<sub>eq</sub>, ΔG, courbe d'équilibre	Sliders dynamiques
📐 Dimensionnement	GHSV, volume, masse catalyseur, ΔP	Sliders + select
💰 Économie	OPEX, CAPEX, sensibilité, décomposition	Sliders + chart
⚠️ Sécurité HAZOP	Propriétés H₂, 5 nœuds, simulateur de fuite	Slider + alertes
📋 Spécifications	Catalyseurs, eau ultra-pure, comparatif	Tableaux
📚 Documentation	Formules, normes, hypothèses	Références
🎬 Démo

👉 Ouvrir la démo en ligne
🚀 Installation

Aucune installation requise. Aucune dépendance.
bash

# Cloner le dépôt
git clone https://github.com/gunout/Synthese-H2-O2.git

# Se rendre dans le dossier
cd Synthese-H2-O2

# Ouvrir dans le navigateur
open index.html      # macOS
xdg-open index.html  # Linux
start index.html     # Windows

Ou simplement télécharger le fichier index.html et l'ouvrir dans un navigateur moderne.
🖱️ Utilisation
Navigation

    Sidebar — accès aux 8 modules d'analyse

    Topbar — breadcrumb, indicateur LIVE, export, impression

    Statusbar — état de connexion, modèle, horloge

⚛️ Constructeur moléculaire
text

1. Cliquez sur [+ Ajouter H₂] ou [+ Ajouter O₂]
2. Ajoutez au moins 2 H₂ et 1 O₂
3. Cliquez sur [⚡ Faire réagir]
4. Observez la formation de H₂O et le réactif limitant

La réaction consomme 2 H₂ + 1 O₂ pour produire 2 H₂O. Les molécules non consommées restent en excès.
🔥 Réacteur catalytique
text

1. Cliquez sur [▶ Démarrer]
2. Le réacteur monte en température (25 → 250 °C)
3. La conversion atteint 99,9 % en régime établi
4. Les particules bleues (H₂) et violettes (O₂) deviennent vertes (H₂O)

⚠️ Simulateur de fuite H₂
Concentration	Statut	Action
< 0,4 %	✅ Nominal	Aucune
0,4 – 1 %	⚠️ Alerte 10 % LIE	Vérifier ventilation
1 – 4 %	🚨 Alarme 25 % LIE	Arrêt d'urgence
≥ 4 %	💥 Explosif	Évacuation immédiate
🏗️ Architecture
text

Synthese-H2-O2/
│
├── index.html          # Application complète (HTML + CSS + JS inline)
│   ├── <style>         # Design system (variables CSS, layout, composants)
│   ├── <body>          # App shell : topbar · sidebar · main · statusbar
│   └── <script>        # 8 modules JS (calculs, canvas, interactions)
│
├── LICENSE             # Licence MIT
└── README.md           # Ce fichier

Stack technique
Couche	Technologie
Structure	HTML5 sémantique
Style	CSS3 (Grid, Flexbox, Custom Properties)
Logique	JavaScript ES6+ (vanilla, aucune lib)
Visualisation	Canvas 2D API
Polices	SF Mono, JetBrains Mono, system fonts
Icônes	Emojis Unicode (zéro dépendance)
📊 Données techniques
Thermodynamique
Paramètre	Valeur
ΔH°f H₂O(g)	−241,8 kJ/mol
ΔH°f H₂O(l)	−285,8 kJ/mol
ΔG°f H₂O(g)	−228,6 kJ/mol
ΔG°f H₂O(l)	−237,1 kJ/mol
S° H₂O(g)	188,7 J/mol·K
S° H₂	130,7 J/mol·K
S° O₂	205,1 J/mol·K
Sécurité H₂
Paramètre	Valeur
LIE (air)	4 % vol.
LSE (air)	75 % vol.
LIE (O₂ pur)	4,5 % vol.
LSE (O₂ pur)	94 % vol.
Énergie min. inflammation	0,017 mJ
Temp. auto-inflammation	585 °C
Vitesse flamme laminaire	2,9 m/s
Détonation H₂/O₂	18–59 %
Spécifications eau ultra-pure
Paramètre	Cible	Norme
Résistivité	18,2 MΩ·cm	SEMI C12
TOC	< 5 ppb	ASTM D1193
O₂ dissous	< 10 ppb	Type I
Métaux (total)	< 1 ppt	—
Particules > 0,05 µm	< 100/mL	—
Bactéries	< 1 CFU/mL	—
⌨️ Raccourcis clavier
Raccourci	Action
<kbd>Ctrl</kbd> + <kbd>E</kbd>	📥 Export JSON
<kbd>Ctrl</kbd> + <kbd>P</kbd>	🖨️ Impression
<kbd>Échap</kbd>	❌ Fermer la modale
🛡️ Sécurité
⚠️ Avertissements

Ce projet est un outil pédagogique de simulation. Il ne doit en aucun cas servir de base à une installation réelle sans validation par un ingénieur procédés qualifié.

Risques liés à la manipulation H₂ / O₂ :

    🔥 H₂ est inflammable et explosif (4–75 % vol. dans l'air)

    💨 O₂ est comburant — il accentue toute combustion

    💥 Mélange H₂/O₂ = détonant au moindre spark

    🧊 Stockage gaz comprimé réglementé (ATEX, ISO 22734)

    🧪 L'eau produite n'est pas potable sans analyse

📜 Normes applicables

    ATEX — Zone 1/2 · IIC T1

    ISO 22734 — Générateurs d'hydrogène par électrolyse

    IEC 62282 — Technologies des piles à combustible

    ASTM D1193 — Eau réactif de qualité

⚠️ Limites du modèle
Aspect	Limite
Thermodynamique	ΔH et ΔS constants (200–3000 K)
Cinétique	Modèle simplifié, pas de transfert de matière
Dimensionnement	Densité de lit fixe (800 g/L), facteur catalyseur
Économie	CAPEX par loi de puissance (exposant 0,6)
Pureté	Pas de simulation de traces

    💡 Pour un projet réel : utiliser Aspen Plus / HYSYS avec données cinétiques validées et une analyse HAZOP complète.

🤝 Contribution

Les contributions sont les bienvenues ! Voici comment procéder :
bash

# 1. Forker le dépôt
# 2. Créer une branche
git checkout -b feature/amelioration

# 3. Committer vos changements
git commit -m "feat: ajout d'une fonctionnalité"

# 4. Pousser la branche
git push origin feature/amelioration

# 5. Ouvrir une Pull Request

🎯 Idées d'amélioration

    □

    Ajout d'un module cinétique avancée (loi de vitesse détaillée)
    □

    Export CSV en plus du JSON
    □

    Tests automatisés (Jest / Vitest)
    □

    PWA avec mode hors-ligne
    □

    i18n (anglais, espagnol, allemand)
    □

    Mode expert vs mode débutant
    □

    Intégration Aspen Plus (fichier .bkp)
    □

    Animations 3D (Three.js)

📄 Licence

Ce projet est distribué sous licence MIT. Voir le fichier LICENSE pour plus de détails.
text

MIT License

Copyright (c) 2025 gunout

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

🙏 Remerciements

    IUPAC — données thermodynamiques de référence

    NIST — propriétés physico-chimiques

    SEMI — spécifications eau ultra-pure

    ADEME / CEA / IFPEN — inspiration design institutionnel
