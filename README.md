
## Run local server
```
bundle exec jekyll serve --livereload
```
## Customize default theme minima
Accessing theme:
```
open $(bundle info --path minima)
```

## Deployment
```
bundle exec jekyll build && \
cp -R _site/ ../thelitdeveloper.github.io
```