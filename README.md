# markdown-cv

See original repository for details https://github.com/elipapa/markdown-cv

## Running in docker
```
docker run --rm -p 4000:4000 -v ${pwd}:/srv/jekyll -it jekyll/jekyll:3.8 jekyll serve --force_polling
```
`--force_polling` is needed on Windows, some details here https://github.com/envygeeks/jekyll-docker/issues/281
