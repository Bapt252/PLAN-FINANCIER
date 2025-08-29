# 📊 Simulateur Financier Tenex

Un outil de planification financière complet pour jobboards SaaS, spécialement conçu pour les métiers supports en Île-de-France.

## 🎯 Vue d'ensemble

Ce simulateur permet de modéliser et prévoir la croissance financière d'un business SaaS avec des abonnements récurrents. Il prend en compte tous les aspects financiers : revenus, charges, marketing, équipe et trésorerie.

## ✨ Fonctionnalités principales

### 💰 Configuration des offres
- Définition d'offres multiples avec tarifs personnalisés
- Objectifs de clients par offre sur 12 mois
- Calcul automatique du MRR (Monthly Recurring Revenue)

### 📈 Simulation financière
- Projections sur 12 mois avec calculs automatiques
- Modélisation de la croissance et du churn
- Evolution de la trésorerie mois par mois

### 🎯 Métriques SaaS
- **MRR/ARR** : Revenus récurrents mensuels et annuels
- **CAC** : Coût d'acquisition client avec budget marketing
- **LTV/CAC Ratio** : Rentabilité de l'acquisition
- **Runway** : Mois restants de trésorerie
- **Break-even** : Seuil de rentabilité

### 👥 Gestion des charges
- **Équipe** : Salaires avec charges sociales (45% par défaut)
- **Outils SaaS** : Hébergement, CRM, analytics, support
- **Frais généraux** : Bureau, assurances, juridique
- **Charges variables** : Indexées sur le CA (15% par défaut)

### 📊 Dashboard interactif
- Graphiques en temps réel (Chart.js)
- KPI colorés selon performance
- 4 graphiques : MRR, marge nette, clients, cash flow

### 💾 Sauvegarde et historique
- Système de sauvegarde avec horodatage
- Export/Import JSON des configurations
- Historique des 10 dernières versions

## 🚀 Utilisation

### Accès direct
Ouvrez le simulateur : **[https://bapt252.github.io/PLAN-FINANCIER/](https://bapt252.github.io/PLAN-FINANCIER/)**

### Étapes d'utilisation
1. **Configurez vos offres** : Définissez tarifs et objectifs clients
2. **Paramétrez les charges** : Équipe, outils, frais généraux
3. **Ajustez les métriques** : Churn, budget marketing, conversion
4. **Analysez les résultats** : Consultez simulation et KPI
5. **Sauvegardez** : Exportez pour réutiliser vos configurations

## 📱 Interface

### Onglets disponibles
- **📝 Hypothèses** : Configuration de tous les paramètres
- **📈 Simulation** : Tableau de projection sur 12 mois  
- **📊 KPI Dashboard** : Métriques clés et graphiques
- **💾 Historique** : Sauvegardes et versions précédentes

## 🎨 Technologies

- **Frontend** : HTML5, CSS3, JavaScript vanilla
- **Graphiques** : Chart.js 3.9.1
- **Design** : CSS Grid/Flexbox, responsive
- **Hébergement** : GitHub Pages

## 📊 Métriques calculées

### Revenus
- **MRR** : Monthly Recurring Revenue par offre
- **ARR** : Annual Recurring Revenue (MRR × 12)
- **ARPU** : Average Revenue Per User pondéré

### Acquisition
- **CAC** : Budget marketing annuel ÷ nouveaux clients
- **LTV** : ARPU ÷ churn mensuel
- **Ratio LTV/CAC** : Rentabilité acquisition (objectif > 3x)

### Opérationnel
- **Churn** : Taux de perte clients mensuels
- **Croissance nette** : Nouveaux clients - clients perdus
- **Runway** : Mois de trésorerie restants
- **Break-even** : Premier mois rentable

## 🎯 Configuration recommandée

### Offres type jobboard
```
Starter   : 49€/mois  - PME locales (15 → 50 clients)
Standard  : 149€/mois - Entreprises moyennes (8 → 30 clients)  
Premium   : 299€/mois - Grands comptes (2 → 15 clients)
```

### Métriques de référence SaaS
```
Churn mensuel    : 3-7%
Conversion leads : 10-20%
LTV/CAC ratio    : >3x
Charges sociales : 42-50%
Charges variables: 10-20% CA
```

### Budget marketing réparti
```
Google Ads       : 3000€/mois
LinkedIn Ads     : 2500€/mois
Facebook/Meta    : 1500€/mois
Content/SEO      : 1000€/mois
Total            : 8000€/mois
```

## 💡 Cas d'usage

- **Startups SaaS** : Planification financière initiale
- **Scale-ups** : Modélisation de croissance
- **Investisseurs** : Due diligence et projections
- **Équipes Finance** : Budget prévisionnel
- **Fondateurs** : Validation d'hypothèses business

## 🔧 Développement local

```bash
# Cloner le repository
git clone https://github.com/Bapt252/PLAN-FINANCIER.git
cd PLAN-FINANCIER

# Ouvrir dans le navigateur
open index.html
```

## 📈 Exemple de simulation

**Configuration de base :**
- Trésorerie initiale : 50 000€
- Budget marketing : 8 000€/mois  
- Churn : 5%/mois
- Conversion : 12%

**Résultats attendus M12 :**
- 95 clients actifs
- MRR : ~12 000€
- ARR : ~144 000€
- Runway : 8-10 mois

## 🤝 Contribution

Pour améliorer le simulateur :
1. Fork le repository
2. Créez une branche feature
3. Commitez vos changements
4. Soumettez une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

---

**Développé pour Tenex** - Simulateur financier SaaS v1.0

Pour toute question : [Créer une issue](https://github.com/Bapt252/PLAN-FINANCIER/issues)