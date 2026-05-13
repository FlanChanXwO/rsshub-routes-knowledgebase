# 华储网 - 通知

## Coverage
`index-only`

## Route
- Namespace: `mrm`
- Namespace Name: `华储网`
- Route Path: `/:category?`
- Route Name: `通知`
- Example: `/mrm`
- URL: `mrm.com.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/mrm/index.ts')`

## Description
| 交易通知     | 政策规定             | 业务通知          |
| ------------ | -------------------- | ----------------- |
| zonghezixun3 | zhengceguiding_list | yewutongzhi_list |

## Parameters
- `category`: N


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
    "finance"
  ],
  "description": "| 交易通知     | 政策规定             | 业务通知          |\n| ------------ | -------------------- | ----------------- |\n| zonghezixun3 | zhengceguiding_list | yewutongzhi_list |",
  "example": "/mrm",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/mrm/index.ts')",
  "name": "通知",
  "parameters": {
    "category": "N"
  },
  "path": "/:category?"
}
```
