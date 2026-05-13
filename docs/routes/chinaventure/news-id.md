# 投中网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `chinaventure`
- Namespace Name: `投中网`
- Route Path: `/news/:id?`
- Route Name: `分类`
- Example: `/chinaventure/news/78`
- URL: `chinaventure.com.cn/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `yuxinliu-alex`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/chinaventure/index.ts')`

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
  "location": "index.ts",
  "maintainers": [
    "yuxinliu-alex"
  ],
  "module": "() => import('@/routes/chinaventure/index.ts')",
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
  "url": "chinaventure.com.cn/"
}
```
