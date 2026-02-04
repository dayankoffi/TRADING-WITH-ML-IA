Si vous n'arrivez pas à lancer le fichier jupiter, veuillez lancer ce lien pour l'avoir directement par " Google Collab "
https://colab.research.google.com/github/dayankoffi/TRADING-WITH-ML-IA/blob/main/Trade_ML_IA.ipynb#scrollTo=c2ec034e

# TRADING-WITH-ML-IA
Designed a trading strategy on the S&amp;P 500 combining macroeconomic factors, market sentiment analysis (VADER), and machine learning models (LightGBM) using python

L'objectif principal est de construire une base de données consolidée combinant plusieurs sources d'informations pour prédire ou identifier des opportunités de marché sur l'indice S&P 500 (^GSPC). Le projet couvre la période allant de janvier 2018 à juillet 2020.
NB: Les données sont journalière, donc trading daily

Les outils suivants sont utilisés pour le traitement des données et l'analyse :

Analyse de données : pandas, numpy.

Données Financières : yfinance (Yahoo Finance), fredapi (Données de la Réserve Fédérale).

Visualisation : plotly.

Traitement du Langage Naturel (NLP) : nltk (VADER pour l'analyse de sentiment).

Gestion de Base de données : SQLAlchemy, PyMySQL.

Pour exécuter ce notebook :

Assurez-vous d'avoir installé les dépendances nécessaires (pip install yfinance pandas fredapi nltk plotly sqlalchemy pymysql).

Vous devrez disposer d'une clé API FRED valide (celle incluse dans le code est 647427cf56b3b2ed607cbb90a8c76bef).

Exécutez les cellules séquentiellement pour générer les indicateurs et les graphiques.

Veuillez lancer le code sur "Google Collabs" pour beneficier de ma base d'information de marché sur le S&P , je ne l'ai pas ajouté par API car cela demande un paiement, si vous arrivez à ajoutez des infos de marchés par API dans le code vous avez la possibilité d'agrandir l'horizon de trading et même trader en temps réel.
