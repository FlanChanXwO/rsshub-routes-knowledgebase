# 通識・現代中國 - 議題熱話

## Coverage
`index-only`

## Route
- Namespace: `chiculture`
- Namespace Name: `通識・現代中國`
- Route Path: `/topic/:category?`
- Route Name: `議題熱話`
- Example: `/chiculture/topic`
- URL: `chiculture.org.hk`
- Language: `zh-HK`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/chiculture/topic.ts')`

## Description
| 全部 | 現代中國 | 今日香港 | 全球化 | 一周時事通識 |
| ---- | -------- | -------- | ------ | ------------ |
|      | 76       | 479      | 480    | 379          |

## Parameters
- `category`: 分类，见下表，默认为全部


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
  "description": "| 全部 | 現代中國 | 今日香港 | 全球化 | 一周時事通識 |\n| ---- | -------- | -------- | ------ | ------------ |\n|      | 76       | 479      | 480    | 379          |",
  "example": "/chiculture/topic",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topic.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/chiculture/topic.ts')",
  "name": "議題熱話",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/topic/:category?"
}
```
