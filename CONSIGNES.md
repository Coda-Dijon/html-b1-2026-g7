---
layout: default
title: Consignes
---

# Projets de groupe

- **Durée** : 4 jours
- **Groupes** : 3-4 personnes
- **Evaluation** :
    - 40% : Livrables
    - 35% : Démo groupe: capacité du groupe à expliquer ses choix et son code
    - 25% : Individuel : questions solo et challenges individuels

## Déroulé

| Jour            | Plage horaire | Activité                                                    |
|-----------------|---------------|-------------------------------------------------------------|
| Lundi 23 nov    | Après-midi    | Composition des groupes, logistique Git, inspiration sujets |
| Mardi 24 nov    | Journée       | Présentation du projet, barème, début du travail (Jour 1)   |
| Mercredi 25 nov | Journée       | Démos, travail en groupe (Jour 2)                           |
| Jeudi 26 nov    | Journée       | Démos, finalisation, préparation soutenance (Jour 3)        |
| Vendredi 27 nov | Journée       | Dernières démos, soutenances, évaluation (Jour 4)           |

## Livrable (40% de la note totale)

**Repères de niveau**

- **0 — Absent ou inutilisable :** le critère n'est pas présent, ou ne peut pas être évalué parce qu'il ne fonctionne pas.
- **1 — Très incomplet :** quelques éléments sont en place, mais le critère est majoritairement non satisfait.
- **2 — Partiel :** résultat compréhensible, mais avec des lacunes visibles ou des incohérences.
- **3 — Attendu atteint :** résultat fonctionnel et approprié pour le niveau du cours.
- **4 — Solide :** résultat particulièrement cohérent, soigné ou robuste ; les détails renforcent l'expérience sans être indispensables.

### Pages et contenus (5 points)

| Numéro de critère | Nombre de points | Nom                          | Description                                                                                              | Comment vérifier                                                                                               |
|-------------------|-----------------:|------------------------------|----------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| P1                |                1 | Nombre de pages              | Le site comporte au moins trois pages distinctes et pertinentes.                                         | Ouvrir la navigation et vérifier que trois pages différentes sont accessibles.                                 |
| P2                |                1 | Page d’accueil               | Le site comprend une page d’accueil identifiable.                                                        | Vérifier qu’une page d’accueil est présente et accessible depuis la navigation.                                |
| P3                |                1 | Crédits du groupe et membres | Une page de présentation indique le nom du groupe et de ses membres.                                     | Vérifier que le nom du groupe et des membres apparaît sur une page du site.                                    |
| P4                |                1 | Liens de référence           | Le site contient un lien vers la page Speedlify du projet et un lien de validation W3C pour chaque page. | Cliquer sur chaque lien et vérifier qu'il mène à la bonne page ou au bon résultat de validation.               |
| P5                |                1 | Navigation cohérente         | Toutes les pages partagent une navigation commune avec les mêmes liens vers les autres pages.            | Ouvrir chaque page et vérifier que la navigation est présente et que les liens mènent aux bonnes destinations. |

### Images (3 points)

| Critère                      | Max. | Niveau (0-4) | Points | Observations |
|------------------------------|------|--------------|--------|--------------|
| I1 — Images pertinentes      | 1    |              |        |              |
| I2 — Alternatives textuelles | 2    |              |        |              |

### Structure et sémantique (5 points)

| Critère                          | Max. | Niveau (0-4) | Points | Observations |
|----------------------------------|------|--------------|--------|--------------|
| S1 — Régions de page (landmarks) | 1    |              |        |              |
| S2 — Balises sémantiques         | 1    |              |        |              |
| S3 — Hiérarchie des titres       | 1    |              |        |              |
| S4 — Noms des liens              | 1    |              |        |              |
| S5 — Sections sémantiques        | 1    |              |        |              |

### Style et mise en page (9 points)

| Critère                   | Max. | Niveau (0-4) | Points | Observations |
|---------------------------|------|--------------|--------|--------------|
| M1 — Flexbox ou Grid      | 5    |              |        |              |
| M2 — Sélecteurs variés    | 1    |              |        |              |
| M3 — Combinateurs         | 1    |              |        |              |
| M4 — Sélecteur d'attribut | 1    |              |        |              |
| M5 — Variables CSS        | 1    |              |        |              |

