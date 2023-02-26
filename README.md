# OID2020

Website for OpenInfra Days Indonesia 2020

## How to contribute?

Run this,
```bash
docker run --rm -it -p 8080:8080 -v $(pwd):/src --env HUGO_ENVIRONMENT=production --env HUGO_ENV=production klakegg/hugo:0.87.0-ext-ubuntu server -p 8080
```

You can access it now in `http://localhost:8080` ,
And do any changes.
