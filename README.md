# Ligne de commandes linux et autres tricks

## Lignes de commande linux

* Supprimer un dossier et son contenu

```cmd
rm -rf dirname
```

## Lignes de commande Anaconda

* Info sur les environnements

```cmd
conda info -e
```

* Supprimer un environnement

```cmd
conda remove --name [ENVIRONNEMENT] --all 

```




## Github

### Configuration authentification github

Marre de tapper son logging/ password dans VsCode.

Creer une fichier .netrc dans le repertoire racine /user/.netrc

```.netrc
machine github.com
login toto
password blabla
```

## Commands lines npm

**connaitre les package installe globalement**

```cmd
npm ls -g
```

## Eclipse

**Raccourcie**

Ctr+Shift+f ==> Indentation code

**Afficher toutes la documentations Eclipse**

[JAVADOC](http://objis.com/tutoriel-java-n4-integration-de-la-javadoc-jse-dans-eclipse/)


## VsCode

**Raccourcie**

Shift+Alt+F ==> Indentation code

## netstat

[netstat](http://www.faqs.org/docs/linux_network/)

Ecouter les ports 

```cmd
netstat -ta
```
* Controle du port ex:9000 a remplacer le cas echeant

```cmd
netstat -ano | findstr :9000
  TCP    0.0.0.0:9000           0.0.0.0:0              LISTENING       7836
  TCP    [::]:9000              [::]:0                 LISTENING       7836
```
Retourne le numer o de PORT ici 7836

* Kill port 7836

```cmd
taskkill /PID 7836 /F
Opération réussie : le processus avec PID 7836 a été terminé.
```
## Fuser

Permet de fermer le port 548

```cmd
fuser- k 548/tcp 
```
