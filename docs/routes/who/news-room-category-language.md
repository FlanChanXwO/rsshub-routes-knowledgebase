# World Health Organization | WHO - Newsroom

## Coverage
`index-only`

## Route
- Namespace: `who`
- Namespace Name: `World Health Organization | WHO`
- Route Path: `/news-room/:category?/:language?`
- Route Name: `Newsroom`
- Example: `/who/news-room/feature-stories`
- URL: `who.int/news`
- Language: `en`
- Categories: `government`
- Maintainers: `LogicJake, nczitzk`
- Source Location: `news-room.ts`
- Source Module: `() => import('@/routes/who/news-room.ts')`

## Description
Category

| Feature stories | Commentaries |
| --------------- | ------------ |
| feature-stories | commentaries |

  Language

| English | العربية | 中文 | Français | Русский | Español | Português |
| ------- | ------- | ---- | -------- | ------- | ------- | --------- |
| en      | ar      | zh   | fr       | ru      | es      | pt        |

## Parameters
- `category`: Category, see below, Feature stories by default
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
  - `who.int/news-room/:type`
- `target`: `/news-room/:type`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "Category\n\n| Feature stories | Commentaries |\n| --------------- | ------------ |\n| feature-stories | commentaries |\n\n  Language\n\n| English | العربية | 中文 | Français | Русский | Español | Português |\n| ------- | ------- | ---- | -------- | ------- | ------- | --------- |\n| en      | ar      | zh   | fr       | ru      | es      | pt        |",
  "example": "/who/news-room/feature-stories",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news-room.ts",
  "maintainers": [
    "LogicJake",
    "nczitzk"
  ],
  "module": "() => import('@/routes/who/news-room.ts')",
  "name": "Newsroom",
  "parameters": {
    "category": "Category, see below, Feature stories by default",
    "language": "Language, see below, English by default"
  },
  "path": "/news-room/:category?/:language?",
  "radar": [
    {
      "source": [
        "who.int/news-room/:type"
      ],
      "target": "/news-room/:type"
    }
  ],
  "url": "who.int/news"
}
```
