# 深圳市罗湖区人民政府 - 惠州市人民政府

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `深圳市罗湖区人民政府`
- Route Path: `/gov/huizhou/zwgk/:category?`
- Route Name: `惠州市人民政府`
- Example: `/gov/huizhou/zwgk/jgdt`
- URL: `www.szlh.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `huizhou/zwgk/index.ts`
- Source Module: `_None_`

## Description
#### 政务公开 {#guang-dong-sheng-ren-min-zheng-fu-hui-zhou-shi-ren-min-zheng-fu-zheng-wu-gong-kai}

## Parameters
- `category`: 资讯类别，可以从网址中得到，默认为政务要闻


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
    "government"
  ],
  "description": "#### 政务公开 {#guang-dong-sheng-ren-min-zheng-fu-hui-zhou-shi-ren-min-zheng-fu-zheng-wu-gong-kai}",
  "example": "/gov/huizhou/zwgk/jgdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "huizhou/zwgk/index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "惠州市人民政府",
  "parameters": {
    "category": "资讯类别，可以从网址中得到，默认为政务要闻"
  },
  "path": "/huizhou/zwgk/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
