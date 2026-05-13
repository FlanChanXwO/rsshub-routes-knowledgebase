# 雨苁博客 - 分类

## Coverage
`index-only`

## Route
- Namespace: `ddosi`
- Namespace Name: `雨苁博客`
- Route Path: `/category/:category?`
- Route Name: `分类`
- Example: `/ddosi/category/黑客工具`
- URL: `ddosi.org/`
- Language: `zh-CN`
- Categories: `blog`
- Maintainers: `XinRoom`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/ddosi/category.ts')`

## Description
_None_

## Parameters
- `category`: N


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
  - `ddosi.org/category/:category/`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/ddosi/category/黑客工具",
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
    "XinRoom"
  ],
  "module": "() => import('@/routes/ddosi/category.ts')",
  "name": "分类",
  "parameters": {
    "category": "N"
  },
  "path": "/category/:category?",
  "radar": [
    {
      "source": [
        "ddosi.org/category/:category/"
      ],
      "target": "/category/:category"
    }
  ],
  "url": "ddosi.org/"
}
```
