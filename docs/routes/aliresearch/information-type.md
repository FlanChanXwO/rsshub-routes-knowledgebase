# 阿里研究院 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `aliresearch`
- Namespace Name: `阿里研究院`
- Route Path: `/information/:type?`
- Route Name: `资讯`
- Example: `/aliresearch/information`
- URL: `aliresearch.com/cn/information`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `information.ts`
- Source Module: `() => import('@/routes/aliresearch/information.ts')`

## Description
| 新闻 | 观点 | 案例 |
| ---- | ---- | ---- |

## Parameters
- `type`: 类型，见下表，默认为新闻


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
  - `aliresearch.com/cn/information`
  - `aliresearch.com/`
- `target`: `/information`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 新闻 | 观点 | 案例 |\n| ---- | ---- | ---- |",
  "example": "/aliresearch/information",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "information.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/aliresearch/information.ts')",
  "name": "资讯",
  "parameters": {
    "type": "类型，见下表，默认为新闻"
  },
  "path": "/information/:type?",
  "radar": [
    {
      "source": [
        "aliresearch.com/cn/information",
        "aliresearch.com/"
      ],
      "target": "/information"
    }
  ],
  "url": "aliresearch.com/cn/information"
}
```
