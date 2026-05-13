# KBS - Today

## Coverage
`index-only`

## Route
- Namespace: `kbs`
- Namespace Name: `KBS`
- Route Path: `/today/:language?`
- Route Name: `Today`
- Example: `/kbs/today`
- URL: `world.kbs.co.kr/`
- Language: `ko`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `today.ts`
- Source Module: `() => import('@/routes/kbs/today.ts')`

## Description
| 한국어 | عربي | 中国语 | English | Français | Deutsch | Bahasa Indonesia | 日本語 | Русский | Español | Tiếng Việt |
| ------ | ---- | ------ | ------- | -------- | ------- | ---------------- | ------ | ------- | ------- | ---------- |
| k      | a    | c      | e       | f        | g       | i                | j      | r       | s       | v          |

## Parameters
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
- `target`: `/today`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 한국어 | عربي | 中国语 | English | Français | Deutsch | Bahasa Indonesia | 日本語 | Русский | Español | Tiếng Việt |\n| ------ | ---- | ------ | ------- | -------- | ------- | ---------------- | ------ | ------- | ------- | ---------- |\n| k      | a    | c      | e       | f        | g       | i                | j      | r       | s       | v          |",
  "example": "/kbs/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "today.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/kbs/today.ts')",
  "name": "Today",
  "parameters": {
    "language": "Language, see below, e as English by default"
  },
  "path": "/today/:language?",
  "radar": [
    {
      "source": [
        "world.kbs.co.kr/"
      ],
      "target": "/today"
    }
  ],
  "url": "world.kbs.co.kr/"
}
```
