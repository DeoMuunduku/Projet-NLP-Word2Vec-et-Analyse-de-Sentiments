# Projet-NLP-Word2Vec-et-Analyse-de-Sentiments
Projet Word2Vec

Ce projet utilise le modèle Word2Vec pour analyser des similitudes entre des termes et effectuer une analyse de sentiments à partir de données extraites de Wikipédia. Le projet est présenté dans un notebook Jupyter.
![ảnh](https://github.com/user-attachments/assets/7cc847b8-7535-4518-9193-b8a9d09aa044)

Table des Matières

	•	Aperçu
	•	Prérequis
	•	Installation
	•	Utilisation
	•	Résultats
	•	Analyse de Sentiments
	•	Contributions
	•	Licence  

Aperçu

Dans ce projet, nous entraînons notre propre modèle Word2Vec en utilisant le contenu de la page Wikipédia sur la “computer science”. Nous comparons les résultats de notre modèle local avec ceux d’un modèle pré-entraîné (word2vec-google-news-300).

Prérequis

	•	Python 3.x
	•	Jupyter Notebook
	•	Bibliothèques Python : gensim, nltk, sklearn, matplotlib, pandas

Installation
git clone https://github.com/votre-utilisateur/word2vec-projet.git
cd word2vec-projet
2.	Installez les dépendances :
pip install gensim nltk sklearn matplotlib pandas

pip install gensim nltk sklearn matplotlib pandas

2.	Suivez les étapes dans le notebook pour entraîner le modèle et analyser les résultats.


Résultats

Les résultats de similitude pour le terme “computer” et “software” sont les suivants :

	•	Modèle pré-entraîné (word2vec-google-news-300) : La similarité entre “Computer” et “Software” est de 0.46974862.
	•	Modèle entraîné localement : La similarité entre “computer” et “software” est de 0.1368767.

 ![ảnh](https://github.com/user-attachments/assets/3b75d821-4581-4e50-90df-efe29c56d642)


La différence de similarité observée est normale et attendue en raison des différences de taille et de qualité du corpus d’entraînement.

Analyse de Sentiments

L’analyse de sentiments est également réalisée dans le notebook pour évaluer les sentiments positifs ou négatifs des textes extraits. Veuillez vous référer au notebook pour plus de détails et les résultats complets.

Contributions

Les contributions sont les bienvenues. Veuillez soumettre une pull request ou ouvrir une issue pour discuter des changements proposés.

Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails
