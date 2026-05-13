# Rock the JVM - Article

## Coverage
`index-only`

## Route
- Namespace: `rockthejvm`
- Namespace Name: `Rock the JVM`
- Route Path: `/articles`
- Route Name: `Article`
- Example: `/rockthejvm/articles`
- URL: `rockthejvm.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `articles.ts`
- Source Module: `() => import('@/routes/rockthejvm/articles.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `rockthejvm.com/articles`
- `target`: `/articles`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/rockthejvm/articles",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "articles.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/rockthejvm/articles.ts')",
  "name": "Article",
  "path": "/articles",
  "radar": [
    {
      "source": [
        "rockthejvm.com/articles"
      ],
      "target": "/articles"
    }
  ],
  "url": "rockthejvm.com",
  "view": 0
}
```
