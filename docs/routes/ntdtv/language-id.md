# 新唐人电视台 - 频道

## Coverage
`index-only`

## Route
- Namespace: `ntdtv`
- Namespace Name: `新唐人电视台`
- Route Path: `/:language/:id`
- Route Name: `频道`
- Example: `/ntdtv/b5/prog1201`
- URL: `www.ntdtv.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `Fatpandac`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/ntdtv/channel.ts')`

## Description
参数均可在官网获取，如：

  `https://www.ntdtv.com/b5/prog1201` 对应 `/ntdtv/b5/prog1201`

## Parameters
- `language`: 语言，简体为`gb`，繁体为`b5`
- `id`: 子频道名称


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
  - `www.ntdtv.com/:language/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "参数均可在官网获取，如：\n\n  `https://www.ntdtv.com/b5/prog1201` 对应 `/ntdtv/b5/prog1201`",
  "example": "/ntdtv/b5/prog1201",
  "features": {
    "antiCrawler": false,
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
  "module": "() => import('@/routes/ntdtv/channel.ts')",
  "name": "频道",
  "parameters": {
    "id": "子频道名称",
    "language": "语言，简体为`gb`，繁体为`b5`"
  },
  "path": "/:language/:id",
  "radar": [
    {
      "source": [
        "www.ntdtv.com/:language/:id"
      ]
    }
  ]
}
```
