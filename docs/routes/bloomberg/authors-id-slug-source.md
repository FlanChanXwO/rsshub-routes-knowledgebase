# Bloomberg - Authors

## Coverage
`index-only`

## Route
- Namespace: `bloomberg`
- Namespace Name: `Bloomberg`
- Route Path: `/authors/:id/:slug/:source?`
- Route Name: `Authors`
- Example: `/bloomberg/authors/ARbTQlRLRjE/matthew-s-levine`
- URL: `www.bloomberg.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `josh, pseudoyu`
- Source Location: `authors.ts`
- Source Module: `() => import('@/routes/bloomberg/authors.ts')`

## Description
_None_

## Parameters
- `id`: Author ID, can be found in URL
- `slug`: Author Slug, can be found in URL
- `source`: Data source, either `api` or `rss`,`api` by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.bloomberg.com/*/authors/:id/:slug`
  - `www.bloomberg.com/authors/:id/:slug`
- `target`: `/authors/:id/:slug`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/bloomberg/authors/ARbTQlRLRjE/matthew-s-levine",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "authors.ts",
  "maintainers": [
    "josh",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/bloomberg/authors.ts')",
  "name": "Authors",
  "parameters": {
    "id": "Author ID, can be found in URL",
    "slug": "Author Slug, can be found in URL",
    "source": "Data source, either `api` or `rss`,`api` by default"
  },
  "path": "/authors/:id/:slug/:source?",
  "radar": [
    {
      "source": [
        "www.bloomberg.com/*/authors/:id/:slug",
        "www.bloomberg.com/authors/:id/:slug"
      ],
      "target": "/authors/:id/:slug"
    }
  ],
  "view": 0
}
```
