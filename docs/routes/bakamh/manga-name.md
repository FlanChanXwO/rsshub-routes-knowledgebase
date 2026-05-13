# 巴卡漫画 - 漫画更新

## Coverage
`index-only`

## Route
- Namespace: `bakamh`
- Namespace Name: `巴卡漫画`
- Route Path: `/manga/:name`
- Route Name: `漫画更新`
- Example: `/bakamh/manga/最强家丁`
- URL: `bakamh.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `yoyobase`
- Source Location: `manga.ts`
- Source Module: `() => import('@/routes/bakamh/manga.ts')`

## Description
_None_

## Parameters
- `name`: 漫画名称，漫画主页的地址栏中


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `bakamh.com/manga/:name/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bakamh/manga/最强家丁",
  "location": "manga.ts",
  "maintainers": [
    "yoyobase"
  ],
  "module": "() => import('@/routes/bakamh/manga.ts')",
  "name": "漫画更新",
  "parameters": {
    "name": "漫画名称，漫画主页的地址栏中"
  },
  "path": "/manga/:name",
  "radar": [
    {
      "source": [
        "bakamh.com/manga/:name/"
      ]
    }
  ],
  "url": "bakamh.com"
}
```
