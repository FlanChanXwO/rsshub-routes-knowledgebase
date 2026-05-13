# Paul Graham - Essays

## Coverage
`index-only`

## Route
- Namespace: `paulgraham`
- Namespace Name: `Paul Graham`
- Route Path: `/essays`
- Route Name: `Essays`
- Example: `/paulgraham/articles`
- URL: `paulgraham.com/articles.html`
- Language: `en`
- Categories: `blog`
- Maintainers: `Maecenas, nczitzk, dvorak0`
- Source Location: `article.ts`
- Source Module: `() => import('@/routes/paulgraham/article.ts')`

## Description
_None_

## Parameters
_None_


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
  - `paulgraham.com/articles.html`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/paulgraham/articles",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "article.ts",
  "maintainers": [
    "Maecenas",
    "nczitzk",
    "dvorak0"
  ],
  "module": "() => import('@/routes/paulgraham/article.ts')",
  "name": "Essays",
  "parameters": {},
  "path": [
    "/articles",
    "/essays",
    "/"
  ],
  "radar": [
    {
      "source": [
        "paulgraham.com/articles.html"
      ]
    }
  ],
  "url": "paulgraham.com/articles.html"
}
```
