# Spark_Notebook
Template + Tuto pour monter localement un notebook spark

Tuto video : https://www.youtube.com/watch?v=XvbEADU0IPU&t=612s

Etape 1: Installer Java (ou s'assurer que Java est installé)
Etape 2: Installer Spark
Etape 3: Déclarer les variables d'environnement Java et Spark dans windows (taper environnement dans l'onglet de recherche puis dans paramètre système avancé cliquer sur Variables d'environnement).

Dans variable système :
JAVA_HOME = Chemin vers java
SPARK_HOME = Chemin vers Spark
HADOOP_HOME = Chemin vers Spark également

Dans variable utilisateur :
LOCAL = Chemin vers java bin
LOCAL = Chemin vers Spark

Etape 4 :  Dans https://github.com/steveloughran/winutils
Trouver la version correspondant à la version hadoop utilisée (dans l'exemple hadoop-2.7.1)
Dans bin télécharger le fichier winutils.exe
Coller le fichier dans le répertoire bin de Spark

Etape 5 : S'appuyer sur le notebook pour initier un projet Spark

