# TOPYS - 关键字

## Coverage
`index-only`

## Route
- Namespace: `topys`
- Namespace Name: `TOPYS`
- Route Path: `/:keyword?`
- Route Name: `关键字`
- Example: `/topys`
- URL: `topys.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/topys/index.ts')`

## Description
| 创意 | 设计 | 商业 | 艺术 | 文化 | 科技 |
| ---- | ---- | ---- | ---- | ---- | ---- |

## Parameters
- `keyword`: 关键字，可在对应结果页的 URL 中找到


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
  - `topys.cn/search/:keyword`
  - `topys.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 创意 | 设计 | 商业 | 艺术 | 文化 | 科技 |\n| ---- | ---- | ---- | ---- | ---- | ---- |",
  "example": "/topys",
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
  "module": "() => import('@/routes/topys/index.ts')",
  "name": "关键字",
  "parameters": {
    "keyword": "关键字，可在对应结果页的 URL 中找到"
  },
  "path": "/:keyword?",
  "radar": [
    {
      "source": [
        "topys.cn/search/:keyword",
        "topys.cn/"
      ]
    }
  ]
}
```
