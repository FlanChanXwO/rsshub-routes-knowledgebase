# AP News - Sitemap

## Coverage
`index-only`

## Route
- Namespace: `apnews`
- Namespace Name: `AP News`
- Route Path: `/sitemap/:route`
- Route Name: `Sitemap`
- Example: `/apnews/sitemap/ap-sitemap-latest`
- URL: `apnews.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `zoenglinghou, mjysci, TonyRL, dzx-dzx`
- Source Location: `sitemap.ts`
- Source Module: `() => import('@/routes/apnews/sitemap.ts')`

## Description
_None_

## Parameters
- `route`: {"description": "Route for sitemap, excluding the `.xml` extension"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `apnews.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/apnews/sitemap/ap-sitemap-latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "sitemap.ts",
  "maintainers": [
    "zoenglinghou",
    "mjysci",
    "TonyRL",
    "dzx-dzx"
  ],
  "module": "() => import('@/routes/apnews/sitemap.ts')",
  "name": "Sitemap",
  "parameters": {
    "route": {
      "description": "Route for sitemap, excluding the `.xml` extension"
    }
  },
  "path": "/sitemap/:route",
  "radar": [
    {
      "source": [
        "apnews.com/"
      ]
    }
  ],
  "view": 0
}
```
