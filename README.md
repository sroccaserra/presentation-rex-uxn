Slides de présentation d'un REX sur Uxn dans Uxn, pour OCTO Technology.

### Prérequis

Avertissement : ce n'est pas un PDF ni un PPT, pour voir ces slides il faut git,
SDL2 avec la lib de dev, et un compilateur, afin de compiler la VM Uxn.

Pour télécharger les sources et compiler la VM sur un OS moderne :

- https://git.sr.ht/~rabbits/uxn ~ d64600e7

Le programme qui lit et affiche les slides est la rom "adelie.rom" (24 ko).

- https://rabbits.srht.site/adelie/adelie.rom ~ 35f22cf1

### Ouvrir les slides

Charger la rom d'adelie dans la VM, avec comme argument le chemin relatif vers les slides :

```
$ uxnemu -s 2 adelie.rom slides
```

### Sur des OS plus anciens

La VM sous DOS :

- https://git.sr.ht/~rabbits/uxn-vga

La VM pour Windows NT / 2000 / XP / Vista (avec versions précompilées)

- https://github.com/randrew/uxn32

La VM pour X11, sans SDL2 :

- https://git.sr.ht/~rabbits/uxn11
