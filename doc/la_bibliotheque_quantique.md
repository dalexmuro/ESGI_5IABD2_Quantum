# ESGI_5IABD2_Quantum

## Algorithme de Grover - La bibliothèque quantique
Niveau de difficulté = 4 / 5
<br>
*Avec avantage quantique

### La situation :
Bob est victime d'un mauvais sort il se sent toujours un peu déphasé.
Il sait que le rituel pour lever cette malédiction est consignée dans un grimoire qui se trouve dans une bibliothèque quantique.

Le problème est que dans une bibliothèque quantique l'emprunt se fait toujours au hasard. En empruntant un grimoire, on ne sait pas
sur lequel on va tomber.<br>

La bonne nouvelle est que cette section de la bibliothèque ne compte que trois autres grimoires. La mauvaise c'est que ceux-ci ne
contiennent que plus de malédiction.

![img_004.png](..%2Fimg%2Fimg_004_a.png)

### Le défi :
Trouver le bon grimoire avec 100% de certitude.

### La stratégie
Pour lui aider, Bob fait appel à Aika, qui a le pouvoir de marquer le bon grimoire en inversant sa phase quantique.

Il doit utiliser les pouvoirs d'inversion de phase d'Aika et sa maîtrise de l'interférence pour 
maximiser ses chances d'emprunter le bon grimoire et ainsi lever le mauvais sort que lui afflige.

En combinant ses connaissances à celles d'Aika, il mettra en place un algorithme bien connu en informatique quantique : *l'algorithme de Grover*.

La bibliothèque quantique attribue initialement une chance égale d'emprunter n'importe lequel de ces grimoires dans l'état actuel des choses.

Lorsqu'on emprunte un grimoire, on a une chance sur quatre de tomber sur le bon. On peut, donc, attribuer à chacun des grimoires une probabilité de 1/4.
Pour décrire la situation dans le monde quantique, on assigne d’abord chaque grimoire à un état quantique.
Ensuite, il est plus facile de travailler avec l'histogramme des amplitudes de probabilité, qui permettent de montrer la phase de chaque État.
Les amplitudes de probabilité de chaque État sont fixés à 1/2.
Les probabilités d'obtenir chacun de ces résultats sont en fait donnés par le carré de l'amplitude de probabilité.

![img_004_b.png](..%2Fimg%2Fimg_004_b.png)

Initialement, chaque grimoire a une amplitude de probabilité de 1/2 et une probabilité de 1/2 au carré est 1/4.
Aike utilise son pouvoir pour marquer le grimoire dans lequel se trouve le rituel en inversant sa phase.
Mais il ne faut pas aller emprunter un grimoire trop vite. En effet, la probabilité d'emprunter le bon grimoire n'a pas changé et il y a toujours une chance sur 4.
Bob prend alors le relais avec un opérateur quantique qu'il a conçu et qu'il appelle le diffuseur.
Il agit d'une manière bien particulière : 

Illustrons son application sur un seul grimoire, c'est-à-dire : sur un histogramme ou un grimoire à 100% des chances d'être emprunté, par exemple le numéro 0.

![img_004_c.png](..%2Fimg%2Fimg_004_c.png)

Le diffuseur produit alors une superposition uniforme de tous les États, mais où la phase du grimoire de départ est inversée.

![img_004_d.png](..%2Fimg%2Fimg_004_d.png)

L'effet de ce diffuseur sur l'état 01 est :

![img_004_e.png](..%2Fimg%2Fimg_004_e.png)

Son effet sur l'état 1 0 qui serait déphasé est :

![img_004_f.png](..%2Fimg%2Fimg_004_f.png)

Et finalement sur l'état 11 :

![img_004_g.png](..%2Fimg%2Fimg_004_g.png)

Le diffuseur, lorsque appliqué sur l'état préparé par Aïka, agit sur les quatre grimoires en parallèle comme si chaque grimoire avait 100% de chance d'être emprunté.

![img_004_h.png](..%2Fimg%2Fimg_004_h.png)
![img_004_i.png](..%2Fimg%2Fimg_004_i.png)

L'État qu'il produit est simplement la somme des 4 résultats individuels.

![img_004_j.png](..%2Fimg%2Fimg_004_j.png)

L'application du diffuseur permet donc aux amplitudes de probabilité d'interférer entre elles.
Ainsi les amplitudes négatives compensent les amplitudes positives et les positives s'additionnent entre elles,
ce qui augmente l'amplitude associée au grimoire recherché et diminue l'amplitude des autres.

Dans le cas présent, l'application de l'inversion de phase et de l'opérateur d'interférence augmente à 100% la probabilité d'emprunt du bon grimoire.

![img_004_k.png](..%2Fimg%2Fimg_004_k.png)


### Vidéo explicative :
[![Les Énigmes quantiques - Algorithme de Grover - La bibliothèque quantique](https://img.youtube.com/vi/YFe5MEPo09I/0.jpg)](https://www.youtube.com/watch?v=YFe5MEPo09I)