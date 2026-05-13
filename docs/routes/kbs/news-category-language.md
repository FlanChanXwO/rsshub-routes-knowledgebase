# KBS - News

## Coverage
`index-only`

## Route
- Namespace: `kbs`
- Namespace Name: `KBS`
- Route Path: `/news/:category?/:language?`
- Route Name: `News`
- Example: `/kbs/news`
- URL: `world.kbs.co.kr/`
- Language: `ko`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/kbs/news.ts')`

## Description
| 한국어 | عربي | 中国语 | English | Français | Deutsch | Bahasa Indonesia | 日本語 | Русский | Español | Tiếng Việt |
| ------ | ---- | ------ | ------- | -------- | ------- | ---------------- | ------ | ------- | ------- | ---------- |
| k      | a    | c      | e       | f        | g       | i                | j      | r       | s       | v          |

## Parameters
- `category`: Category, can be found in Url as `id`, all by default
- `language`: Language, see below, e as English by default


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
  - `world.kbs.co.kr/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 한국어 | عربي | 中国语 | English | Français | Deutsch | Bahasa Indonesia | 日本語 | Русский | Español | Tiếng Việt |\n| ------ | ---- | ------ | ------- | -------- | ------- | ---------------- | ------ | ------- | ------- | ---------- |\n| k      | a    | c      | e       | f        | g       | i                | j      | r       | s       | v          |",
  "example": "/kbs/news",
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
  "module": "() => import('@/routes/kbs/news.ts')",
  "name": "News",
  "parameters": {
    "category": "Category, can be found in Url as `id`, all by default",
    "language": "Language, see below, e as English by default"
  },
  "path": "/news/:category?/:language?",
  "radar": [
    {
      "source": [
        "world.kbs.co.kr/"
      ],
      "target": "/news"
    }
  ],
  "url": "world.kbs.co.kr/"
}
```
