# 东网 - Money18

## Coverage
`index-only`

## Route
- Namespace: `oncc`
- Namespace Name: `东网`
- Route Path: `/money18/:id?`
- Route Name: `Money18`
- Example: `/oncc/money18/exp`
- URL: `hk.on.cc`
- Language: `zh-HK`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `money18.ts`
- Source Module: `() => import('@/routes/oncc/money18.ts')`

## Description
| 新聞總覽 | 全日焦點 | 板塊新聞 | 國際金融 | 大行報告 | A 股新聞 | 地產新聞 | 投資理財  | 新股 IPO | 科技財情 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- | -------- | -------- |
| exp      | fov      | industry | int      | recagent | ntlgroup | pro      | weainvest | ipo      | tech     |

## Parameters
- `id`: 栏目 id，可在对应栏目页 URL 中找到，默认为 exp，即新聞總覽


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
    "traditional-media"
  ],
  "description": "| 新聞總覽 | 全日焦點 | 板塊新聞 | 國際金融 | 大行報告 | A 股新聞 | 地產新聞 | 投資理財  | 新股 IPO | 科技財情 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | --------- | -------- | -------- |\n| exp      | fov      | industry | int      | recagent | ntlgroup | pro      | weainvest | ipo      | tech     |",
  "example": "/oncc/money18/exp",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "money18.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/oncc/money18.ts')",
  "name": "Money18",
  "parameters": {
    "id": "栏目 id，可在对应栏目页 URL 中找到，默认为 exp，即新聞總覽"
  },
  "path": "/money18/:id?"
}
```
