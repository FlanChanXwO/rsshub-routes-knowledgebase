# 秀动网 - 按音乐人 - 演出更新

## Coverage
`index-only`

## Route
- Namespace: `showstart`
- Namespace Name: `秀动网`
- Route Path: `/artist/:id`
- Route Name: `按音乐人 - 演出更新`
- Example: `/showstart/artist/301783`
- URL: `www.showstart.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `lchtao26`
- Source Location: `artist.ts`
- Source Module: `() => import('@/routes/showstart/artist.ts')`

## Description
::: tip
音乐人 ID 查询: `/showstart/search/artist/:keyword`，如: [https://rsshub.app/showstart/search/artist/周杰伦](https://rsshub.app/showstart/search/artist/周杰伦)
:::

## Parameters
- `id`: 音乐人 ID


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
  - `www.showstart.com/artist/:id`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "::: tip\n音乐人 ID 查询: `/showstart/search/artist/:keyword`，如: [https://rsshub.app/showstart/search/artist/周杰伦](https://rsshub.app/showstart/search/artist/周杰伦)\n:::",
  "example": "/showstart/artist/301783",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "artist.ts",
  "maintainers": [
    "lchtao26"
  ],
  "module": "() => import('@/routes/showstart/artist.ts')",
  "name": "按音乐人 - 演出更新",
  "parameters": {
    "id": "音乐人 ID"
  },
  "path": "/artist/:id",
  "radar": [
    {
      "source": [
        "www.showstart.com/artist/:id"
      ]
    }
  ]
}
```
