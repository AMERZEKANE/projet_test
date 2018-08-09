# commandes HDFS

les commandes les plus utilisées : Créer un dossier dans HDFS :

### hadoop fs -mkdir 
  Exemple :

* hadoop fs -mkdir /user/monDossier

* hadoop fs -mkdir /user/monDossier1  /user/monDossier2  /user/monDossier3

  commande :

### hadoop fs -ls 
  Exemple :

* hadoop fs -ls /user

* hadoop fs -ls /user/monDossier
## Charger un ou plusieurs fichiers du local à HDFS:

 Commande :

### hadoop fs -put  
  Exemple :

* hadoop fs -put /home/monFichier.txt /user/monDossier
## Exporter un ou plusieurs fichiers de HDFS au local:

  Commande:

### hadoop fs -get  
  Exemple :

* hadoop fs -get /user/monDossier/monFichier.txt /home
## Copier un ou plusieurs fichiers dans HDFS:

  Commande :

### hadoop fs -cp   
  Exemple :

* hadoop fs -cp /user/monDossier1/monFichier.txt  /user/monDossier2
## Déplacer un ou plusieurs fichiers dans HDFS:

  Commande :

### hadoop fs -mv   
  Exemple :

* hadoop fs -mv /user/monDossier1/monFichier.txt  /user/monDossier2
## Charger un ou plusieurs fichiers du local à HDFS: Cette commande est similaire à -put

  Commande :
 
### hadoop fs -copyFromLocal  
  Exemple :

* hadoop fs -copyFromLocal /home/monFichier.txt /user/monDossier
## Exporter un ou plusieurs fichiers de HDFS au local:

  Commande:

### hadoop fs -copyToLocal  
  Exemple :

* hadoop fs -copyToLocal /user/monDossier/monFichier.txt /home
## Cette commande est similaire à -get Afficher le contenu d’un fichier:

  Commande:

### hadoop fs -cat <Path[Filename]>
Exemple :

* hadoop fs -cat /user/monFichier.txt
## Afficher les dernières lignes d’un fichier:

  Commande :

### hadoop fs -tail <Path[Filename]>
  Exemple :

* hadoop fs -tail /user/monFichier.txt
## Supprimer un fichier dans HDFS:

Commande :

### hadoop fs -rm 
   Exemple :

* hadoop fs -rm /user/monFichier.txt
## Suppression récursive dans HDFS:

  Commande :

### hadoop fs -rmr 
    Exemple :

* hadoop fs -rmr /user/

