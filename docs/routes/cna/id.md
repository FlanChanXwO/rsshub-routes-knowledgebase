# 中央通讯社 - 分类

## Coverage
`index-only`

## Route
- Namespace: `cna`
- Namespace Name: `中央通讯社`
- Route Path: `/:id?`
- Route Name: `分类`
- Example: `/cna/aall`
- URL: `cna.com.tw`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/cna/index.ts')`

## Description
| 聚焦      | 即時 | 政治 | 國際 | 兩岸 | 產經 | 證券 | 科技 | 生活 | 社會 | 地方 | 文化 | 運動 | 娛樂 |
| --------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| headlines | aall | aipl | aopl | acn  | aie  | asc  | ait  | ahel | asoc | aloc | acul | aspt | amov |

## Parameters
- `id`: 分类 id 或新闻专题 id。分类 id 见下表，新闻专题 id 為 https://www.cna.com.tw/list/newstopic.aspx 中，連結的數字部份。此參數默认为 aall


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
  "description": "| 聚焦      | 即時 | 政治 | 國際 | 兩岸 | 產經 | 證券 | 科技 | 生活 | 社會 | 地方 | 文化 | 運動 | 娛樂 |\n| --------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| headlines | aall | aipl | aopl | acn  | aie  | asc  | ait  | ahel | asoc | aloc | acul | aspt | amov |",
  "example": "/cna/aall",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/cna/index.ts')",
  "name": "分类",
  "parameters": {
    "id": "分类 id 或新闻专题 id。分类 id 见下表，新闻专题 id 為 https://www.cna.com.tw/list/newstopic.aspx 中，連結的數字部份。此參數默认为 aall"
  },
  "path": "/:id?"
}
```
