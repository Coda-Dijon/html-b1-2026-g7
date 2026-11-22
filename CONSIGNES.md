## Barème général

Le total est sur 100 points : A (40) + B2 (35) + B1 (25). Pour convertir la note finale sur 20, diviser le total par 5.

L’idée centrale pour B : **on évalue ce que les apprenants comprennent et savent faire au terme du parcours, ainsi que leur capacité à progresser — pas l’absence d’erreurs pendant le développement.**

## A — Évaluation du site livré : 40 points

Pour chaque critère, attribuer un niveau de 0 à 4, puis calculer : **points obtenus = maximum du critère × niveau ÷ 4**. Des demi-points peuvent être utilisés.

Voir `CONSIGNES.md` pour la liste complète des 23 critères organisés en 7 sections :

| Section | Max. | Critères |
|---------|-----:|----------|
| **Pages et contenus** | 5 | P1–P5 |
| **Images** | 4 | I1–I3 |
| **Structure et sémantique** | 5 | S1–S5 |
| **Style et mise en page** | 9 | M1–M5 |
| **Accessibilité et affichage adaptatif** | 9 | A1–A3 |
| **Éco-conception** | 3 | E1 |
| **Mesure et qualité** | 5 | Q1–Q3 |
| **JavaScript (pénalité)** | –2 | J1 |
| **Total A** | **40** | |

**Repères de niveau communs**

- **0 — Absent ou inutilisable :** le critère n’est pas présent, ou ne peut pas être évalué parce qu’il ne fonctionne pas.
- **1 — Très incomplet :** quelques éléments sont en place, mais le critère est majoritairement non satisfait.
- **2 — Partiel :** résultat compréhensible, mais avec des lacunes visibles ou des incohérences.
- **3 — Attendu atteint :** résultat fonctionnel et approprié pour le niveau du cours.
- **4 — Solide :** résultat particulièrement cohérent, soigné ou robuste ; les détails renforcent l’expérience sans être indispensables.

Une erreur isolée ne fait pas tomber automatiquement tout un critère au niveau 0 ou 1 .
Le résultat est jugé dans son ensemble et la gravité de l’impact sur l’usage.

## B — Démos

### Cadence recommandée

**Une démonstration évaluée par groupe chaque jour**.

Le groupe peut solliciter une deuxième démo pour montrer une évolution ou donner un retour intermédiaire.

Pour chaque groupe, compter environ **8 minutes** :

1. **1 minute — État du projet :** ce qui est présent ou a changé depuis la dernière démo.
2. **2 minutes — Démonstration :** montrer une partie fonctionnelle du site.
3. **2 minutes — Choix techniques :** expliquer une décision HTML, CSS, responsive ou autre, et son intérêt.
4. **2 minutes — Question individuelle :** répondre à une question courte liée au cours.
5. **1 minute — Problème et vérification :** décrire une erreur, une limite ou un point à améliorer, puis expliquer comment le corriger ou le vérifier.

La démonstration peut être adaptée si un projet ne dispose pas encore de la fonctionnalité montrée : les apprenants peuvent expliquer ce qu’ils testent, ce qu’ils observent et la suite envisagée.

### Garantir une évaluation individuelle équitable

- Faire tourner la personne qui présente l’état d’avancement.
- Poser à chaque apprenant **au moins deux questions individuelles évaluées pendant les cinq jours** ; trois si le temps le permet.
- Noter séparément les réponses individuelles : la bonne réponse d’un coéquipier ne vaut pas comme preuve de maîtrise individuelle.
- Poser des questions de difficulté et de portée comparables à tous.
- Évaluer la clarté du raisonnement et la compréhension, pas l’aisance à parler en public.

Exemples de questions comparables :

- « Pourquoi avoir choisi cet élément HTML ? »
- « Quelle différence entre cette classe et un identifiant dans votre cas ? »
- « Comment cette mise en page change-t-elle sur petit écran ? »
- « Comment vérifier que ce champ est compréhensible au clavier ? »
- « Que regarderiez-vous si cette règle CSS ne s’appliquait pas ? »
- « Quelle solution permettrait de faire cela sans JavaScript ? »

### B2 — Résultat collectif des démonstrations : 35 points

