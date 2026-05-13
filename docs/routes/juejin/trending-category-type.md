# 掘金 - 热门

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/trending/:category/:type`
- Route Name: `热门`
- Example: `/juejin/trending/ios/monthly`
- URL: `juejin.cn`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `moaix`
- Source Location: `trending.ts`
- Source Module: `() => import('@/routes/juejin/trending.ts')`

## Description
_None_

## Parameters
- `category`: {"default": "all", "description": "分类名", "options": [{"label": "Android", "value": "android"}, {"label": "前端", "value": "frontend"}, {"label": "iOS", "value": "ios"}, {"label": "后端", "value": "backend"}, {"label": "设计", "value": "design"}, {"label": "产品", "value": "product"}, {"label": "工具资源", "value": "freebie"}, {"label": "阅读", "value": "article"}, {"label": "人工智能", "value": "ai"}, {"label": "运维", "value": "devops"}, {"label": "全部", "value": "all"}]}
- `type`: {"default": "weekly", "description": "类型", "options": [{"label": "本周最热", "value": "weekly"}, {"label": "本月最热", "value": "monthly"}, {"label": "历史最热", "value": "historical"}]}


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
    "programming"
  ],
  "example": "/juejin/trending/ios/monthly",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "trending.ts",
  "maintainers": [
    "moaix"
  ],
  "module": "() => import('@/routes/juejin/trending.ts')",
  "name": "热门",
  "parameters": {
    "category": {
      "default": "all",
      "description": "分类名",
      "options": [
        {
          "label": "Android",
          "value": "android"
        },
        {
          "label": "前端",
          "value": "frontend"
        },
        {
          "label": "iOS",
          "value": "ios"
        },
        {
          "label": "后端",
          "value": "backend"
        },
        {
          "label": "设计",
          "value": "design"
        },
        {
          "label": "产品",
          "value": "product"
        },
        {
          "label": "工具资源",
          "value": "freebie"
        },
        {
          "label": "阅读",
          "value": "article"
        },
        {
          "label": "人工智能",
          "value": "ai"
        },
        {
          "label": "运维",
          "value": "devops"
        },
        {
          "label": "全部",
          "value": "all"
        }
      ]
    },
    "type": {
      "default": "weekly",
      "description": "类型",
      "options": [
        {
          "label": "本周最热",
          "value": "weekly"
        },
        {
          "label": "本月最热",
          "value": "monthly"
        },
        {
          "label": "历史最热",
          "value": "historical"
        }
      ]
    }
  },
  "path": "/trending/:category/:type"
}
```
