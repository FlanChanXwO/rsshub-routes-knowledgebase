# 36kr - 资讯热榜

## Coverage
`index-only`

## Route
- Namespace: `36kr`
- Namespace Name: `36kr`
- Route Path: `/hot-list/:category?`
- Route Name: `资讯热榜`
- Example: `/36kr/hot-list`
- URL: `36kr.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `hot-list.ts`
- Source Module: `() => import('@/routes/36kr/hot-list.ts')`

## Description
| 24 小时热榜 | 资讯人气榜 | 资讯综合榜 | 资讯收藏榜 |
| ----------- | ---------- | ---------- | ---------- |
| 24          | renqi      | zonghe     | shoucang   |

## Parameters
- `category`: 分类，默认为24小时热榜


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
  - `36kr.com/hot-list/:category`
  - `36kr.com/`
- `target`: `/hot-list/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 24 小时热榜 | 资讯人气榜 | 资讯综合榜 | 资讯收藏榜 |\n| ----------- | ---------- | ---------- | ---------- |\n| 24          | renqi      | zonghe     | shoucang   |",
  "example": "/36kr/hot-list",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "hot-list.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/36kr/hot-list.ts')",
  "name": "资讯热榜",
  "parameters": {
    "category": "分类，默认为24小时热榜"
  },
  "path": "/hot-list/:category?",
  "radar": [
    {
      "source": [
        "36kr.com/hot-list/:category",
        "36kr.com/"
      ],
      "target": "/hot-list/:category"
    }
  ]
}
```
