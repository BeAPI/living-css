# Living CSS

## Styleguide

SASS file are commented in order to generate a living styleguide using `npm run livingcss`
It is also available at `your_local_url/livingcss/html/` and watched by `gulp serve`
For more details look at : https://github.com/straker/livingcss

## Step 1

Clone the folder in the theme root.

## Step 2

In package.json, add this script in build command:

```
&& cd livingcss && npm install && gulp livingcss
```

And this one more in scripts:

```
"livingcss": "cd livingcss && npm install && gulp livingcss && gulp sass"
```

## Step 3

```
npm run build
```

## Step 4

You can check you're livingcss in your local env like: http://localhost:3000/living-css/html/

### Enjoy \o/ !