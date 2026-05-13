# 大麦网 - 票务更新

## Coverage
`index-only`

## Route
- Namespace: `damai`
- Namespace Name: `大麦网`
- Route Path: `/activity/:city/:category/:subcategory/:keyword?`
- Route Name: `票务更新`
- Example: `/damai/activity/上海/音乐会/全部/柴可夫斯基`
- URL: `search.damai.cn`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `hoilc, Konano`
- Source Location: `activity.tsx`
- Source Module: `() => import('@/routes/damai/activity.tsx')`

## Description
城市、分类名、子分类名，请参见[大麦网搜索页面](https://search.damai.cn/search.htm)

## Parameters
- `city`: 城市，如果不需要限制，请填入`全部`
- `category`: 分类，如果不需要限制，请填入`全部`
- `subcategory`: 子分类，如果不需要限制，请填入`全部`
- `keyword`: 搜索关键字，置空为不限制


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
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
  "description": "城市、分类名、子分类名，请参见[大麦网搜索页面](https://search.damai.cn/search.htm)",
  "example": "/damai/activity/上海/音乐会/全部/柴可夫斯基",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "activity.tsx",
  "maintainers": [
    "hoilc",
    "Konano"
  ],
  "module": "() => import('@/routes/damai/activity.tsx')",
  "name": "票务更新",
  "parameters": {
    "category": "分类，如果不需要限制，请填入`全部`",
    "city": "城市，如果不需要限制，请填入`全部`",
    "keyword": "搜索关键字，置空为不限制",
    "subcategory": "子分类，如果不需要限制，请填入`全部`"
  },
  "path": "/activity/:city/:category/:subcategory/:keyword?"
}
```
