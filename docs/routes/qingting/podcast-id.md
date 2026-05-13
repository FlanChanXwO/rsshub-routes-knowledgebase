# 蜻蜓 FM - 播客

## Coverage
`index-only`

## Route
- Namespace: `qingting`
- Namespace Name: `蜻蜓 FM`
- Route Path: `/podcast/:id`
- Route Name: `播客`
- Example: `/qingting/podcast/293411`
- URL: `qingting.fm`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `RookieZoe, huyyi, pseudoyu`
- Source Location: `podcast.ts`
- Source Module: `() => import('@/routes/qingting/podcast.ts')`

## Description
获取的播放 URL 有效期只有 1 天，需要开启播客 APP 的自动下载功能。

## Parameters
- `id`: 专辑id, 可在专辑页 URL 中找到


## Features
- `supportPodcast`: true
- `requireConfig`: [{"description": "用户id， 部分专辑需要会员身份，用户id可以通过从网页端登录蜻蜓fm后使用开发者工具，在控制台中运行JSON.parse(localStorage.getItem(\"user\")).qingting_id获取", "name": "QINGTING_ID", "optional": true}]

## Radar
### Rule 1
- `source`:
  - `qingting.fm/channels/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "获取的播放 URL 有效期只有 1 天，需要开启播客 APP 的自动下载功能。",
  "example": "/qingting/podcast/293411",
  "features": {
    "requireConfig": [
      {
        "description": "用户id， 部分专辑需要会员身份，用户id可以通过从网页端登录蜻蜓fm后使用开发者工具，在控制台中运行JSON.parse(localStorage.getItem(\"user\")).qingting_id获取",
        "name": "QINGTING_ID",
        "optional": true
      }
    ],
    "supportPodcast": true
  },
  "location": "podcast.ts",
  "maintainers": [
    "RookieZoe",
    "huyyi",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/qingting/podcast.ts')",
  "name": "播客",
  "parameters": {
    "id": "专辑id, 可在专辑页 URL 中找到"
  },
  "path": "/podcast/:id",
  "radar": [
    {
      "source": [
        "qingting.fm/channels/:id"
      ]
    }
  ]
}
```
