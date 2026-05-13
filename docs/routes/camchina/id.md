# 中国管理现代化研究会 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `camchina`
- Namespace Name: `中国管理现代化研究会`
- Route Path: `/:id?`
- Route Name: `栏目`
- Example: `/camchina`
- URL: `cste.org.cn`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/camchina/index.ts')`

## Description
| 新闻 | 通告栏 |
| ---- | ------ |
| 1    | 2      |

## Parameters
- `id`: 分类，见下表，默认为 1，即新闻


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
  - `cste.org.cn/categories/:id`
  - `cste.org.cn/`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| 新闻 | 通告栏 |\n| ---- | ------ |\n| 1    | 2      |",
  "example": "/camchina",
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
  "module": "() => import('@/routes/camchina/index.ts')",
  "name": "栏目",
  "parameters": {
    "id": "分类，见下表，默认为 1，即新闻"
  },
  "path": "/:id?",
  "radar": [
    {
      "source": [
        "cste.org.cn/categories/:id",
        "cste.org.cn/"
      ]
    }
  ]
}
```
