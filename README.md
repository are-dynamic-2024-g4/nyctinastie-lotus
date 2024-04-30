# Exploration de la Nyctinastie chez le Lotus Sacré

## Bienvenue sur notre Plateforme d'Étude !
Découvrez notre projet dédié à l'étude et à la modélisation de la nyctinastie chez le Lotus Sacré (Nelumbo nucifera). Nous vous présentons une suite d'outils et de fonctionnalités conçus pour explorer ce phénomène biologique complexe.

## Présentation de l'équipe

| Ait Taleb Rachel | Boukrif Liza | Lalaoui Lena| Manegabe David |

### À Propos de la Nyctinastie :

La nyctinastie est un phénomène biologique observé chez de nombreuses plantes, caractérisé par des mouvements de fermeture et d'ouverture de leurs organes en réponse à des variations de luminosité et d'autres facteurs environnementaux. Notre objectif est de comprendre et de modéliser ces mécanismes chez le Lotus Sacré.
<a href="https://www.pexels.com/fr-fr/photo/nature-fleurs-plantes-centrales-19845796/">
  <img src="https://zupimages.net/up/19/13/jrzz.png" alt="">
</a>



### Problématique :

Pourquoi et comment le Lotus Sacré modifie-t-il le mouvement de ses pétales en réponse à des stimuli externes tels que la température et la luminosité ou l'heure du jour ? Pour répondre à cette question, nous examinons plusieurs facteurs qui influent sur la nyctinastie chez le Lotus Sacré :

- **Luminosité / Heure du Jour :** Bien que la luminosité soit un facteur important, notre étude accorde une importance particulière à l'heure du jour comme principal déterminant de la nyctinastie.  En quoi l'heure du jour influence-t-elle les mouvements nyctinastiques du Lotus Sacré ?
- **Température :** Nous analysons également l'impact de la température sur la nyctinastie de cette plante.
- **Saisonnalité :** Nous explorons le rôle de la saisonnalité dans la régulation de la nyctinastie, en tenant compte des variations climatiques tout au long de l'année

### Objectif de notre projet :

Nous visons à fournir une plateforme complète pour l'analyse et la modélisation de la nyctinastie chez le Lotus Sacré. Pour ce faire, nous avons développé un ensemble d'outils mathématiques et techniques pour étudier les réponses nyctinastiques de cette plante.

### Progression logique de l'algorithme
La procédure commence par la collecte de données climatiques régionales où pousse le lotus, cruciales pour comprendre les réactions nyctinastiques du lotus sacré en fonction de son environnement. L'analyse de la corrélation entre ces variables et les mouvements nyctinastiques des feuilles est effectuée pour déterminer comment la température influence ces mouvements. 
- Les **données climatiques** alimentent directement l'**analyse de corrélation**, qui à son tour est essentielle pour paramétrer et ajuster les **modèles mathématiques** qui simulent le comportement nyctinastique.
- Les résultats de l'**analyse de corrélation** et de l'**interpolation linéaire** aident à peaufiner les modèles qui prédisent les taux d'ouverture basés sur la température.
- Les **modèles de taux d'ouverture** influencent la façon dont les **graphiques temporels** sont interprétés et présentés, fournissant un aperçu complet de la dynamique diurne et saisonnière des mouvements nyctinastiques.
La modélisation mathématique s'appuie sur des techniques statistiques pour évaluer les corrélations entre les variables climatiques et la nyctinastie. Le code Python utilise des bibliothèques Matplotlib, NumPy et Turtle pour traiter les données et visualiser les résultats.

