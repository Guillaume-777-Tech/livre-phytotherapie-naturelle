# Dossier de relecture scientifique et juridique

> Ticket #6 : Relecture scientifique et juridique. Ce dossier est destiné au relecteur (professionnel de santé / juriste du droit de l'édition). Il dit **quoi vérifier, où, et dans quel ordre de priorité**.

---

## 1. Ce que ce livre est — et n'est pas (rappel pour cadrer la relecture)

- **Est** : un ouvrage d'information et de culture générale sur les usages traditionnels et documentés des plantes et substances naturelles.
- **N'est pas** : un ouvrage de conseils médicaux, une prescription, un traitement.
- Position éditoriale assumée : vocabulaire encadré (« soulager », « accompagner », jamais « guérir »), usages traditionnels signalés comme tels, sources citées.
- Le relecteur valide cette position, ou propose les ajustements nécessaires.

## 2. Documents à relire (ordre de priorité)

### 🔴 Priorité 1 — validité juridique et sanitaire

| Document | Point de contrôle |
|----------|-------------------|
| `docs/introduction-avertissement.md` | Avertissement sanitaire : conforme aux usages d'édition santé en France ; mentions pharmacovigilance ; vocabulaire |
| `docs/partie-5-utiliser-en-securite.md` (ch. 21–22) | **Tableau des interactions** : exactitude, absence d'omission majeure, niveau de preuve à préciser fiche par fiche |
| `docs/partie-5-utiliser-en-securite.md` (ch. 23) | Drapeaux rouges : conformité avec les consignes de santé publique (numéros d'urgence, seuils de fièvre) |
| 13 monographies 🚩 | Encadrés de sécurité : millepertuis, consoude, achillée, lierre, hysope, sauge, trèfle rouge, angélique, mélilot, ginseng, éleuthérocoque, grande camomille, eschscholtzia, gentiane |

**Liste des plantes 🚩 avec leur point juridique/ sanitaire clé :**
1. **Millepertuis** — interactions médicamenteuses majeures documentées (contraceptifs oraux, AVK, immunosuppresseurs, antirétroviraux) : à vérifier mot pour mot
2. **Sauge** — contre-indications hormonodépendances, HE neurotoxique
3. **Consoude** — usage externe uniquement, interdiction orale (alcaloïdes pyrrolizidiques)
4. **Lierre** — baies toxiques, posologie stricte
5. **Hysope** — HE épileptisante
6. **Mélilot** — interactions anticoagulantes, conservation (dicoumarol)
7. **Trèfle rouge** — phyto-œstrogènes
8. **Angélique** — photosensibilisation, coumarines
9. **Grande camomille** — interactions anticoagulantes, grossesse
10. **Ginseng / Éleuthérocoque** — HTA, AVK
11. **Gentiane** — espèce protégée : citer les arrêtés de protection exacts
12. **Achillée** — grossesse, Astéracées
13. **Eschscholtzia** — conduite, sédation

### 🟠 Priorité 2 — exactitude scientifique

| Document | Point de contrôle |
|----------|-------------------|
| `docs/liste-50-plantes.md` | Noms latins exacts, familles botaniques à jour (ex. la classification du romarin et du gattilier a changé) |
| `docs/plantes/*.md` (50 fiches) | Usages traditionnels vs documentés : chaque citation EMA à vérifier (numéro de monographie) ; posologies dans les fourchettes des monographies |
| `docs/partie-2-guide-des-preparations.md` | Grille des températures (ch. 8) : valeurs à sourcer ; tableau des durées de conservation (ch. 9) |
| `docs/partie-4-substances-naturelles.md` | HE : règles de dilution et populations (ch. 17) ; miel < 1 an (ch. 18) : conformité recommandations sanitaires |
| `docs/partie-1-comprendre-avant-d-agir.md` | Tableau des familles d'actifs (ch. 4) : simplifications acceptables ? Histoire (ch. 3) : dates et faits |

### 🟡 Priorité 3 — éléments annexes

| Document | Point de contrôle |
|----------|-------------------|
| `docs/sites-et-sources-fiables.md` | **Re-vérification obligatoire de chaque enseigne** (la liste est datée du 30 octobre 2026) ; formulation « indicative » à valider juridiquement |
| `docs/regles-illustrations.md` | Modèles de crédits : conformité droit d'auteur ; tableau de suivi des droits à faire valider par le juriste |
| Annexe C (dosages) et annexe D (températures) | À générer à la maquette : le relecteur valide la structure |

## 3. Les règles éditoriales à valider (déjà appliquées dans tout le livre)

Le relecteur confirme (ou corrige) ces 5 règles :

1. **🌡️ Températures** : toute préparation liquide chauffée indique la température cible et la sensibilité des actifs (grille : macérat à froid / 50–80 °C / 80–90 °C / ~95 °C).
2. **🌍 Origine** : priorité France, pays source indiqué sinon.
3. **🔗 Fournisseurs** : liste d'herboristeries factuelle, datée, sans affiliation.
4. **🖼️ Images** : crédit sous chaque image ; image protégée = autorisation écrite obligatoire.
5. **📅 Traçabilité** : dates de proposition/vérification affichées (liste des sites, licences d'images).

## 4. Points d'attention signalés par l'auteur (honnêteté de relecture)

Les zones où je sais que le brouillon est perfectible :

- **Sources des fiches** : les monographies citent l'EMA en référence principale mais **ne donnent pas encore les numéros de monographies ni les références complètes** — c'est précisément le travail de bibliographie du relecteur.
- **Posologies** : les fourchettes sont issues d'usages traditionnels croisés ; le relecteur doit les confronter aux monographies EMA/OMS et signaler toute divergence.
- **Chapitre 22 (interactions)** : tableau de synthèse à partir des fiches — toute omission dans une fiche doit être corrigée aux deux endroits.
- **Chapitre 3 (histoire)** : quelques dates et anecdotes à fact-checker (Dioscoride, Hildegarde, suppression du diplôme d'herboriste en 1941).
- **Chapitre 20 (aliments)** : ail/curcuma/citron — les affirmations d'absorption (allicine, pipérine) sont à sourcer précisément.
- **Miel « antibactérien »** : le chapitre 18 mentionne l'usage traditionnel sur plaies — formulation à valider pour rester dans l'usage traditionnel, pas l'allégation de soin.

## 5. Livrables attendus du relecteur

| Livrable | Format |
|----------|--------|
| Corrections et ajouts | Directement dans les documents du dépôt (ou annotations) |
| Bibliographie normalisée | Un document `docs/bibliographie.md` (structure validée au chap. 24) |
| Validation des 13 encadrés rouges | Mention explicite fiche par fiche |
| Validation des règles éditoriales | Les 5 règles ci-dessus, une par une |
| Avis juridique final | Avertissement p. 2, crédits images, liste des sites, mentions légales |

## 6. État des tickets concernés

| Ticket | Sujet | Statut |
|--------|-------|--------|
| #1 | Plan détaillé | À fermer après validation du dossier |
| #2 | Fiche type | À fermer après validation |
| #3 | Liste des 50 plantes | À fermer après vérification des noms latins |
| #4 | Introduction + avertissement | ✅ Fermé (v0.1 validée) |
| #5 | Illustrations | Règles rédigées ; brief graphique à lancer après relecture |
| #6 | **Cette relecture** | Le présent dossier en est le cadre |
