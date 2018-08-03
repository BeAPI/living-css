# Living CSS

## Étape 1

Cloner le dossier à la racine du thème.

## Étape 2

Dans le package.json, ajouter dans le script de build:

```
&& cd livingcss && npm install && gulp livingcss
```

Et le script supplémentaire;

```
"livingcss": "cd livingcss && npm install && gulp livingcss && gulp sass"
```

## Étape 3

```
npm run build
```

### Enjoy \o/ !