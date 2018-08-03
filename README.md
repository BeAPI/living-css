# Living CSS

Dans le package.json, ajouter dans le script de build

```
&& cd livingcss && npm install && gulp livingcss
```

Et le script supplémentaire

```
"livingcss": "cd livingcss && npm install && gulp livingcss && gulp sass"
```