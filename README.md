# Portefolio

Ce site web a été crée par Quentin CHEVRIAUX dans le cadre de l'EU "TRANS-10 Environnement socio-economique" encadrée par Mme Catherine BARRY à L'UPJV.

Il se base sur un squelette pré-établie et répond a une annonce qui a été selectionnée lors d'un rendu precedent.

## Mise en place

Si vous venez de télécharger se repo sur le git l'utilisation de la commande suivant permettra d'installer les dépendances
```
    npm install
```

Si vous n'avez pas node et npm veuillez vous reférée au [site officiel de node.js pour le téléchargé](https://nodejs.org/en/)
## Commande npm
Pour compiler les fichier SCSS
```
    npm run css
```

Pour compiler les fichers blade
```
    npm run blade
```

## Structure du repo

Le site web compiler ce trouve dans le dossier docs
Le reste du site contient le code qui permet de généré ces fichiers
 - template : Contient les fichier HTML utilisé par blade
 - assets : Contient les fichiers scss et js qui on besoin d'etre transformé avant d'etre utilisé dans publique.