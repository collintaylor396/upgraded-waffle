# Redirect Page

A minimal static HTML redirect page that forwards visitors to `https://shareonepoint.replit.app`, passing along any URL hash fragment.

## How to run

The project is served by Python's built-in HTTP server:

```
python3 -m http.server 5000
```

The workflow "Start application" is configured to run this automatically.

## Project structure

- `index.html` — the only file; reads `window.location.hash` and redirects to the target URL

## User preferences

_None recorded yet._
