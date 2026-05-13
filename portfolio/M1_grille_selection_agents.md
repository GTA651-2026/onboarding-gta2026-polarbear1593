# M1 — Grille de sélection et évaluation de solutions IA

## Contexte 1 — PME de 50 employés

**Description :** Cabinet de services professionnels (ex: génie-conseil) à Sherbrooke. Maturité numérique moyenne (utilisent déjà Microsoft 365), budget IA limité (~15k$ - 20k$), équipe IT réduite à un seul administrateur système. Soumis à la Loi 25 sur la protection des données.

| Critère | Brex | Salesforce Einstein | Microsoft Copilot 365 |
|---|---|---|---|
| **1. Rôle spécialisé orchestré** | **Contrôleur financier (CFO) :** Automatisation des notes de frais et conformité. | **Analyste des ventes :** Priorisation prédictive des opportunités commerciales. | **Adjoint à la rédaction :** Synthèse de réunions et rédaction de rapports techniques. |
| **2. Impact d'affaires** | **4/5** : Réduction massive du temps administratif pour la direction financière. | **2/5** : Impact limité si le volume de leads n'exige pas de priorisation IA. | **5/5** : Gain de productivité quotidien pour 100% des employés de bureau. |
| **3. Faisabilité PME** | **5/5** : Solution SaaS native, nécessite peu de nettoyage de données préalable. | **1/5** : Nécessite une instance Salesforce propre et des compétences de gestion de données. | **4/5** : Intégration facile si l'infrastructure M365 est déjà en place. |
| **4. Coût estimé** | ~0$ - 1 000$ (frais de service variables, pas de licences lourdes). | ~40 000$+ (coût cumulé CRM + licences Einstein + intégration). | ~24 000$ / an (environ 40$ CAD / usager / mois pour 50 pers.). |
| **5. Risque principal** | **Sécurité financière :** Accès aux fonds. *Mitigation :* Plafonds de dépenses stricts. | **Données biaisées :** Mauvais conseils de vente. *Mitigation :* Audit des données initial. | **Loi 25 :** Fuite de données sensibles. *Mitigation :* Configuration des politiques de sécurité M365. |

### Recommandation pour la PME

Microsoft Copilot 365 est la solution à déployer en priorité, car elle offre le meilleur rapport impact/faisabilité pour une organisation sans équipe de données dédiée. Elle bat Einstein par sa simplicité d'intégration et Brex par son utilité transversale pour tous les "knowledge workers" du cabinet.

---

## Contexte 2 — Grande entreprise de 500+ employés

**Description :** Manufacturier québécois avec distribution internationale. Utilise un ERP complexe (ex: SAP) et Salesforce comme CRM central. Gouvernance stricte, équipe TI dédiée et sponsor exécutif identifié.

| Critère | Brex | Salesforce Einstein | Microsoft Copilot 365 |
|---|---|---|---|
| **1. Rôle spécialisé orchestré** | **Auditeur de dépenses :** Surveillance automatisée des politiques de frais mondiales. | **Directeur de la stratégie commerciale :** Prévision des revenus (Forecasting). | **Gestionnaire de base de connaissances :** Navigation dans l'information corporative. |
| **2. Impact d'affaires** | **3/5** : Gain d'efficacité, mais valeur incrémentale faible face à un ERP robuste. | **5/5** : Une hausse de 5% du taux de conversion génère des revenus massifs. | **4/5** : Réduction du "bruit" informationnel pour les cadres et la gestion. |
| **3. Faisabilité** | **2/5** : Difficile d'intégrer Brex aux systèmes bancaires et ERP régionaux disparates. | **4/5** : Données déjà centralisées ; l'équipe TI peut gérer le nettoyage et l'optimisation. | **3/5** : Risque de sur-partage d'information interne sans gouvernance préalable. |
| **4. Coût estimé** | ~15k$ - 25k$ (intégration et support spécifique). | ~150k$+ / an (licences Enterprise + support expert interne). | ~250k$+ / an (30$ USD/usager pour 500+ employés). |
| **5. Risque principal** | **Silos de données :** Incompatibilité ERP. *Mitigation :* Connecteurs API personnalisés. | **Hallucinations :** Prévisions de ventes erronées. *Mitigation :* Validation humaine systématique. | **Sécurité des documents :** Accès de l'IA à des dossiers restreints. *Mitigation :* Audit SharePoint. |

### Recommandation pour la grande entreprise

Salesforce Einstein est le choix stratégique, car l'avantage compétitif réside ici dans la précision décisionnelle plutôt que dans la simple productivité individuelle. Contrairement à la PME, la grande entreprise possède les ressources TI pour transformer les prédictions d'Einstein en un levier de croissance mesurable.

---

## Synthèse — ce que la grille révèle

Le critère de la faisabilité organisationnelle (données propres et compétences TI) a été le facteur décisif, dépassant la simple puissance technique de l'IA. Cela enseigne que la sélection d'une solution IA est un acte d'alignement stratégique : en PME, on privilégie l'agilité et la polyvalence, alors qu'en grande entreprise, on cherche la spécialisation à haut impact sur le revenu. La grille montre que le contexte détermine la pondération des critères, une leçon fondamentale pour l'Examen-cas 1.

> **Crédit :** Jalon M1 — pass/fail (1,5 % du cours). Préparation directe à l'**Examen-cas 1** (S05, 25 %).

