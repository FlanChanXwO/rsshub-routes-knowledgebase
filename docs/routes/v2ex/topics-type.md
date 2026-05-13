# V2EX - 最热 / 最新主题

## Coverage
`index-only`

## Route
- Namespace: `v2ex`
- Namespace Name: `V2EX`
- Route Path: `/topics/:type`
- Route Name: `最热 / 最新主题`
- Example: `/v2ex/topics/latest`
- URL: `v2ex.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `WhiteWorld`
- Source Location: `topics.ts`
- Source Module: `() => import('@/routes/v2ex/topics.ts')`

## Description
_None_

## Parameters
- `type`: {"default": "hot", "description": "主题类型", "options": [{"label": "最热主题", "value": "hot"}, {"label": "最新主题", "value": "latest"}]}


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
    "bbs"
  ],
  "example": "/v2ex/topics/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topics.ts",
  "maintainers": [
    "WhiteWorld"
  ],
  "module": "() => import('@/routes/v2ex/topics.ts')",
  "name": "最热 / 最新主题",
  "parameters": {
    "type": {
      "default": "hot",
      "description": "主题类型",
      "options": [
        {
          "label": "最热主题",
          "value": "hot"
        },
        {
          "label": "最新主题",
          "value": "latest"
        }
      ]
    }
  },
  "path": "/topics/:type",
  "view": 0
}
```
