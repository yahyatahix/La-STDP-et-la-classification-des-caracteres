# Etude des différentes formes de STDP et utilisation pour la classification de MNIST
Les  réseaux  de  neurones  à  décharges  s'inspirent  ducomportement des neurones biologiques pour les modéliser etoffrent de nouvelles opportunités pour atteindre l'objectif del'intelligence artificielle en se basant sur l'intelligence humaine. Dans  les  réseaux  de  neurones  intelligents,  la  méthoded'apprentissage standard est la rétropropagation. Cependant, laSTDP, qui est une méthode non supervisée, est biologiquementplus plausible.  Ce projet est basé sur l'article de Diehl &amp; Cook[1], qui fournit une méthode d'apprentissage non supervisé pourla classification d'images qui utilise la STDP et sur les notebookd'Ismaël  Balafrej  et  Ahmad  El  Ferdaoussi.  Ainsi,pour  laréalisation  de  ce  projet,  nous  avons  utilisé  la  bibliothèque brian2 de python ainsi que l'environnement Jupyter notebook. 

######################################## Description

Ce dossier est destiné dans un premier temps à l'étude des différentes formes de STDP et dans un second temps
à la résolution d'un problème de classification de caractères manuscrits (base de données MNIST) en utilisant la STDP.

######################################## Structures

Ce dossier contient :

	* Partie_1_Etude_STDP.ipynb : Un fichier notebook mettant en relief quelques formes de la STDP, ainsi l'effet
de la fréquence sur l'impact de la STDP et un moyen d'y remedier

	* Entrainement_Validation.ipynb : Un fichier notebook contenant le code permettant d'entrainer un 
réseau de neurones et de le valider.

	* Test.ipynb : Un fichier notebook contenant le code permettant de tester le réseau de neurones 
créé afin de connaitre les performances.

	* labelfile : Un fichier contenant les labels trouvés dans le fichier Entrainement_Validation.ipynb

	* weightfile : Un fichier contenant les poids trouvés dans le fichier Entrainement_Validation.ipynb

	* weightHistoryfile : Un fichier contenant l'évolution des poids trouvés dans le fichier Entrainement_Validation.ipynb

######################################## Exécution

Ce peut être exécuté dans un environement Jupyter Notebook avec python 3.
La bibliothèque Brian2 a été utilisée.
NB: Pour le système d'exploitation windows il est nécessaire d'avoir l'environement Microsoft visual c++

######################################## Auteurs

* ETTAHI Yahya
* WAHBI Yasmine
* YARGA Arnaud
