<div align="center">
  
# Churn bancaire

</div>


Cette analyse explore les déterminants du churn (départ des clients) dans le secteur bancaire en comparant les profils des clients partis et restés. Les résultats révèlent que les clients ayant quitté la banque sont en moyenne plus âgés (44 ans vs 37 ans), possèdent un solde plus élevé (71 209 € vs 51 255 €), mais souscrivent à moins de produits (1,33 vs 1,62). Ces insights permettent d'identifier des leviers d'action pour réduire le churn, comme le ciblage des clients seniors ou l'incitation à l'adoption de produits supplémentaires.

---

## 📊 Données
- **Source** : [Kaggle - Bank churn](https://www.kaggle.com/datasets/rangalamahesh/bank-churn/data)
- **Champs principaux** :
  - Customer ID - L'identifiant unique de chaque client.
  - Credit Score - Un nombre indiquant la solvabilité du client.
  - Geography - Le pays où le client est domicilié bancairement.
  - Gender - Le genre avec lequel le client s'identifie.
  - Age - L'âge du client.
  - Tenure - La durée en années pendant laquelle le client est avec la banque.
  - Balance -  Le montant actuellement disponible sur le compte du client.
  - NumOfProducts -  Le nombre de produits achetés par le client via la banque.
  - HasCrCard - Indique si le client a une carte de crédit.
  - IsActiveMember - Indique si le client est actif ou inactif.
  - EstimatedSalary - L'estimation bancaire du revenu du client.
  - Exited - Indique si le client a quitté la banque ou non.

---

## 🧹 Préparation des données

---

## 🚀 Visualisations
![](https://github.com/FabienHaury/Churn/blob/main/Screenshoots/Graphiques/graph_age.png)   
![](https://github.com/FabienHaury/Churn/blob/main/Screenshoots/Graphiques/graph_gender_pie.png)   


| Exited  | Age moyen | Age median | Age min | Age max | Score de crédit moyen | Score de crédit std | Solde moyem | Salaire estimé moyen | Nb de produits moyen | Nombre de clients | % Effectifs |
|----------|----------|------------|---------|---------|------------------|-----------------|--------------|----------------------|-------------------|------------------|-------------|
| Churned | 44       | 44         | 18      | 92      | 652              | 81              | 71209.98     | 114402.50            | 1.33              | 34921            | 21.16       |
| Retained | 37       | 36         | 18      | 92      | 658              | 80              | 51255.81     | 112084.29            | 1.62              | 130113           | 78.84       |

---

## 📈 Résultats 


---

## 💡 Suggestions  

---

## 🛠️ Outils
- **Python** : Pandas, Seaborn (Préparation, Analyses visuelles)

---

## 📬 Contact  
- 📧 [Email](mailto:67912775+FabienHaury@users.noreply.github.com)  
- 💼 [LinkedIn](https://www.linkedin.com/in/fabienhaury/)
