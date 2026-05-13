# Plurk - Plurk News

## Coverage
`index-only`

## Route
- Namespace: `plurk`
- Namespace Name: `Plurk`
- Route Path: `/news/:lang?`
- Route Name: `Plurk News`
- Example: `/plurk/news/:lang?`
- URL: `plurk.com/news`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/plurk/news.ts')`

## Description
_None_

## Parameters
- `lang`: Language, see the table above, `en` by default


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
  - `plurk.com/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/plurk/news/:lang?",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/plurk/news.ts')",
  "name": "Plurk News",
  "parameters": {
    "lang": "Language, see the table above, `en` by default"
  },
  "path": "/news/:lang?",
  "radar": [
    {
      "source": [
        "plurk.com/news"
      ],
      "target": "/news"
    }
  ],
  "url": "plurk.com/news"
}
```
