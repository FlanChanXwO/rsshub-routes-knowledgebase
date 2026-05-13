# 日本語多読道場 - 等级

## Coverage
`index-only`

## Route
- Namespace: `yomujp`
- Namespace Name: `日本語多読道場`
- Route Path: `/:level?`
- Route Name: `等级`
- Example: `/yomujp/n1`
- URL: `yomujp.com/`
- Language: `ja`
- Categories: `reading`
- Maintainers: `eternasuno`
- Source Location: `level.ts`
- Source Module: `() => import('@/routes/yomujp/level.ts')`

## Description
_None_

## Parameters
- `level`: 等级，n1~n6，为空默认全部


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
  - `yomujp.com/`
  - `yomujp.com/:level`
- `target`: `/:level`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/yomujp/n1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "level.ts",
  "maintainers": [
    "eternasuno"
  ],
  "module": "() => import('@/routes/yomujp/level.ts')",
  "name": "等级",
  "parameters": {
    "level": "等级，n1~n6，为空默认全部"
  },
  "path": "/:level?",
  "radar": [
    {
      "source": [
        "yomujp.com/",
        "yomujp.com/:level"
      ],
      "target": "/:level"
    }
  ],
  "url": "yomujp.com/"
}
```
