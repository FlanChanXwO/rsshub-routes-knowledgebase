# 纵横中文网 - 章节更新

## Coverage
`index-only`

## Route
- Namespace: `zongheng`
- Namespace Name: `纵横中文网`
- Route Path: `/detail/:id`
- Route Name: `章节更新`
- Example: `/zongheng/detail/1366535`
- URL: `www.zongheng.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `TonyRL`
- Source Location: `detail.ts`
- Source Module: `() => import('@/routes/zongheng/detail.ts')`

## Description
_None_

## Parameters
- `id`: 作品 ID


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
  - `www.zongheng.org/detail/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/zongheng/detail/1366535",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "detail.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/zongheng/detail.ts')",
  "name": "章节更新",
  "parameters": {
    "id": "作品 ID"
  },
  "path": "/detail/:id",
  "radar": [
    {
      "source": [
        "www.zongheng.org/detail/:id"
      ]
    }
  ],
  "url": "www.zongheng.com"
}
```