Évaluer une seule fois pour le groupe, à partir des démonstrations et de l’évolution du projet. La qualité de présentation n’est pas une compétition : une équipe n’est pas mieux notée uniquement parce qu’elle parle avec plus d’assurance.

| Critère collectif                                 |   Max. | Ce qui est observé                                                                                                                                                       |
|---------------------------------------------------|-------:|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Fonctionnalité montrée et évolution du projet** |      8 | Le groupe sait montrer ce qui est effectivement réalisé et expliquer où cela s’inscrit dans le projet.                                                                   |
| **Explication des choix**                         |      8 | Les décisions de structure, de styles ou de mise en page sont compréhensibles et reliées aux besoins du site.                                                            |
| **Compréhension des concepts du cours**           |      6 | Les explications mobilisent correctement les notions étudiées, même avec des formulations simples.                                                                       |
| **Diagnostic et correction**                      |      6 | Le groupe sait examiner un problème, essayer une correction adaptée et expliquer ce qu’il vérifie ensuite.                                                               |
| **Progression entre les démos**                   |      7 | Le groupe réutilise les retours, affine son travail ou améliore sa méthode. Une amélioration peut être une correction, une vérification ou une décision mieux justifiée. |
| **Total B2**                                      | **35** |                                                                                                                                                                          |

### B1 — Maîtrise individuelle : 25 points

Attribuer les points à partir des questions individuelles, des explications données pendant les démos et des corrections auxquelles la personne a contribué.

| Critère individuel                           |   Max. | Ce qui est observé                                                                                       |
|----------------------------------------------|-------:|----------------------------------------------------------------------------------------------------------|
| **Expliquer un choix réalisé par le groupe** |      7 | La personne explique le choix, son rôle et son effet sur le site.                                        |
| **Mobiliser un concept du cours**            |      5 | Elle utilise ou explique correctement une notion pertinente de HTML, CSS, mise en page ou accessibilité. |
| **Analyser et corriger un problème**         |      5 | Elle formule une hypothèse, essaie une correction et vérifie le résultat, avec ou sans aide.             |
| **Contribution et progression personnelle**  |      3 | Elle peut décrire sa contribution et montrer ce qu’elle a appris ou amélioré.                            |
| **Progression individuelle**                 |      5 | Elle réutilise les retours, affine sa compréhension ou adopte une meilleure méthode de vérification.     |
| **Total B1**                                 | **25** |                                                                                                          |

### Évaluer une correction sans pénaliser l’erreur

Pendant une démonstration, observer la démarche plutôt que le fait que le code ait été parfait dès le départ :

- **Repérer :** la personne constate ou comprend le problème.
- **Expliquer :** elle propose une cause plausible.
- **Essayer :** elle modifie ou teste quelque chose de pertinent.
- **Vérifier :** elle constate si le résultat attendu est obtenu.

Une erreur remarquée et corrigée peut donc fournir une **preuve positive d’apprentissage**. Si le problème n’est pas encore résolu, la personne peut tout de même montrer sa compréhension en expliquant la cause probable, le test suivant et le résultat qu’elle cherche à obtenir.

### Barème de prise de notes pour B

Pour chacun des critères, utiliser la même échelle de **0 à 4**, puis calculer : **points obtenus = maximum du critère × niveau ÷ 4**.

- **0 — Pas de preuve observée**
- **1 — Compréhension très fragile, même avec aide**
- **2 — Compréhension partielle ; la personne avance avec des indications**
- **3 — Réponse ou démarche appropriée de façon autonome**
- **4 — Explication claire, raisonnement solide ou transfert pertinent à une autre situation**

Pour la progression, ne pas comparer les apprenants entre eux et ne pas calculer une simple différence entre leur première et leur dernière prestation. Noter plutôt les signes concrets d’évolution : retour pris en compte, diagnostic plus structuré, vérification ajoutée, décision mieux expliquée ou autonomie accrue. Une personne déjà compétente au départ peut démontrer sa progression par un travail plus approfondi, de meilleures vérifications ou une justification plus précise.

**Conseil de suivi :** tenir une fiche par groupe pour B2 et une fiche par apprenant pour B1, avec une ligne par date : critère observé, niveau, exemple ou citation courte. Cette trace rend la note plus facile à justifier et limite le poids d’une impression générale en fin de semaine.