### Accessibilité et affichage adaptatif (10 points)

| Numéro de critère | Nombre de points | Nom                     | Description                                                                                                                                                                        | Comment vérifier                                                                                                                                               |
|-------------------|-----------------:|-------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A1                |                4 | Responsive et adaptatif | Le contenu s’adapte aux différentes largeurs d’écran sans perte d’information, s’affiche correctement à 350 × 650 px sans défilement horizontal et reste utilisable au zoom 200 %. | Tester les pages sur petit et grand écran, à 350 × 650 px et au zoom 200 %, et vérifier que tout le contenu et toutes les fonctionnalités restent accessibles. |
| A2                |                3 | Media queries           | Le CSS utilise des media queries pour adapter la mise en page à différentes largeurs d'écran.                                                                                      | Rechercher `@media` dans le CSS et vérifier qu'au moins une media query est présente et fonctionnelle.                                                         |
| A3                |                2 | Approche mobile first   | Le CSS prévoit d’abord une mise en page pour petit écran, puis des adaptations pour les écrans plus larges.                                                                        | Examiner la feuille CSS et vérifier que les règles de base ciblent les petits écrans et que les adaptations plus larges sont ajoutées ensuite.                 |
| A4                |                1 | Lisibilité des couleurs | Les couleurs de texte et de fond offrent un contraste suffisant pour une lecture confortable sur toutes les pages.                                                                  | Vérifier avec le color picker des DevTools Chrome ou l'extension « WCAG Color Contrast Checker ».                                                                       |

### Éco-conception (3 points)

| Numéro de critère | Nombre de points | Nom               | Description                                                                                              | Comment vérifier                                                                                                                                            |
|-------------------|-----------------:|-------------------|----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| E1                |                3 | Images optimisées | Le format, le poids et les dimensions des images sont adaptés à leur usage et à leur taille d’affichage. | Vérifier les fichiers et leur affichage : chaque image doit utiliser un format adapté, avoir des dimensions raisonnables et ne pas être inutilement lourde. |

L’utilisation de `<picture>` ou de `srcset` peut être proposée comme amélioration facultative, sans incidence sur le score.

### Mesure et qualité (5 points)

| Numéro de critère | Nombre de points | Nom                       | Description                                                                           | Comment vérifier                                                                            |
|-------------------|-----------------:|---------------------------|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| Q1                |                3 | Validation HTML           | Toutes les pages sont vérifiées avec le validateur W3C et ne comportent pas d’erreur. | Consulter le résultat du validateur pour chaque page : aucune erreur ne doit être signalée. |
| Q2                |                1 | Liens fonctionnels        | Le site ne contient pas de lien mort.                                                 | Cliquer sur chaque lien interne et externe et vérifier que sa destination fonctionne.       |
| Q3                |                1 | Feuille de style partagée | Une même feuille de style CSS est réutilisée sur toutes les pages.                    | Vérifier que chaque page référence le fichier CSS commun du projet.                         |

### JavaScript (pénalité)

| Numéro de critère | Pénalité | Nom                       | Description                                                                                            | Comment vérifier                                                                          |
|-------------------|---------:|---------------------------|--------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| J1                |       -2 | Utilisation de JavaScript | Pénalité de 2 points si le projet utilise du JavaScript, sauf si cela a été suggéré par le professeur. | Vérifier la présence de fichiers JavaScript ou de code JavaScript intégré dans les pages. |

## Démos en groupe (35% de la note totale)

Les démos ont lieu chaque jour de projet, y compris le dernier jour sous forme
de soutenance. Chaque groupe présente son avancement, explique ses choix
techniques et répond aux questions du professeur. L'évaluation porte sur
l'ensemble des démos, pas sur une seule.

Le dernier jour, la soutenance (10 min par groupe) compte comme la dernière démo
et est évaluée avec les mêmes critères D1–D5.

**Repères de niveau**

