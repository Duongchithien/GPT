# AI Leaders Vietnam Academy Clone

## Run locally

Because this is a static website, if you open from incorrect sub-paths you may see `404` on some hosting providers.

Run with a local static server:

```bash
python3 -m http.server 8080
```

Then open:

- http://localhost:8080/

## 404 handling

This repo includes `404.html` that redirects users back to `/` to reduce broken-route errors on static hosts.
