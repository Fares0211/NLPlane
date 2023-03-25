# NLPlane

Ce projet consiste un chatbot NLP qui utilise la similarité cosinus pour trouver la réponse la plus appropriée à une question posée par l'utilisateur. Il est implémenté avec Streamlit pour offrir une interface utilisateur conviviale.

## Installation

Les bibliothèques nécessaires pour faire fonctionner le chatbot sont les suivantes :

pandas
nltk
numpy
random
string
bs4
re
sklearn
streamlit
Il est également nécessaire de télécharger tous les fichiers NLTK à l'aide de nltk.download('all').

## Fonctionnement

Le chatbot fonctionne en récupérant les questions-réponses à partir d'un fichier CSV, en prétraitant le texte pour le nettoyer et en créer des vecteurs de mots à l'aide de TfidfVectorizer. Ensuite, il calcule la similarité cosinus entre la question de l'utilisateur et les questions-réponses stockées pour trouver la réponse la plus appropriée.

Le chatbot peut également reconnaître les salutations de l'utilisateur et y répondre avec une réponse prédéfinie.

Le chatbot est exécuté via Streamlit. L'utilisateur peut poser des questions à l'aide de la zone de texte et le chatbot affichera la réponse appropriée. Les messages échangés entre l'utilisateur et le chatbot sont stockés dans l'historique et affichés dans l'interface utilisateur.

Le chatbot peut être exécuté en exécutant la commande streamlit run nom_du_fichier.py dans le terminal, en supposant que toutes les bibliothèques requises ont été installées.
