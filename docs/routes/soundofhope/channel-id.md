# 希望之声 - 频道

## Coverage
`index-only`

## Route
- Namespace: `soundofhope`
- Namespace Name: `希望之声`
- Route Path: `/:channel/:id`
- Route Name: `频道`
- Example: `/soundofhope/term/203`
- URL: `soundofhope.org`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `Fatpandac`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/soundofhope/channel.ts')`

## Description
参数均可在官网获取，如：

  `https://www.soundofhope.org/term/203` 对应 `/soundofhope/term/203`

## Parameters
- `channel`: 频道
- `id`: 子频道 ID


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
  - `soundofhope.org/:channel/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "参数均可在官网获取，如：\n\n  `https://www.soundofhope.org/term/203` 对应 `/soundofhope/term/203`",
  "example": "/soundofhope/term/203",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "channel.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/soundofhope/channel.ts')",
  "name": "频道",
  "parameters": {
    "channel": "频道",
    "id": "子频道 ID"
  },
  "path": "/:channel/:id",
  "radar": [
    {
      "source": [
        "soundofhope.org/:channel/:id"
      ]
    }
  ]
}
```
