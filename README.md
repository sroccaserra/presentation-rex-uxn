Slides de présentation d'un REX sur Uxn dans Uxn, pour OCTO Technology.

Quelques infos sur la philosophie et l'intention de Uxn :

- <https://100r.co/site/uxn_design.html>

### Prérequis

La lib SDL2.

Des versions précompilées 64 bits de la VM pour Linux, Windows et macOS sont
dispos ici (~ 50 ko):

- <https://100r.co/site/uxn.html>

Le programme qui lit et affiche les slides est la rom "adelie.rom" (24 ko).

- <https://rabbits.srht.site/adelie/adelie.rom> ~ 35f22cf1

### Ouvrir les slides

Charger la rom d'adelie dans la VM, avec comme argument le chemin relatif vers les slides :

```
$ uxnemu -s 2 adelie.rom slides
```

### Sources et versions de la VM pour OS plus anciens

Certains vieux OS ont déjà des versions précompilées.

Le nombre de portages de cette VM sur des OS / systèmes différents d'âges
variés montre la facilité de l'implémenter, c'est assez rare pour un système
qui inclut des images et du son.

#### Sources de la VM de référence

Pour compiler la VM Uxn de référence à partir des sources, il faudra
git, la lib SDL2 en version dev, et un compilateur C.

- <https://git.sr.ht/~rabbits/uxn> ~ d64600e7

#### La VM sous DOS

- <https://git.sr.ht/~rabbits/uxn-vga>

#### La VM pour Windows NT / 2000 / XP / Vista (avec versions précompilées)

- <https://github.com/randrew/uxn32>

#### La VM pour X11, sans SDL2

- <https://git.sr.ht/~rabbits/uxn11>

### Liens de la présentation

- Uxn Design ~ <https://100r.co/site/uxn_design.html>
- Uxn implemetation ~ <https://git.sr.ht/~rabbits/uxn/tree/main/item/src/uxn.c>
