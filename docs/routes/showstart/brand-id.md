# 秀动网 - 按厂牌 - 演出更新

## Coverage
`index-only`

## Route
- Namespace: `showstart`
- Namespace Name: `秀动网`
- Route Path: `/brand/:id`
- Route Name: `按厂牌 - 演出更新`
- Example: `/showstart/brand/34707`
- URL: `www.showstart.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `lchtao26`
- Source Location: `brand.ts`
- Source Module: `() => import('@/routes/showstart/brand.ts')`

## Description
::: tip
厂牌 ID 查询: `/showstart/search/brand/:keyword`，如: [https://rsshub.app/showstart/search/brand/声场](https://rsshub.app/showstart/search/brand/声场)
:::

## Parameters
- `id`: 厂牌 ID


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
  - `www.showstart.com/host/:id`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "::: tip\n厂牌 ID 查询: `/showstart/search/brand/:keyword`，如: [https://rsshub.app/showstart/search/brand/声场](https://rsshub.app/showstart/search/brand/声场)\n:::",
  "example": "/showstart/brand/34707",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "brand.ts",
  "maintainers": [
    "lchtao26"
  ],
  "module": "() => import('@/routes/showstart/brand.ts')",
  "name": "按厂牌 - 演出更新",
  "parameters": {
    "id": "厂牌 ID"
  },
  "path": "/brand/:id",
  "radar": [
    {
      "source": [
        "www.showstart.com/host/:id"
      ]
    }
  ]
}
```
