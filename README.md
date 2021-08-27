
## Run local server
bundle exec jekyll serve --livereload

## Customize default theme minima
Accessing theme:
```
open $(bundle info --path minima)
```

## Deployment
```
jekyll build && cd _site && cp -R . ../../thelitdeveloper.github.io/
```