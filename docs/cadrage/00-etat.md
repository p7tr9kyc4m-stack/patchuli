# État du cadrage — patchuli

> Fichier de suivi tenu par l'agent de cadrage. Il permet la reprise : relancer `/cadrage D:\Projects\patchuli`.

- **Démarré le** : 2026-11-09
- **Dernière mise à jour** : 2026-11-09
- **Étape courante** : 01
- **Pilotage du développement** : non généré

## Position
> Mise à jour après **chaque lot validé**. C'est la première section lue à la reprise.

- **Étape** : 01 — Vision et problème (en cours, validation du gate retirée)
- **Lot** : —
- **Dernière action** : validation du gate de l'étape 01 retirée le 2026-11-09 à la demande de l'utilisateur ; livrable conservé, D01-01 à D01-08 maintenues sauf révision
- **Prochaine action** : recueillir les points de l'étape 01 à reprendre, puis refaire le gate
- **Mise à jour le** : 2026-11-09

## Profil du projet
| Champ | Valeur |
|---|---|
| Type(s) | web, mobile |
| Taille / contexte | startup / MVP |
| Niveau d'exigence | **élevé** (`etapes/00-exigences-communes.md`) |
| Point de départ | nouveau (dossier vide constaté le 2026-11-09, confirmé par l'utilisateur) |
| Équipe | solo — qui code : Claude Code (l'utilisateur pilote et valide) |
| Interface | visuelle → maquettes (étape 08) |
| Projets voisins | aucun |
| Valideur externe | aucun |

## Avancement
Statuts : `à faire` · `en cours` · `terminée` · `sans objet` (raison obligatoire)

| # | Étape | Statut | Livrable | Note (raison si sans objet) |
|---|---|---|---|---|
| 01 | Vision et problème | en cours | 01-vision-probleme.md | validation du 2026-11-09 retirée le 2026-11-09 |
| 02 | Utilisateurs et parties prenantes | à faire | 02-utilisateurs-parties-prenantes.md | |
| 03 | Objectifs et critères de succès | à faire | 03-objectifs-succes.md | |
| 04 | Périmètre et MVP | à faire | 04-perimetre-mvp.md | |
| 05 | Exigences fonctionnelles | à faire | 05-exigences-fonctionnelles.md | |
| 06 | Exigences non fonctionnelles et conformité | à faire | 06-exigences-non-fonctionnelles-conformite.md | |
| 07 | Contraintes, risques et hypothèses | à faire | 07-contraintes-risques-hypotheses.md | |
| 08 | UX, parcours et maquettes | à faire | 08-ux-parcours.md | |
| 09 | Données et domaine | à faire | 09-donnees-domaine.md | |
| 10 | Architecture et stack | à faire | 10-architecture-stack.md | |
| 11 | Environnement de dev et qualité | à faire | 11-environnement-qualite.md | |
| 12 | Planification et organisation | à faire | 12-planification-organisation.md | |
| 13 | Exploitation et maintenance | à faire | 13-exploitation-maintenance.md | |
| 14 | Synthèse et Go/No-Go | à faire | 14-synthese-go-no-go.md | |

## Décisions clés
| Date | Étape | Décision | Raison | ADR |
|---|---|---|---|---|
| 2026-11-09 | 01 | D01-01 Double cible : consommateurs et producteurs dès la V1 | Une place de marché a besoin de ses deux côtés | — |
| 2026-11-09 | 01 | D01-02 Motivation : opportunité business | Réponse de l'utilisateur | — |
| 2026-11-09 | 01 | D01-03 Lancement sur un territoire restreint (lequel : Q-01) | Frais et local couvre déjà la France ; la valeur vient de la densité locale | — |
| 2026-11-09 | 01 | D01-04 V1 : infos à jour tenues par le producteur, vitrine producteur, expérience mobile (carte et recherche par produit) | Cœur de la promesse « trouver » | — |
| 2026-11-09 | 01 | D01-05 Publicité payante hors V1 (V1.1 ou V2) | Pas de valeur sans audience | — |
| 2026-11-09 | 01 | D01-06 Succès à 12 mois : densité locale (réflexe local) | Préalable aux revenus | — |
| 2026-11-09 | 01 | D01-08 Durée de vie : plusieurs années | Ambition d'entreprise, V2 | — |
| 2026-11-09 | 01 | D01-07 Non-objectifs NO-01 à NO-04 : pas de grande surface, pas de B2B, pas de logistique en V1, pas d'avis publics en V1 | Recentrer sur la vente directe aux particuliers | — |

## Hypothèses (à valider)
| # | Hypothèse | Étape | Impact si fausse | Comment la valider | Statut |
|---|---|---|---|---|---|
| H-01 | Les situations types de 01 §2.3 sont représentatives | 01 | Problème mal ciblé | Entretiens : 5 producteurs, 5 consommateurs (02) | à valider |
| H-02 | Les informations des réseaux sociaux et de Google Maps sur les producteurs sont rarement à jour | 01 | Différenciation affaiblie | Échantillon de 20 fiches (02 ou 07) | à valider |
| H-03 | Les producteurs tiendront eux-mêmes leurs informations à jour | 01 | Données périmées | Entretiens producteurs (02) ; risque en 07 | à valider |

## Questions ouvertes
Identifiants `Q-01`, `Q-02`… stables. À l'étape 12, chaque question non bloquante devient une tâche de décision : noter alors « → Txx » dans la colonne Suite.

| # | Question | Étape | Bloquante pour | Responsable | Suite |
|---|---|---|---|---|---|
| Q-01 | Territoire de lancement (agglomération, département ou région) | 01 | 04 (périmètre), 07 (risques), 12 | utilisateur | |
| Q-02 | Vitrine producteur : le lien « réseaux sociaux » mène-t-il aux comptes du producteur ou à ceux de patchuli ? | 01 | 05 | utilisateur | |
| Q-03 | Durée de vie attendue du produit | 01 | 10 (architecture) | utilisateur | tranchée le 2026-11-09 : D01-08 (plusieurs années) |
| Q-04 | Modèle de revenus de la V1, la publicité étant reportée (D01-05) | 01 | 03, 04 | utilisateur | |
| Q-05 | Amorçage des données : inscription par les producteurs, démarchage ou import de données ouvertes | 01 | 04, 09 | utilisateur | |

## Maquettes publiées
| Écran | Fichier | Artifact (URL) | Statut |
|---|---|---|---|
