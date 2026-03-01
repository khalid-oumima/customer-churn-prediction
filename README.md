# 🚀 Prédiction du Churn Client (Télécom)

Ce projet utilise le Machine Learning pour identifier les clients risquant de quitter un opérateur télécom.

## 🎯 Objectif Business
Réduire le taux d'attrition (churn) en identifiant les profils instables afin de proposer des campagnes de rétention ciblées.

## 🛠️ Stack Technique
- **Modèle :** Random Forest Classifier (Scikit-Learn)
- **Interface :** Streamlit (Python)
- **Analyse :** Pandas, Matplotlib, Seaborn

## 📈 Résultats du Modèle
- **Précision :** ~80%
- **Facteur n°1 de churn :** Le type de contrat (Contrats courts/mois par mois).
- **Facteur n°2 :** Le montant des charges mensuelles.

## 💻 Comment lancer l'application
1. Cloner le projet : `git clone https://github.com/TON_PSEUDO/customer-churn-prediction.git`
2. Installer les dépendances : `pip install -r requirements.txt`
3. Lancer l'app : `streamlit run app.py`
