# AllesAusserScrumWebsite


## Change main color

```
vim assets/colors/_presets.scss
compile scss (see below)
```

## Compile scss to css

```
npm install -g sass
cd AllesAusserScrumWebsite
sass assets/scss/main.scss assets/css/main.css
```

## Watch & compile scss on the fly

```
npm install -g sass
cd AllesAusserScrumWebsite

# to compile
sass assets/scss/main.scss assets/css/main.css


# to watch
sass --watch  assets/scss/main.scss assets/css/main.css
```


