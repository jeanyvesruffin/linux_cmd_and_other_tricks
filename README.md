# Ligne de commandes linux et autres tricks

## Lignes de commande linux



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


## VsCode

**Raccourcie**

Ctr+Shift+i ==> Indentation code

## netstat

[netstat](http://www.faqs.org/docs/linux_network/)

Ecouter les ports 

```cmd
netstat -ta
```

## Fuser

Permet de fermer le port 548

```cmd
fuser- k 548/tcp 
```