### Modélisation temporelle de la nyctinastie
La modélisation se concentre sur la simulation des réactions nyctinastiques du lotus sacré (Nelumbo nucifera) aux variations environnementales dans le temps. Les variations journalières de nyctinastie sont modélisées pour comprendre comment les ouvertures fluctuent au cours de la journée.
- **Interpolation linéaire** (`lineariser_donnees`) pour prédire le taux d'ouverture à des températures non mesurées directement, en utilisant les données existantes pour estimer des valeurs intermédiaires. Cela utilise typiquement une formule d'interpolation linéaire où étant la température et le taux d'ouverture.
- **Fonction `nyctinastie_periode_journalier(periode, donnees_temperature, ov_nyctinastie, tp_nyctinastie, jf, debut_fleuraison, fin_fleuraison)`** : Calcule les paramètres de nyctinastie pour chaque heure d'un jour spécifique, fournissant une analyse détaillée du comportement nyctinastique sur une base journalière.   
- **Fonction `nyctinastie_moyenne_mensuelle(mois, donnees_temperature, ov_nyctinastie, tp_nyctinastie, jf, debut_fleuraison, fin_fleuraison)`** et **Fonction `nyctinastie_max_mensuelle(mois, donnees_temperature, ov_nyctinastie, tp_nyctinastie, jf, debut_fleuraison, fin_fleuraison)`** : Calculent respectivement les moyennes et les valeurs maximales mensuelles pour le taux d'ouverture, la vitesse et la température.
- **Fonction `nyctinastie_dans_annee(donnees_temperature, ov_nyctinastie, tp_nyctinastie, jf, debut_fleuraison, fin_fleuraison)`** : Aggrège les données nyctinastiques pour chaque mois de l'année, utilisé pour évaluer les variations saisonnières de la nyctinastie.

### Visualisation des données
   - **Fonction `visualiser_lotus(taux_ouverture, vitesse_ouverture)`** : Utilise la bibliothèque Turtle pour dessiner une représentation graphique de la fleur de lotus en fonction de son état d'ouverture et de la vitesse d'ouverture, illustrant visuellement l'effet de ces paramètres.
   - **Fonction `graphique_nyctinastie_journaliere(dataset, periode, j)`** : Crée un graphique des données nyctinastiques journalières, affichant le taux d'ouverture, la vitesse d'ouverture, et la température en fonction de l'heure de la journée.
   - **Fonction `afficher_evolution_annuelle_nyctinastie(moyennes_annuelles)`** : Crée un graphique combiné montrant à la fois le taux d'ouverture et la température moyenne au cours de l'année, donnant une vue d'ensemble de l'activité nyctinastique sur une base annuelle.

### Comment Commencer ?

Pour débuter votre exploration de la nyctinastie chez le Lotus Sacré, téléchargez le notebook Jupyter contenant nos fonctions et outils de modélisation. Vous trouverez le lien de téléchargement dans le dossier principal de notre dépôt GitHub.

### Consulter notre blog : <a href="https://are-dynamic-2024-g4.github.io/nyctinastie-lotus" target="_blank"> C'est ici ! </a>

### Documentation des Fonctions :

Pour accéder à la documentation complète de toutes les fonctions que nous avons développées pour l'étude de la nyctinastie chez le Lotus Sacré, veuillez consulter notre wiki sur GitHub. Vous y trouverez des explications détaillées sur chaque fonction, y compris leurs descriptions, paramètres d'entrée, et exemples d'utilisation.

[Accéder à la documentation des fonctions](https://github.com/are-dynamic-2024-g4/nyctinastie-lotus/wiki)

Explorez notre wiki pour obtenir des informations approfondies sur la manière d'utiliser nos outils de modélisation, d'analyse et de visualisation. Que vous soyez un étudiant ou un passionné de botanique, notre documentation vous aidera à tirer le meilleur parti de notre plateforme d'étude de la nyctinastie du Lotus Sacré.

Rejoignez-nous dans cette aventure scientifique alors que nous explorons les subtilités de la nyctinastie du Lotus Sacré !

## Bibliographie :

**Carte mentale de vos mots-clés, en utilisant** <a href="https://framindmap.org/mindmaps/index.html">Framindmap </a> 

Liste de l'ensemble des ressources bibliographiques utilisées pour vos travaux. **<= Indiquez le canal utilisé pour les trouver (Google Scholar, sources wikipedia, ressources en ligne SU, ...)**
