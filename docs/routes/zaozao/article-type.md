# 前端早早聊 - 文章

## Coverage
`index-only`

## Route
- Namespace: `zaozao`
- Namespace Name: `前端早早聊`
- Route Path: `/article/:type?`
- Route Name: `文章`
- Example: `/zaozao/article/quality`
- URL: `www.zaozao.run`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `shaomingbo`
- Source Location: `article.ts`
- Source Module: `() => import('@/routes/zaozao/article.ts')`

## Description
| 精品推荐  | 技术干货 | 职场成长 | 社区动态  | 组件物料 | 行业动态 |
| --------- | -------- | -------- | --------- | -------- | -------- |
| recommend | quality  | growth   | community | material | industry |

## Parameters
- `type`: 文章分类


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
  - `www.zaozao.run/article/:type`
- `target`: `/article/:type`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| 精品推荐  | 技术干货 | 职场成长 | 社区动态  | 组件物料 | 行业动态 |\n| --------- | -------- | -------- | --------- | -------- | -------- |\n| recommend | quality  | growth   | community | material | industry |",
  "example": "/zaozao/article/quality",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "article.ts",
  "maintainers": [
    "shaomingbo"
  ],
  "module": "() => import('@/routes/zaozao/article.ts')",
  "name": "文章",
  "parameters": {
    "type": "文章分类"
  },
  "path": "/article/:type?",
  "radar": [
    {
      "source": [
        "www.zaozao.run/article/:type"
      ],
      "target": "/article/:type"
    }
  ]
}
```
