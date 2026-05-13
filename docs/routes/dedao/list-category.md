# 得到 - 首页

## Coverage
`index-only`

## Route
- Namespace: `dedao`
- Namespace Name: `得到`
- Route Path: `/list/:category?`
- Route Name: `首页`
- Example: `/dedao/list/年度日更`
- URL: `igetget.com/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `list.ts`
- Source Module: `() => import('@/routes/dedao/list.ts')`

## Description
_None_

## Parameters
- `category`: 分类名，默认为年度日更


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
  - `igetget.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/dedao/list/年度日更",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "list.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/dedao/list.ts')",
  "name": "首页",
  "parameters": {
    "category": "分类名，默认为年度日更"
  },
  "path": "/list/:category?",
  "radar": [
    {
      "source": [
        "igetget.com/"
      ]
    }
  ],
  "url": "igetget.com/"
}
```
