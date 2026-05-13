# MeriTalk - Latest Articles

## Coverage
`index-only`

## Route
- Namespace: `meritalk`
- Namespace Name: `MeriTalk`
- Route Path: `/articles`
- Route Name: `Latest Articles`
- Example: `/meritalk/articles`
- URL: `meritalk.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `superguyDiluc`
- Source Location: `articles.ts`
- Source Module: `() => import('@/routes/meritalk/articles.ts')`

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
  - `meritalk.com/articles/`
- `target`: `/articles`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/meritalk/articles",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "articles.ts",
  "maintainers": [
    "superguyDiluc"
  ],
  "module": "() => import('@/routes/meritalk/articles.ts')",
  "name": "Latest Articles",
  "path": "/articles",
  "radar": [
    {
      "source": [
        "meritalk.com/articles/"
      ],
      "target": "/articles"
    }
  ]
}
```
