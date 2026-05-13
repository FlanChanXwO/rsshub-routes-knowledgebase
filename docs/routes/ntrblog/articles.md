# NTR BLOG（寝取られブログ） - Articles

## Coverage
`index-only`

## Route
- Namespace: `ntrblog`
- Namespace Name: `NTR BLOG（寝取られブログ）`
- Route Path: `/articles`
- Route Name: `Articles`
- Example: `/ntrblog/articles`
- URL: `ntrblog.com`
- Language: `ja`
- Categories: `anime`
- Maintainers: `keocheung`
- Source Location: `articles.ts`
- Source Module: `() => import('@/routes/ntrblog/articles.ts')`

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
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `ntrblog.com`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/ntrblog/articles",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "articles.ts",
  "maintainers": [
    "keocheung"
  ],
  "module": "() => import('@/routes/ntrblog/articles.ts')",
  "name": "Articles",
  "path": "/articles",
  "radar": [
    {
      "source": [
        "ntrblog.com"
      ]
    }
  ]
}
```
