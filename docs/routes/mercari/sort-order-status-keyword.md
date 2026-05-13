# Mercari - 关键词

## Coverage
`index-only`

## Route
- Namespace: `mercari`
- Namespace Name: `Mercari`
- Route Path: `/:sort/:order/:status/:keyword`
- Route Name: `关键词`
- Example: `/mercari/create_time/desc/default/ふもふも`
- URL: `jp.mercari.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `yana9i`
- Source Location: `keyword.ts`
- Source Module: `() => import('@/routes/mercari/keyword.ts')`

## Description
_None_

## Parameters
- `sort`: {"default": "default", "description": "排序方式", "options": [{"label": "默认排序", "value": "default"}, {"label": "发布时间", "value": "create_time"}, {"label": "评分", "value": "score"}, {"label": "点赞", "value": "like"}, {"label": "价格", "value": "price"}]}
- `order`: {"default": "desc", "description": "排序顺序", "options": [{"label": "降序", "value": "desc"}, {"label": "升序", "value": "asc"}]}
- `status`: {"default": "default", "description": "商品状态", "options": [{"label": "全部", "value": "default"}, {"label": "在售", "value": "onsale"}, {"label": "已售", "value": "soldout"}]}
- `keyword`: {"description": "关键词"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/mercari/create_time/desc/default/ふもふも",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "keyword.ts",
  "maintainers": [
    "yana9i"
  ],
  "module": "() => import('@/routes/mercari/keyword.ts')",
  "name": "关键词",
  "parameters": {
    "keyword": {
      "description": "关键词"
    },
    "order": {
      "default": "desc",
      "description": "排序顺序",
      "options": [
        {
          "label": "降序",
          "value": "desc"
        },
        {
          "label": "升序",
          "value": "asc"
        }
      ]
    },
    "sort": {
      "default": "default",
      "description": "排序方式",
      "options": [
        {
          "label": "默认排序",
          "value": "default"
        },
        {
          "label": "发布时间",
          "value": "create_time"
        },
        {
          "label": "评分",
          "value": "score"
        },
        {
          "label": "点赞",
          "value": "like"
        },
        {
          "label": "价格",
          "value": "price"
        }
      ]
    },
    "status": {
      "default": "default",
      "description": "商品状态",
      "options": [
        {
          "label": "全部",
          "value": "default"
        },
        {
          "label": "在售",
          "value": "onsale"
        },
        {
          "label": "已售",
          "value": "soldout"
        }
      ]
    }
  },
  "path": "/:sort/:order/:status/:keyword",
  "url": "jp.mercari.com"
}
```
