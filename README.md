# Projet SI IBISC --- Documents de pilotage

> Laboratoire IBISC --- Université Évry Paris-Saclay
> Dernière mise à jour : 23 May 2026

Ce dépôt héberge les documents de pilotage du projet de **refonte du site Web IBISC** engagé en mars 2026 par décision de la Pr. Feng CHU, directrice du laboratoire.

## 📂 Organisation des fichiers

### 🔓 `public/` --- documents en libre accès

Documents institutionnels du chantier, diffusables sans restriction :

| Document | Description |
|---|---|
| [`note-cadrage-refonte-v1.0.pdf`](public/note-cadrage-refonte-v1.0.pdf) | **Note de cadrage** v1.0 (20 mai 2026) --- document de référence du chantier |
| [`addendum-dmcom-lmee-v1.0.5.pdf`](public/addendum-dmcom-lmee-v1.0.5.pdf) | **Addendum DMCom/LMEE** v1.0.5 (20 mai 2026) --- éclaire Q3 (articulation UEVRY) |
| [`cr-comite-web-1-v1.0.pdf`](public/cr-comite-web-1-v1.0.pdf) | **CR du Comité Web n°1** (11 mai 2026) --- 5 décisions, 4 actions, 4 arbitrages |
| [`kit-graphique-ibisc-uevry-v1.3.zip`](public/kit-graphique-ibisc-uevry-v1.3.zip) | **Kit graphique IBISC × UEVRY** v1.3 --- tokens CSS, fontes URW DIN, logos |

### 📁 `public/identite-numerique/` --- campagne identité numérique scientifique

Ressources opérationnelles de la **campagne d'accompagnement à l'identité numérique scientifique** des membres IBISC, ouverte en mai 2026 en application de l'**Action 4** du Comité Web n°1 (« Message aux membres sur l'importance des identifiants pour synchronisation : idHAL, ORCID, cvHAL »). Destinée à tous les EC permanents, doctorants, et autres statuts.

| Ressource | Description |
|---|---|
| [`faq-identite-numerique-ibisc-v1.0.html`](public/identite-numerique/faq-identite-numerique-ibisc-v1.0.html) | **FAQ Identité numérique IBISC** v1.0 --- 17 questions bilingues FR/EN sur 5 sections (création compte HAL, gestion publications/affiliations, CV HAL, liaison ORCID, cas particuliers) |
| [`guide-hal-orcid-cvhal-v1.0.pdf`](public/identite-numerique/guide-hal-orcid-cvhal-v1.0.pdf) | **Guide HAL/ORCID/CV HAL IBISC** v1.0 --- guide pratique de référence à destination des membres IBISC |

> Pilotage de la campagne : F. Davesne (Représentant HAL pour IBISC et LMEE)
> Phase A test interne ✅ · Phase B pilote en cours · Phase C/D/E (déploiement EC + doctorants + autres) à venir

### 🔒 `reserve/` --- documents fondateurs du SI

Documents techniques et stratégiques du projet SI cible, **protégés par mot de passe à l'ouverture du PDF**.

> **Mot de passe** : à demander à F. Davesne (resp. Communication IBISC) ou à un membre du Comité Web.

| Document | Description |
|---|---|
| [`objectifs-si-v1.13.pdf`](reserve/objectifs-si-v1.13.pdf) | **Objectifs SI Laboratoire** v1.13 --- 7 objectifs O1 à O7 |
| [`cdc-structure-v3.21.pdf`](reserve/cdc-structure-v3.21.pdf) | **CdC Structure des données** v3.21 --- 8 entités, workflow O7 |
| [`cdc-fonctionnel-o4-v1.1.pdf`](reserve/cdc-fonctionnel-o4-v1.1.pdf) | **CdC Fonctionnel O4 Annuaire Web** v1.1 |
| [`note-cadrage-technologique-v1.1.pdf`](reserve/note-cadrage-technologique-v1.1.pdf) | **Note de cadrage technologique** v1.1 --- pile Python/FastAPI |
| [`analyse-site-web-v1.24.pdf`](reserve/analyse-site-web-v1.24.pdf) | **Analyse Site Web IBISC** v1.24 --- 89 faiblesses, 34 recommandations |
| [`note-demo-annuaire-v1.3.pdf`](reserve/note-demo-annuaire-v1.3.pdf) | **Note Démo Annuaire** v1.3 |

### Données opérationnelles (RGPD)

Certains documents (formulaires personnalisés, XML opérationnels) contiennent des données individuelles relevant du RGPD. Ils ne sont **jamais** déposés ici, même chiffrés.

➤ Accès par e-mail nominatif ou via SEAFILE Paris-Saclay sur demande motivée à F. Davesne.

## 🔗 Liens associés

- [**Démonstrateur de l'annuaire IBISC**](https://ibiscweb.github.io/annuaire-ibisc/) --- premier livrable de la refonte, validé à 73% par l'enquête membres
- [**Dashboard de l'enquête site Web 2026**](https://ibiscweb.github.io/annuaire-ibisc/enquete/dashboard_enquete_site_ibisc_2026FR.html) (mot de passe : `annuaireibisc`) --- 34 réponses
- [**Code source du démonstrateur**](https://github.com/ibiscweb/annuaire-ibisc)

## 👥 Comité Web IBISC

13 membres pérennes (au 20 mai 2026), présidé par Pr. Feng CHU :

- **Direction** : F. CHU, S. ALFAYAD
- **Communication/SI** : F. Davesne (chef de projet)
- **Support administratif** : M. Bourgeois
- **Équipes** : É. Angel (AROBAS), G. Hutzler (COSMO), A. Chellali + G. Loup (IRA2), S. Ahmed Ali + D. Fourer (SIAM)
- **Système d'information** : L. Ishiomin (IBGBI), G. Bemba (Pelvoux)

## 📅 Chronologie du chantier

- **Mars-avril 2026** : décision Pr. CHU + constitution du comité Web
- **Avril-mai 2026** : enquête membres (34 réponses sur 127 actifs)
- **11 mai 2026** : Comité Web n°1 (Pelvoux, salle Ax10)
- **16 mai 2026** : clôture de l'enquête
- **20 mai 2026** : Note de cadrage v1.0 + Addendum
- **Fin mai / début juin 2026** : Comité Web n°2 (IBGBI)

## ⚖️ Gouvernance documentaire

Le statut juridique de l'organisation GitHub `ibiscweb` est rattaché au laboratoire IBISC. Les droits d'écriture sont limités aux administrateurs désignés (F. Davesne, L. Ishiomin, G. Bemba).

Ce dépôt constitue une solution **transitoire**. À terme, une migration des documents internes derrière le CAS UEVE est envisagée (arbitrage 2 du comité n°2).

---

*Laboratoire IBISC --- Université Évry Paris-Saclay*
*Document généré automatiquement par `deploy-projet-si.sh` v1.1*
