## Analyse du vieillissement cérébral et des performances cognitives – OASIS-1

#### *Présentation*
Ce projet personnel consiste à analyser les relations entre l'âge, le volume cérébral et les performances cognitives à partir des données OASIS-1 (Open Access Series of Imaging Studies). <br>
L'objectif est de mettre en pratique différentes méthodes d'analyse statistique sur des données issues du domaine des neurosciences.

#### *Questions étudiées*
1. L'âge est-il associé au volume cérébral normalisé (nWBV) ?
2. Le volume cérébral est-il associé aux performances cognitives (MMSE) ?
3. Les performances cognitives diffèrent-elles selon le statut CDR ?

#### *Méthodes utilisées*
- Statistiques descriptives
- Corrélations de Pearson
- Test t de Student avec correction de Welch
- Visualisation des données

#### *Principaux résultats*
L'analyse met en évidence :<br>
- une forte corrélation négative entre l'âge et le volume cérébral normalisé (r = -0,874 ; p < 0,001) ;
- une corrélation positive modérée entre le volume cérébral et le score MMSE (r = 0,47 ; p < 0,001) ;
- des scores MMSE significativement plus élevés chez les participants avec un CDR = 0 que chez ceux avec un CDR > 0 (p < 0,001). <br>
Ces résultats décrivent des associations et ne permettent pas d'établir de relation causale.

#### *Données*
Les données utilisées proviennent du jeu de données OASIS-1 (Open Access Series of Imaging Studies), développé par la Washington University in St. Louis. <br>

#### *Fichier*
**etude_oasis.ipynb** : notebook contenant la préparation des données, les analyses statistiques, les visualisations et l'interprétation des résultats.
