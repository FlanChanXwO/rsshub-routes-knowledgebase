# 秀动网 - 演出搜索

## Coverage
`index-only`

## Route
- Namespace: `showstart`
- Namespace Name: `秀动网`
- Route Path: `/search/:type/:keyword?`
- Route Name: `演出搜索`
- Example: `/showstart/search/live`
- URL: `www.showstart.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `lchtao26`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/showstart/search.ts')`

## Description
_None_

## Parameters
- `keyword`: 搜索关键词
- `type`: {"description": "类别", "options": [{"label": "演出", "value": "event"}, {"label": "音乐人", "value": "artist"}, {"label": "场地", "value": "site"}, {"label": "厂牌", "value": "brand"}, {"label": "城市", "value": "city"}, {"label": "风格", "value": "style"}]}


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
  "example": "/showstart/search/live",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "lchtao26"
  ],
  "module": "() => import('@/routes/showstart/search.ts')",
  "name": "演出搜索",
  "parameters": {
    "keyword": "搜索关键词",
    "type": {
      "description": "类别",
      "options": [
        {
          "label": "演出",
          "value": "event"
        },
        {
          "label": "音乐人",
          "value": "artist"
        },
        {
          "label": "场地",
          "value": "site"
        },
        {
          "label": "厂牌",
          "value": "brand"
        },
        {
          "label": "城市",
          "value": "city"
        },
        {
          "label": "风格",
          "value": "style"
        }
      ]
    }
  },
  "path": "/search/:type/:keyword?"
}
```
