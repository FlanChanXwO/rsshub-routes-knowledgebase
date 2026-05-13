# VCB-Studio - 分类文章

## Coverage
`index-only`

## Route
- Namespace: `vcb-s`
- Namespace Name: `VCB-Studio`
- Route Path: `/category/:cate`
- Route Name: `分类文章`
- Example: `/vcb-s/category/works`
- URL: `vcb-s.com/`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `cxfksword`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/vcb-s/category.ts')`

## Description
| 作品项目 | 科普系列 | 计划与日志 |
| -------- | -------- | ---------- |
| works    | kb       | planlog    |

## Parameters
- `cate`: 分类


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
  - `vcb-s.com/archives/category/:cate`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "| 作品项目 | 科普系列 | 计划与日志 |\n| -------- | -------- | ---------- |\n| works    | kb       | planlog    |",
  "example": "/vcb-s/category/works",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "category.ts",
  "maintainers": [
    "cxfksword"
  ],
  "module": "() => import('@/routes/vcb-s/category.ts')",
  "name": "分类文章",
  "parameters": {
    "cate": "分类"
  },
  "path": "/category/:cate",
  "radar": [
    {
      "source": [
        "vcb-s.com/archives/category/:cate"
      ]
    }
  ],
  "url": "vcb-s.com/"
}
```