- **0 — Pas de preuve observée**
- **1 — Compréhension très fragile, même avec aide**
- **2 — Compréhension partielle ; la personne avance avec des indications**
- **3 — Réponse ou démarche appropriée de façon autonome**
- **4 — Explication claire, raisonnement solide ou transfert pertinent à une autre situation**

| Numéro de critère | Nombre de points | Nom                                 | Description                                                                                       | Comment vérifier                                                                                  |
|-------------------|-----------------:|-------------------------------------|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| D1                |                8 | Fonctionnalité montrée et évolution | Le groupe démontre des fonctionnalités concrètes et montre que le projet évolue entre les démos.  | Observer les démos et vérifier que le site progresse de manière visible d'une démo à l'autre.     |
| D2                |                8 | Explication des choix               | Le groupe explique clairement ses choix de conception, de structure et de style.                  | Écouter les explications et vérifier que les justifications sont claires et pertinentes.          |
| D3                |                6 | Compréhension des concepts          | Le groupe montre qu'il comprend les concepts du cours (HTML sémantique, CSS, responsive, etc.).   | Poser des questions sur le code et vérifier que les réponses montrent une compréhension réelle.   |
| D4                |                6 | Diagnostic et correction            | Le groupe identifie ses blocages, propose des solutions et applique les corrections suggérées.    | Observer comment le groupe réagit face aux problèmes et aux suggestions du professeur.            |
| D5                |                7 | Progression entre les démos         | Le groupe montre une progression continue et une amélioration visible du projet au fil des jours. | Comparer les démos successives et vérifier que les retours sont intégrés et que le projet avance. |

## Évaluation en individuel (25% de la note totale)

**Repères de niveau**

- **0 — Pas de preuve observée**
- **1 — Compréhension très fragile, même avec aide**
- **2 — Compréhension partielle ; la personne avance avec des indications**
- **3 — Réponse ou démarche appropriée de façon autonome**
- **4 — Explication claire, raisonnement solide ou transfert pertinent à une autre situation**

L'évaluation individuelle porte sur la maîtrise personnelle des concepts du cours, observée pendant les démos et par des questions posées à chaque étudiant. Pour chaque critère, le professeur attribue un niveau de 0 à 4, puis calcule : **points obtenus = maximum du critère × niveau ÷ 4**. Des demi-points peuvent être utilisés.

Les évaluations individuelles sont réparties sur les Jours 2 à 4 : la partie « Question individuelle » de chaque démo (2 min) sert de base, complétée par des entretiens plus longs si nécessaire. Cela permet de ne pas concentrer toutes les évaluations le dernier jour.

| Numéro de critère | Nombre de points | Nom                                      | Description                                                                                      | Comment vérifier                                                                                  |
|-------------------|-----------------:|------------------------------------------|--------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| I1                |                7 | Expliquer un choix réalisé par le groupe | L'étudiant explique clairement un choix technique ou de conception qu'il a contribué à faire.    | Poser des questions ciblées sur le code et vérifier que l'explication est précise et personnelle. |
| I2                |                5 | Mobiliser un concept du cours            | L'étudiant utilise correctement un concept vu en cours (HTML sémantique, CSS, responsive, etc.). | Demander de définir ou d'illustrer un concept et vérifier la justesse de la réponse.              |
| I3                |                5 | Analyser et corriger un problème         | L'étudiant identifie la cause d'un bug ou d'un problème et propose une correction pertinente.    | Présenter un problème concret et observer la démarche de diagnostic et de résolution.             |
| I4                |                3 | Contribution et progression personnelle  | L'étudiant a participé activement au projet et montre une progression visible.                   | Examiner l'historique Git et les retours des membres du groupe.                                   |
| I5                |                5 | Progression individuelle                 | L'étudiant montre une amélioration de ses compétences entre le début et la fin du projet.        | Comparer les premières et dernières démos et vérifier que les lacunes initiales sont comblées.    |

> [!important]
> Les évaluations individuelles se font progressivement sur les Jours 2 à 4.
> Si vous avez des contraintes d'absence, signalez-le au prof pour que votre évaluation
> se fasse avant votre absence.
