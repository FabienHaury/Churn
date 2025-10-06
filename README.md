<div align="center">
  
# Churn bancaire

</div>


Cette analyse explore les déterminants du churn (départ des clients) dans le secteur bancaire en comparant les profils des clients partis et restés. Les résultats révèlent que les clients ayant quitté la banque sont en moyenne plus âgés (44 ans vs 37 ans), possèdent un solde plus élevé (71 209 € vs 51 255 €), mais souscrivent à moins de produits (1,33 vs 1,62). Ces insights permettent d'identifier des leviers d'action pour réduire le churn, comme le ciblage des clients seniors ou l'incitation à l'adoption de produits supplémentaires.

---

## 📊 Données
- **Source** : [Kaggle - Bank churn](https://www.kaggle.com/datasets/rangalamahesh/bank-churn/data)
- **Champs principaux** :
  - **Customer ID** : L'identifiant unique de chaque client.
  - **Credit Score** : Un nombre indiquant la solvabilité du client.
  - **Geography** : Le pays où le client est domicilié bancairement.
  - **Gender** : Le genre avec lequel le client s'identifie.
  - **Age** : L'âge du client.
  - **Tenure** : La durée, en années, pendant laquelle le client est resté avec la banque.
  - **Balance** : Le montant actuellement disponible sur le compte du client.
  - **NumOfProducts** : Le nombre de produits achetés par le client via la banque.
  - **HasCrCard** : Indique si le client possède une carte de crédit.
  - **IsActiveMember** : Indique si le client est actif ou inactif.
  - **EstimatedSalary** : L'estimation bancaire du revenu du client.
  - **Exited** : Indique si le client a quitté la banque ou non.

---

## 🧹 Préparation des données
- **IsActiveMember** : Les scores 0 ou 1 sont remplacés par des valeurs plus explicites : *Non actif* ou *Actif*.
- **HasCrCard** : Les scores 0 ou 1 sont remplacés par des valeurs plus explicites : *Carte de crédit* ou *Pas de carte de crédit*.
- **Exited** : Les scores 0 ou 1 sont remplacés par des valeurs plus explicites : *Retenus* ou *Partis*.

---

## 🚀 Visualisations
![](https://github.com/FabienHaury/Churn/blob/main/Screenshoots/Graphiques/graph_age.png)   
![](https://github.com/FabienHaury/Churn/blob/main/Screenshoots/Graphiques/graph_gender_pie.png)   

### Comparaison des clients partis et restés
| Exited  | Age moyen | Age median | Age min | Age max | Score de crédit moyen | Score de crédit std | Solde moyem | Salaire estimé moyen | Nb de produits moyen | Nombre de clients | % Effectifs |
|----------|----------|------------|---------|---------|------------------|-----------------|--------------|----------------------|-------------------|------------------|-------------|
| Churned | 44       | 44         | 18      | 92      | 652              | 81              | 71209.98     | 114402.50            | 1.33              | 34921            | 21.16       |
| Retained | 37       | 36         | 18      | 92      | 658              | 80              | 51255.81     | 112084.29            | 1.62              | 130113           | 78.84       |

---

## 📈 Résultats
- Le taux de rétention est d'environ **79 %**, mais le taux de churn moyen pour ce secteur est de **5 %**. Il existe donc un écart significatif entre le taux de churn de la banque (**21 %**) et la moyenne du secteur.
- On observe clairement une différence dans les âges moyens entre les clients restés et ceux partis.
- Le score de crédit ne semble pas être un facteur déterminant pour prévoir le départ d'un client.

---

## 💡 Suggestions
- Une étude plus approfondie est nécessaire.
- Des données supplémentaires sont requises pour confirmer ou infirmer les résultats, comme :
  - Les catégories des produits achetés.
  - Les réponses aux questionnaires de départ.
- Mener des campagnes de recrutement pour les pays sous-représentés.

---

## 🛠️ Outils
- **Python** : Pandas, Seaborn (Préparation, Analyses visuelles)

---

## 📬 Contact  
- 📧 [Email](mailto:67912775+FabienHaury@users.noreply.github.com)  
- 💼 [LinkedIn](https://www.linkedin.com/in/fabienhaury/)
