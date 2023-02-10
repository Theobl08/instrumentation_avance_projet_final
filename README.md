# Instrumentation Avance Projet Final
 Projet final du module "Instrumentation Avancé"

# Schema du Projet
Pour ce projet, nous allons utiliser la caméra d'un microcontôleur Arduino Nano 33 BLE Sense pour détecter un cancer de la peau grace au TinyML.
Pour cela, nous allons télécharger un dataset de cancer de la peau à https://docs.edgeimpulse.com/experts/machine-learning-prototype-projects/tinyml-gastroscopic-image-processing et utiliser deux méthode pour la construction et l'entrainement du modèle.

Nous allons d'abord utilser Edge Impulse comme première méthode, avant d'utiliser google colab avec un Jupyter Notebook et du code python pour la deuxième méthode.

Lors de la méthde avec Edge impulse, nous avons eu la même erreur que les autre étudiant au niveau de la mémoire, ce qui rend impossible la vérification.

![Screenshot1](https://user-images.githubusercontent.com/98655331/218170473-a13fee6b-15d8-4c60-8f40-4153f2537d7a.png)

Le dossier "Edge Impulse" contien le code edge impluse ainsi que les codes arduinos construit par Edge impulse lors du déploiement de l'Impulse.

Le dossier "Jupyter notebook" contient le modèle TFlite, le notebook et le code python qui a servi à générer le modèle.
