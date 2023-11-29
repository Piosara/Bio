L'objectif de ce programme est de représenter la généalogie la plus probable entre les individus listés dans un fichier csv,
en fonction de leurs différents marqueurs. Le programme renvoie un graphique permettant cette représentation. 

Afin de s'assurer du bon fonctionnement du programme, il convient d'installer python 3.10 en le téléchargeant au lien suivant:
https://www.python.org/downloads/
Sous Windows, il faudra aussi s'assurer que les chemins suivants sont accesibles dans le Path:
C:\Users\login\AppData\Local\Programs\Python\Python310\Scripts\
C:\Users\login\AppData\Local\Programs\Python\Python310\
Le lien suivant explique la modification des chemins selon la version de Windows utilisée: https://fr.mathworks.com/matlabcentral/answers/94933-how-do-i-edit-my-system-path-in-windows
Le fichier zip nécessitera d'être décompressé avant utilisation.
Il s'agira ensuite d'exécuter le Launcher (en ignorant d'éventuels messages d'avertissement),
par exemple en double-cliquant sur celui-ci. Si les packages numpy, pandas, igraph, et Pillow ne sont pas déjà installés,
ils peuvent être directement installés en cliquant sur "Installer les packages requis" dans la fenêtre ouverte par le Launcher.
L'utilisateur peut aussi les télécharger manuellement avec la commande (respectivement à chaque package):
pip install nom_du_package

Un fichier CSV au format proposé en cours devra être choisi par l'utilisateur dans un format click-bouton.
Une fois le fichier choisi, il suffira d'appuyer sur "Lancer le script" pour faire fonctionner le programme.
En cas d'éventuelles erreurs liées aux packages utilisés, il conviendra de les mettre à jour avec la commande suivante:
pip install --upgrade nom_du_package

