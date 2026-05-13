# World Health Organization | WHO - News

## Coverage
`index-only`

## Route
- Namespace: `who`
- Namespace Name: `World Health Organization | WHO`
- Route Path: `/news/:language?`
- Route Name: `News`
- Example: `/who/news`
- URL: `who.int/news`
- Language: `en`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/who/news.ts')`

## Description
Language

| English | العربية | 中文 | Français | Русский | Español | Português |
| ------- | ------- | ---- | -------- | ------- | ------- | --------- |
| en      | ar      | zh   | fr       | ru      | es      | pt        |

## Parameters
- `language`: Language, see below, English by default


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
  - `who.int/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "Language\n\n| English | العربية | 中文 | Français | Русский | Español | Português |\n| ------- | ------- | ---- | -------- | ------- | ------- | --------- |\n| en      | ar      | zh   | fr       | ru      | es      | pt        |",
  "example": "/who/news",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/who/news.ts')",
  "name": "News",
  "parameters": {
    "language": "Language, see below, English by default"
  },
  "path": "/news/:language?",
  "radar": [
    {
      "source": [
        "who.int/news"
      ],
      "target": "/news"
    }
  ],
  "url": "who.int/news"
}
```
