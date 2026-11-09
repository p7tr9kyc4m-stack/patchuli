# 01 — Vision et problème

> Étape 01/14 du cadrage du projet `patchuli`.
> Premier livrable : il fixe le problème, la cible, la différenciation et l'ambition. Il suit le profilage noté dans [`00-etat.md`](00-etat.md).
> Ne tranche pas :
> - les personas détaillés et les entretiens producteurs → étape 02 ;
> - les objectifs chiffrés (nombre de producteurs, d'utilisateurs) → étape 03 ;
> - le contenu exact de la V1 et de la V2, le modèle de revenus et l'amorçage des données → étape 04 ;
> - la conformité (DSA, P2B, Code de la consommation, INCO) → étape 06.

- **Statut** : en cours (validation du gate retirée le 2026-11-09 à la demande de l'utilisateur)
- **Validé le** : —
- **Sources consultées** : §3.2, toutes consultées le 2026-11-09 à partir de résultats de recherche web, sans lecture intégrale des pages. Les chiffres sont à revérifier avant tout usage public.

## 1. Synthèse
- patchuli met en relation, sur un **territoire restreint** (Q-01), les consommateurs qui veulent acheter local et les producteurs en vente directe (D01-01, D01-03).
- La V1 sert à **trouver** :
  - une carte et une recherche par produit sur mobile ;
  - des informations tenues à jour par le producteur ;
  - une vitrine producteur riche (D01-04).
- La publicité payante vient après la V1, une fois l'audience constituée (D01-05). Le paiement et la livraison sont en V2.
- Le principal concurrent gratuit est Frais et local. La différence assumée tient en trois points (§6) : la fraîcheur des informations, la vitrine et l'expérience mobile.
- Succès à 12 mois : devenir le **réflexe local** sur le territoire de lancement (D01-06).

## 2. Pitch et problème
### 2.1 Pitch
Pitch à **double cible** (D01-01) :

> Pour les consommateurs qui veulent acheter local et les producteurs qui veulent vendre en direct, patchuli est une application de mise en relation géolocalisée qui fait trouver en quelques secondes les producteurs proches et ce qu'ils vendent cette semaine, et qui donne à chaque producteur une vitrine pour se faire connaître.

### 2.2 Problème
Il est formulé indépendamment de la solution (utilisateur, 2026-11-09) :
1. **Côté consommateur.** La majorité des gens achètent des produits industriels en grande surface, de qualité nutritionnelle médiocre, faute de savoir qui produit près de chez eux, quoi, où et quand.
2. **Côté offre.** Des producteurs proches proposent des produits de meilleure qualité, pour un prix équivalent ou un peu plus élevé.
3. **Côté producteur.** Ces producteurs ont du mal à vendre, surtout aux particuliers : ils manquent de visibilité au-delà de leur marché et du bouche-à-oreille.

Ordre de grandeur :
- 23 % des exploitations de métropole vendent en circuit court, soit environ 90 000, selon le recensement agricole 2020 ([DRAAF Normandie](https://draaf.normandie.agriculture.gouv.fr/IMG/pdf/infographie_octobre_2023.pdf)) ;
- la part atteint 52 % en bio contre 19 % en conventionnel ([Agreste Nouvelle-Aquitaine, mars 2026](https://draaf.nouvelle-aquitaine.agriculture.gouv.fr/IMG/pdf/agrestena_etudes_58_mars_2026_circuits_courts.pdf)) ;
- près des deux tiers de ces exploitations vendent à la ferme ([Réussir](https://www.reussir.fr/pres-dune-exploitation-sur-quatre-vend-en-circuit-court)).

### 2.3 Situations concrètes (**hypothèse H-01**)
L'utilisateur n'a pas d'exemple réel. Les deux situations ci-dessous sont des **exemples types**, à confirmer par des entretiens à l'étape 02.
- **Consommatrice.** Claire, 34 ans, habite en périphérie d'une ville moyenne. Elle voudrait acheter ses œufs et ses légumes à un producteur. Elle connaît le marché du samedi, mais ne peut pas y aller cette semaine. Elle ne sait pas qu'une ferme à 6 km vend à la ferme le mercredi de 17 h à 19 h, alors elle achète en grande surface.
- **Producteur.** Un maraîcher bio vend sur un marché hebdomadaire et à la ferme. Sa page Facebook est peu suivie et sa fiche Google Maps ne dit rien de ses légumes du moment. Ses invendus du mercredi n'ont pas d'autre débouché.

## 3. Solutions actuelles et concurrence
### 3.1 Comment le problème est résolu aujourd'hui
Côté consommateur, il est résolu surtout par les **marchés** de plein vent (réponse de l'utilisateur, 2026-11-09). Côté producteur, par la vente à la ferme, les marchés, les réseaux sociaux et les annuaires (§3.2).

### 3.2 Concurrence
Toutes les sources ont été consultées le 2026-11-09.

| # | Solution | Positionnement | Couverture | Modèle et prix | Limites pour le problème de patchuli | Active en 2026 | Sources |
|---|---|---|---|---|---|---|---|
| C1 | Frais et local | Annuaire public du ministère de l'Agriculture et des Chambres, lancé le 12/01/2021 ; carte et filtres | environ 8 000 au lancement, « plus de 12 000 » selon un document non daté du ministère | gratuit | Ni vitrine riche, ni informations sur les produits du moment, ni outils de promotion | probablement (non vérifié) | [info.gouv.fr](https://www.info.gouv.fr/actualite/frais-et-local-la-plateforme-pour-manger-sain-et-responsable), [agriculture.gouv.fr](https://agriculture.gouv.fr/telecharger/123907) |
| C2 | Bienvenue à la ferme | Marque des Chambres d'agriculture (1988) : vente et accueil à la ferme | 4 600 à plus de 10 000 selon les sources (contradictoires) | cotisation annuelle, montant non public | Adhésion payante et cahier des charges ; annuaire peu dynamique | oui | [dossier de presse 2025](https://api.bienvenue-a-la-ferme.com/media/press_attachment/67a9b9b68d5d4910791304.pdf), [Que Choisir](https://www.quechoisir.org/enquete-alimentation-ou-trouver-des-produits-en-circuit-court-n5887) |
| C3 | La Ruche qui dit Oui (CrowdFarming) | Commandes groupées retirées en point de distribution ; CrowdFarming est l'unique actionnaire depuis avril 2025 | 800 Ruches dont la moitié en France, 10 000 agriculteurs inscrits, 25 M€ de chiffre d'affaires en 2024 | commission d'environ 20 % historiquement, taux de 2026 non trouvé | Commande à l'avance, retrait à heure fixe ; pas de découverte libre des producteurs. Concurrent principal de la V2. | oui | [Réussir](https://www.reussir.fr/circuits-courts-la-ruche-qui-dit-oui-rachetee-par-la-plateforme-espagnole-crowdfarming), [Copeps](https://copeps.fr/actualites/la-ruche-qui-dit-oui-statut-juridique/), [Euronews 06/2026](https://www.euronews.com/2026/06/05/crowdfarming-the-platform-that-wants-to-feed-europe-better) |
| C4 | Cagette.net | Logiciel coopératif pour les marchés et groupes d'achat | non trouvée | 9 % HT (6 % de service, 3 % de paiement) | Orienté vers les groupes, pas vers la découverte | probablement | [présentation de 03/2024](https://www.cagette.net/wp-content/uploads/2024/03/Presentation-proposition-1.pdf) |
| C5 | Kuupanda | Logiciel SaaS de gestion et de vente pour producteurs (boutique, caisse) | « plus de 2 000 producteurs » | abonnement, prix sur demande | Outil de gestion sans audience consommateurs : intégration possible plutôt que concurrent | oui | [Appvizer](https://www.appvizer.fr/biens/agro-alimentaire/kuupanda) |
| C6 | Locavor | Commandes groupées par point de distribution | non trouvée | 7,5 % pour le site, plus 9 à 11 % pour le point de distribution (source ancienne) | Même logique que C3 | non vérifiée | [linfodurable](https://www.linfodurable.fr/conso/circuits-courts-et-anti-gaspi-le-premier-point-de-distribution-locavor-debarque-paris-11491) |
| C7 | Le Marché vert | Carte collaborative lancée pendant le confinement de 2020 | environ 1 000 initiatives en 2020 | gratuit | Aucune mise à jour visible depuis 2020 | probablement en sommeil | [linfodurable](https://www.linfodurable.fr/conso/une-carte-collaborative-pour-continuer-dacheter-ses-produits-en-circuits-courts-17339) |
| C8 | AMAP | Contrats de paniers prépayés | non recherchée | associatif | Pas d'achat ponctuel ; engagement sur une saison | oui | — |
| C9 | Google Maps, Facebook, Instagram | Alternatives indirectes | très large | gratuit ; publicité payante | Informations dispersées, rarement à jour ; pas de recherche « qui vend des œufs près de moi cette semaine » | oui | — |
| C10 | Intermarché « Producteurs d'ici » | Annuaire B2B : producteurs et magasins à moins de 70 km, lancé le 24/02/2026 | 15 000 producteurs annoncés | référencement en magasin | Ne s'adresse pas aux consommateurs (hors cible, D01-07) | oui | [FreshPlaza](https://www.freshplaza.com/europe/article/9815765/intermarche-launches-a-platform-dedicated-to-local-producers/) |
| C11 | Outils régionaux (OùAcheterLocal, Terrattitude, Pwodui An-Nou, cartes des Chambres et des intercommunalités) | Annuaires géolocalisés régionaux | régionale | gratuits pour la plupart | Couverture partielle, éparpillement | variable | [Europe 1](https://www.europe1.fr/technologies/ces-sites-et-applications-qui-aident-a-manger-local-3655661) |

## 4. Analyse de l'existant
### 4.1 Éléments existants et rôle
| Élément | Rôle pour le consommateur | Rôle pour le producteur |
|---|---|---|
| Marché de plein vent | Achat direct, contact humain | Principal canal de vente, à jour fixe |
| Vente à la ferme | Achat direct, souvent sur des créneaux | Canal sans intermédiaire, mais peu visible |
| Annuaires (C1, C2, C11) | Trouver une adresse | Être référencé |
| Plateformes de commande (C3, C4, C6) | Commander à l'avance et retirer | Vendre en volume, contre commission |
| Réseaux sociaux et Google Maps (C9) | Découverte fortuite | Communication gratuite mais chronophage |

### 4.2 Défauts constatés
| # | Défaut | Conséquence | Source |
|---|---|---|---|
| DF-01 | Les annuaires (C1, C2) donnent une adresse, pas les produits disponibles ni les horaires de la semaine | Le consommateur ne sait pas si le déplacement vaut la peine et retourne en grande surface | §3.2, fonctions de C1 et C2 |
| DF-02 | Aucune solution grand public ne combine la découverte géolocalisée, une vitrine riche, des informations tenues par le producteur et des outils de promotion | Le producteur doit multiplier les canaux (annuaire, réseaux sociaux, Google) | Constat 1 du rapport `chercheur` du 2026-11-09 |
| DF-03 | Les plateformes de commande (C3, C4, C6) imposent une commande anticipée et un retrait à heure fixe, avec une commission de 9 à 20 % | Elles ne couvrent ni l'achat spontané ni la vente à la ferme | §3.2 |
| DF-04 | Les informations des réseaux sociaux et de Google Maps (C9) sont dispersées et rarement à jour | Elles sont peu fiables pour décider d'un achat | **hypothèse H-02**, à confirmer en entretien (étape 02) |
| DF-05 | Plusieurs annuaires semblent en sommeil (C7) ou ont des chiffres contradictoires (C2) | Données périmées, défiance des utilisateurs | §3.2 |
| DF-06 | Le marché, canal principal du consommateur (§3.1), a lieu un jour fixe | Si l'on manque le marché, on n'achète pas local cette semaine | réponse de l'utilisateur, 2026-11-09 |

## 5. Principes déjà retenus
| # | Principe | Justification | Décision |
|---|---|---|---|
| P-01 | Lancement sur un territoire restreint, territoire *à préciser (Q-01)* | La valeur d'une mise en relation dépend de la densité locale ; C1 couvre déjà la France gratuitement | D01-03 |
| P-02 | Seuls les producteurs en vente directe sont référencés : ni enseigne, ni revendeur, ni produit non local | C'est la promesse de confiance, qui distingue patchuli de la grande distribution (C10) | D01-07 |
| P-03 | Les informations sont tenues par le producteur lui-même | Elles corrigent DF-01 et DF-05 | D01-04 |
| P-04 | Pas de logistique propre en V1 : la vente a lieu chez le producteur ou sur ses points de vente | Coût et complexité réservés à la V2 ; concentration sur la découverte | D01-07 |
| P-05 | La monétisation par la publicité suit l'audience : elle n'est pas en V1 | Sans consommateurs, la mise en avant n'a pas de valeur pour le producteur | D01-05 |

## 6. Différenciation et proposition de valeur
| Axe | Version | Ce que les autres ne font pas | Défaut corrigé |
|---|---|---|---|
| Informations à jour, tenues par le producteur (produits du moment, horaires, points de vente) | V1 | C1 et C2 n'ont que des fiches statiques | DF-01, DF-05 |
| Vitrine producteur : page « À propos », vidéo, lien vers les réseaux sociaux (titulaire du compte *à préciser, Q-02*) | V1 | Les annuaires n'offrent pas de vitrine riche | DF-02 |
| Expérience mobile : carte et recherche par produit autour de soi | V1 | C1 est un site web, sans recherche « produit près de moi » | DF-01, DF-06 |
| Outils marketing : mise en avant payante, promotions, notifications aux clients proches | après la V1 (V1.1 ou V2, à fixer à l'étape 04) | Aucun annuaire ne les propose | DF-02 |
| Paiement en ligne et livraison à domicile | V2 | C3 et C4 le font sur commande groupée, pas en vente à l'unité | DF-03, DF-06 |

Proposition de valeur :
- **pour le consommateur** : savoir en quelques secondes qui vend quoi près de chez lui, et quand ;
- **pour le producteur** : une vitrine gratuite en V1, puis des outils pour attirer des clients.

## 7. Pourquoi maintenant
- Il n'y a pas d'échéance imposée : le projet saisit une opportunité générale, dans le cadre d'une démarche business (D01-02).
- Le contexte de marché (§3.2) :
  - **concentration** : CrowdFarming contrôle La Ruche qui dit Oui depuis avril 2025 ;
  - **arrivée de la grande distribution** sur le « local » : annuaire Intermarché en février 2026 ;
  - **plusieurs annuaires vieillissants** (C7).
- Le créneau « découverte grand public, à jour et mobile » reste libre.

## 8. Vision à 6-12 mois et durée de vie
- **Succès à 12 mois** (D01-06) : sur le territoire de lancement, assez de producteurs actifs et de consommateurs réguliers pour que patchuli soit le réflexe local. Les seuils chiffrés sont fixés à l'étape 03.
- **Durée de vie** : plusieurs années (D01-08). Le produit d'entreprise sera maintenu et étendu (V2, autres territoires) ; l'architecture et la qualité sont pensées pour durer.

## 9. Non-objectifs
| # | Non-objectif | Portée | Décision |
|---|---|---|---|
| NO-01 | Pas de grande surface, d'enseigne, de revendeur ni de produit non local | toutes versions | D01-07 |
| NO-02 | Pas de vente B2B (restaurants, magasins) : uniquement aux particuliers | toutes versions, sauf décision contraire | D01-07 |
| NO-03 | Pas de logistique propre (stock, entrepôt, livreurs) | V1 ; la livraison de la V2 sera cadrée à l'étape 04 | D01-07 |
| NO-04 | Pas de notes ni d'avis publics des consommateurs | V1 | D01-07 |

## 10. Décisions
| # | Question | Décision | Justification |
|---|---|---|---|
| D01-01 | Cible principale du produit | Double cible : consommateurs et producteurs dès la V1 | Une place de marché n'a de valeur que si ses deux côtés sont présents. L'ambition publicitaire suppose des producteurs actifs. |
| D01-02 | Raison d'être du projet | Opportunité business : créer une entreprise rentable | Réponse de l'utilisateur. Le modèle de revenus est détaillé aux étapes 03 et 04. |
| D01-03 | Zone de lancement | Un territoire restreint plutôt que la France entière (lequel : Q-01) | C1 couvre déjà la France gratuitement ; la valeur vient de la densité locale. |
| D01-04 | Contenu de la V1 parmi les axes de différenciation | Informations à jour tenues par le producteur, vitrine producteur, expérience mobile centrée sur la carte et la recherche par produit | C'est le cœur de la promesse « trouver », et cela corrige DF-01, DF-02 et DF-06. |
| D01-05 | Place de la publicité payante | Hors V1 : en V1.1 ou en V2, à fixer à l'étape 04 | La mise en avant n'a de valeur qu'avec une audience. En V1, la vitrine gratuite attire les producteurs. Écarté : publicité dès la V1, sans audience à vendre. |
| D01-06 | Définition du succès à 12 mois | Densité locale : patchuli devient le réflexe local sur le territoire de lancement | Condition préalable aux revenus publicitaires et à une levée de fonds. Écartés comme objectif premier : premiers revenus, levée de fonds. |
| D01-07 | Non-objectifs | NO-01 à NO-04 (§9) | Recentrer la promesse sur la vente directe aux particuliers et éviter la « plateforme pour tout ». |
| D01-08 | Durée de vie attendue (tranche Q-03) | Plusieurs années | L'ambition d'entreprise et la V2 l'exigent. Écarté : une V1 jetable de 6 à 12 mois, dont la réécriture coûterait la densité acquise. |

## 11. Hypothèses
| # | Hypothèse | Impact si fausse | À valider par |
|---|---|---|---|
| H-01 | Les situations types de §2.3 représentent bien les consommateurs et les producteurs ciblés | Problème mal ciblé, fonctions de la V1 inadaptées | Entretiens avec au moins 5 producteurs et 5 consommateurs (étape 02) |
| H-02 | Les informations des réseaux sociaux et de Google Maps sur les producteurs sont rarement à jour (DF-04) | La différenciation « infos à jour » s'affaiblit | Échantillon de 20 fiches de producteurs du territoire de lancement (étape 02 ou 07) |
| H-03 | Les producteurs accepteront de tenir eux-mêmes leurs informations à jour | Données périmées, retour au défaut DF-01 | Entretiens producteurs (étape 02) ; risque à suivre à l'étape 07 |

## 12. Critères de sortie
- [ ] Le problème est formulé indépendamment de la solution (§2.2).
- [ ] Le pitch tient en une phrase et l'utilisateur le valide (§2.1).
- [ ] L'existant et la concurrence sont documentés avec leurs sources (§3, §4).
- [ ] La différenciation est explicite (§6).
- [ ] Au moins un non-objectif est écrit (§9).

Contrôle avant le gate (00-exigences-communes §5), fait le 2026-11-09 avant le retrait de la validation ; à refaire au prochain gate :
1. Codable sans question : oui, au niveau d'une vision ; les fonctions sont détaillées en 04 et 05.
2. Testable : sans objet à cette étape.
3. Valeurs exactes : chaque chiffre est sourcé et daté ; les exemples sont des exemples types, marqués H-01.
4. Cas limites : sans objet à cette étape.
5. Décisions : D01-01 à D01-08 ont chacune leur justification.
6. Renvois : les sections citées existent (§2 à §13).
7. Index et glossaire : mis à jour à la clôture.

## 13. Points à préciser
- Territoire de lancement → Q-01
- Vitrine producteur : le lien « réseaux sociaux » mène-t-il aux comptes du producteur ou à ceux de patchuli ? → Q-02
- Modèle de revenus de la V1, alors que la publicité est reportée (D01-05) → Q-04 (étapes 03 et 04)
- Amorçage des données : inscription par les producteurs, démarchage, ou import de données ouvertes (Frais et local, si disponible) → Q-05 (étapes 04 et 09)
