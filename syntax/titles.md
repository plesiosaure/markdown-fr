# Titres

Pour commencer à écrire un document en markdown, il est nécessaire d'ajouter un titre et des sous-titres.

Le Markdown accepte deux styles d'entêtes, Setext et atx.


Les entêtes Setext-style sont soulignés à l'aide du signe égal (pour le premier niveau) et des tirets (pour l second niveau). Par exemple : 

```
Ceci est un H1
=============

Ceci est un H2
-------------
```

Any number of underlining =’s or -’s will work.
Vous pouvez souligner avec autant de = ou de - que vous le souhaitez

Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:
Les entêtes atx utilisent de 1 à 6 caractères dièse en début de ligne, correspondant aux niveaux 1 à 6. Par exemple :

```
# Ceci est un H1

## Ceci est un H2

###### Ceci est un H6
```


Optionally, you may “close” atx-style headers. This is purely cosmetic — you can use this if you think it looks better. The closing hashes don’t even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :

```
# This is an H1 #

## This is an H2 ##

### This is an H3 ######
```


---

Here's a quiz about markdown titles.

Select the valid headers:
- [x] `# hello`
- [ ] `#hello`

> Headers need space between the hash characters and the text.

Select the valid headers:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Only '=' and '-' are accepted for underlining an header.

---


