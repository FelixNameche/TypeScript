# TypeScript

![logo](TStitle.png)

## Introduction

### TypeScript, kezako ?

TypeScript est un surensemble de JavaScript ainsi qu'un compilateur.

![ts1](TS1.png)


À mis chemin entre un langage et un outils.

TS utilise sa propre syntaxe (comme un langage basé sur JS) et proche de celle de Java sans pour autant trop séloigné de JS. Il ne requiert pas de bibliothèque comme les autres langages découlant de JS, il a juste besoin de NodeJS pour fonctionner. Et finalement, une fois le développement terminer TS n'a plus d'intérêt (le côté outils).

L'intérêt avec TS c'est de pouvoir utiliser plus aisément certaines choses que JS permet, mais de façon complexe, j'y reviendrais plus tard. Un autre avantage de TS c'est la sécurité lors du développement. Pour l'exemple, il exige de préciser ce qui sera placer dans une variable (bien qu'optionnel) afin que par après, si on tente d'y mettre un autre type de donnée, TS nous avertis par une erreur.

### Quels sont les avantages ?

Il est modulaire et permet une programmation orienté objet (encapsulation, héritage, etc ... du coup adieu les prototype JS).

### Comment l'installer ?

__**NodeJS**__

Linux :
```
sudo apt-get update
sudo apt-get install nodejs npm
```

Windows/Mac :
```
https://nodejs.org/en/download/
```

__**TypeScript**__

Linux/Windows :
```
npm install -g typescript
tsc -v
```

Mac :
```
https://www.dyclassroom.com/howto-mac/how-to-install-typescript-on-mac-using-node-npm
```

### Les Types

Où les changements ce font par rapport à JS ?

Dans l'utilisation des strings, des nombres, des booléens, des arrays, du type "any", le void ainsi que le null (même s'ils sont pour ainsi dire identique à JS) et les tuples.
