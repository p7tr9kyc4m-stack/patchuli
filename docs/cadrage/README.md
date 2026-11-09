# Documentation de cadrage — patchuli

> Index du dossier, tenu par l'agent de cadrage et mis à jour à chaque fin d'étape. Le suivi détaillé (position, décisions, questions ouvertes) est dans [`00-etat.md`](00-etat.md).

> Pour les consommateurs qui veulent acheter local et les producteurs qui veulent vendre en direct, patchuli est une application de mise en relation géolocalisée qui fait trouver en quelques secondes les producteurs proches et ce qu'ils vendent cette semaine, et qui donne à chaque producteur une vitrine pour se faire connaître. (01 §2.1)

## Feuille de route
| Étape | Document | Contenu | Statut |
|---|---|---|---|
| 01 | [Vision et problème](01-vision-probleme.md) | problème, existant, non-objectifs | en cours |
| 02 | [Utilisateurs et parties prenantes](02-utilisateurs-parties-prenantes.md) | | à faire |
| 03 | [Objectifs et critères de succès](03-objectifs-succes.md) | | à faire |
| 04 | [Périmètre et MVP](04-perimetre-mvp.md) | | à faire |
| 05 | [Exigences fonctionnelles](05-exigences-fonctionnelles.md) | | à faire |
| 06 | [Exigences non fonctionnelles et conformité](06-exigences-non-fonctionnelles-conformite.md) | | à faire |
| 07 | [Contraintes, risques et hypothèses](07-contraintes-risques-hypotheses.md) | | à faire |
| 08 | [UX, parcours et interface](08-ux-parcours.md) | | à faire |
| 09 | [Données et domaine](09-donnees-domaine.md) | | à faire |
| 10 | [Architecture et stack](10-architecture-stack.md) | | à faire |
| 11 | [Environnement de dev et qualité](11-environnement-qualite.md) | | à faire |
| 12 | [Planification et organisation](12-planification-organisation.md) | | à faire |
| 13 | [Exploitation et maintenance](13-exploitation-maintenance.md) | | à faire |
| 14 | [Synthèse et Go/No-Go](14-synthese-go-no-go.md) | | à faire |

Autres dossiers : décisions d'architecture [`../adr/`](../adr/), maquettes [`../maquettes/`](../maquettes/), pilotage [`../pilotage/`](../pilotage/).

## Glossaire
| Terme | Sens | Défini en |
|---|---|---|
| Circuit court | Vente avec au plus un intermédiaire entre le producteur et le consommateur | 01 §2.2 |
| Producteur (en vente directe) | Exploitant agricole qui vend lui-même sa production aux particuliers ; seul type de vendeur admis (NO-01) | 01 §5 |
| Vitrine producteur | Page du producteur : « À propos », vidéo, lien vers les réseaux sociaux | 01 §6 |
| Mise en avant payante | Placement prioritaire acheté par un producteur ; hors V1 | 01 §6, D01-05 |
| Territoire de lancement | Zone géographique restreinte où patchuli démarre (Q-01) | 01 §5 |

## Index des identifiants
| Préfixe | Nature | Plage | Document |
|---|---|---|---|
| `D01-xx` | décision de l'étape 01 | D01-01 à D01-08 | 01 §10 |
| `C` | solution concurrente | C1 à C11 | 01 §3.2 |
| `DF-xx` | défaut constaté de l'existant | DF-01 à DF-06 | 01 §4.2 |
| `P-xx` | principe retenu | P-01 à P-05 | 01 §5 |
| `NO-xx` | non-objectif | NO-01 à NO-04 | 01 §9 |
| `H-xx` | hypothèse | H-01 à H-03 | 01 §11, 00-etat |
| `Q-xx` | question ouverte | Q-01 à Q-05 | 00-etat |

Les renvois s'écrivent `<document> §<section>` : « 05 §9.1 » désigne la section 9.1 de `05-exigences-fonctionnelles.md`.
