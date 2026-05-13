# 爱范儿 - 分类

## Coverage
`index-only`

## Route
- Namespace: `ifanr`
- Namespace Name: `爱范儿`
- Route Path: `/category/:name`
- Route Name: `分类`
- Example: `/ifanr/category/早报`
- URL: `www.ifanr.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `donghongfei`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/ifanr/category.ts')`

## Description
支持分类：早报、评测、糖纸众测、产品

## Parameters
- `name`: {"description": "分类名称", "options": [{"label": "早报", "value": "早报"}, {"label": "评测", "value": "评测"}, {"label": "糖纸众测", "value": "糖纸众测"}, {"label": "产品", "value": "产品"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.ifanr.com/category/:name`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "支持分类：早报、评测、糖纸众测、产品",
  "example": "/ifanr/category/早报",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "category.ts",
  "maintainers": [
    "donghongfei"
  ],
  "module": "() => import('@/routes/ifanr/category.ts')",
  "name": "分类",
  "parameters": {
    "name": {
      "description": "分类名称",
      "options": [
        {
          "label": "早报",
          "value": "早报"
        },
        {
          "label": "评测",
          "value": "评测"
        },
        {
          "label": "糖纸众测",
          "value": "糖纸众测"
        },
        {
          "label": "产品",
          "value": "产品"
        }
      ]
    }
  },
  "path": "/category/:name",
  "radar": [
    {
      "source": [
        "www.ifanr.com/category/:name"
      ]
    }
  ]
}
```
