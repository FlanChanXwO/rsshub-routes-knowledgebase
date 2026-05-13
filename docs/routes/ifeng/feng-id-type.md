# 凤凰网 - 大风号

## Coverage
`index-only`

## Route
- Namespace: `ifeng`
- Namespace Name: `凤凰网`
- Route Path: `/feng/:id/:type`
- Route Name: `大风号`
- Example: `/ifeng/feng/2583/doc`
- URL: `feng.ifeng.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `Jamch`
- Source Location: `feng.ts`
- Source Module: `() => import('@/routes/ifeng/feng.ts')`

## Description
| 文章 | 视频  |
| ---- | ----- |
| doc  | video |

## Parameters
- `id`: 对应 id，可在 大风号作者页面 找到
- `type`: 类型，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 文章 | 视频  |\n| ---- | ----- |\n| doc  | video |",
  "example": "/ifeng/feng/2583/doc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "feng.ts",
  "maintainers": [
    "Jamch"
  ],
  "module": "() => import('@/routes/ifeng/feng.ts')",
  "name": "大风号",
  "parameters": {
    "id": "对应 id，可在 大风号作者页面 找到",
    "type": "类型，见下表"
  },
  "path": "/feng/:id/:type"
}
```
