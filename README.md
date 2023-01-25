# 2020
Website for Open Infrastructure &amp; Cloud Native Days Indonesia 2020

# How to contribute?
Clone this repository,
```bash
git clone https://github.com/openinfraid/2020.git
```
then to this on your shell,
```bash
podman run --rm -it -p 1313:1313 -v $(pwd):/src --env HUGO_ENVIRONMENT=production --env HUGO_ENV=production klakegg/hugo:0.87.0-ext-ubuntu server --minify
```
U can access web page on your browser, http://localhost:1313
