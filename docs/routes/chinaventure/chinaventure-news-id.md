# 投中网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `chinaventure`
- Namespace Name: `投中网`
- Route Path: `/chinaventure/news/:id?`
- Route Name: `分类`
- Example: `/chinaventure/news/78`
- URL: `chinaventure.com.cn/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `yuxinliu-alex`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 推荐 | 商业深度 | 资本市场 | 5G | 健康 | 教育 | 地产 | 金融 | 硬科技 | 新消费 |
| ---- | -------- | -------- | -- | ---- | ---- | ---- | ---- | ------ | ------ |
|      | 78       | 80       | 83 | 111  | 110  | 112  | 113  | 114    | 116    |

## Parameters
- `id`: 分类，见下表，默认为推荐


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
  - `chinaventure.com.cn/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 推荐 | 商业深度 | 资本市场 | 5G | 健康 | 教育 | 地产 | 金融 | 硬科技 | 新消费 |\n| ---- | -------- | -------- | -- | ---- | ---- | ---- | ---- | ------ | ------ |\n|      | 78       | 80       | 83 | 111  | 110  | 112  | 113  | 114    | 116    |",
  "example": "/chinaventure/news/78",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 53,
  "location": "index.ts",
  "maintainers": [
    "yuxinliu-alex"
  ],
  "name": "分类",
  "parameters": {
    "id": "分类，见下表，默认为推荐"
  },
  "path": "/news/:id?",
  "radar": [
    {
      "source": [
        "chinaventure.com.cn/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "投中网是国内领先的创新经济信息服务平台，拥有立体化媒体矩阵，十多年行业深耕，为创新经济领域核心人群提供深入、独到的智识和洞见，在私募股权投资行业和创新商业领域均拥有权威影响力。 - Powered by RSSHub",
      "errorAt": "2025-06-10T20:06:40.932Z",
      "errorMessage": "Unexpected type of selector\n",
      "id": "61948380852672523",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.chinaventure.com.cn/news/78.html",
      "title": "商业深度-投中网",
      "type": "feed",
      "url": "rsshub://chinaventure/news/78"
    },
    {
      "description": "投中网是国内领先的创新经济信息服务平台，拥有立体化媒体矩阵，十多年行业深耕，为创新经济领域核心人群提供深入、独到的智识和洞见，在私募股权投资行业和创新商业领域均拥有权威影响力。 - Powered by RSSHub",
      "errorAt": "2025-05-03T23:46:31.901Z",
      "errorMessage": "Unexpected type of selector\n",
      "id": "73956968061162496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.chinaventure.com.cn/index.html",
      "title": "推荐-投中网",
      "type": "feed",
      "url": "rsshub://chinaventure/news"
    }
  ],
  "url": "chinaventure.com.cn/"
}
```
