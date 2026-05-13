# 极术社区 - 频道、专栏、用户

## Coverage
`index-only`

## Route
- Namespace: `aijishu`
- Namespace Name: `极术社区`
- Route Path: `/:type/:name?`
- Route Name: `频道、专栏、用户`
- Example: `/aijishu/channel/ai`
- URL: `www.aijishu`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `None`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/aijishu/index.ts')`

## Description
| type    | 说明 |
| ------- | ---- |
| channel | 频道 |
| blog    | 专栏 |
| u       | 用户 |

## Parameters
- `type`: 文章类型，可以取值如下
- `name`: 名字，取自URL


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
    "programming"
  ],
  "description": "| type    | 说明 |\n| ------- | ---- |\n| channel | 频道 |\n| blog    | 专栏 |\n| u       | 用户 |",
  "example": "/aijishu/channel/ai",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [],
  "module": "() => import('@/routes/aijishu/index.ts')",
  "name": "频道、专栏、用户",
  "parameters": {
    "name": "名字，取自URL",
    "type": "文章类型，可以取值如下"
  },
  "path": "/:type/:name?"
}
```
