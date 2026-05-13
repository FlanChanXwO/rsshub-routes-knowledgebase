# ÖVW - ÖVW Suche

## Coverage
`index-only`

## Route
- Namespace: `oevw`
- Namespace Name: `ÖVW`
- Route Path: `/:json?`
- Route Name: `ÖVW Suche`
- Example: `/oevw/%7B%22rooms%22%3A%5B%222%22%2C%223%22%5D%7D`
- URL: `oevw.at`
- Language: `_None_`
- Categories: `other`
- Maintainers: `sk22`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/oevw/index.ts')`

## Description
When applying a filter on https://www.oevw.at/suche, a POST request is sent
to https://www.oevw.at/suche/filter. You can take its JSON body, URL-encode it
(`encodeURIComponent('{...}')`) and append it to the URL, see example URL.
for this route.

## Parameters
- `json`: JSON request body, as sent to oevw.at/suche


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "\nWhen applying a filter on https://www.oevw.at/suche, a POST request is sent\nto https://www.oevw.at/suche/filter. You can take its JSON body, URL-encode it\n(`encodeURIComponent('{...}')`) and append it to the URL, see example URL.\nfor this route.",
  "example": "/oevw/%7B%22rooms%22%3A%5B%222%22%2C%223%22%5D%7D",
  "location": "index.ts",
  "maintainers": [
    "sk22"
  ],
  "module": "() => import('@/routes/oevw/index.ts')",
  "name": "ÖVW Suche",
  "parameters": {
    "json": "JSON request body, as sent to oevw.at/suche"
  },
  "path": "/:json?"
}
```
