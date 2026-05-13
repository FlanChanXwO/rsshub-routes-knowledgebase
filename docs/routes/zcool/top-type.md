# 站酷 - 作品总榜单

## Coverage
`index-only`

## Route
- Namespace: `zcool`
- Namespace Name: `站酷`
- Route Path: `/top/:type`
- Route Name: `作品总榜单`
- Example: `/zcool/top/design`
- URL: `www.zcool.com.cn`
- Language: `zh-CN`
- Categories: `design`
- Maintainers: `yuuow`
- Source Location: `top.ts`
- Source Module: `() => import('@/routes/zcool/top.ts')`

## Description
_None_

## Parameters
- `type`: {"description": "推荐类型", "options": [{"label": "作品榜单", "value": "design"}, {"label": "文章榜单", "value": "article"}]}


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
    "design"
  ],
  "example": "/zcool/top/design",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "top.ts",
  "maintainers": [
    "yuuow"
  ],
  "module": "() => import('@/routes/zcool/top.ts')",
  "name": "作品总榜单",
  "parameters": {
    "type": {
      "description": "推荐类型",
      "options": [
        {
          "label": "作品榜单",
          "value": "design"
        },
        {
          "label": "文章榜单",
          "value": "article"
        }
      ]
    }
  },
  "path": "/top/:type",
  "view": 2
}
```
