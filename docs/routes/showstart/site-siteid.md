# 秀动网 - 按场地 - 演出更新

## Coverage
`index-only`

## Route
- Namespace: `showstart`
- Namespace Name: `秀动网`
- Route Path: `/site/:siteId`
- Route Name: `按场地 - 演出更新`
- Example: `/showstart/site/3583`
- URL: `www.showstart.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `lchtao26`
- Source Location: `site.ts`
- Source Module: `() => import('@/routes/showstart/site.ts')`

## Description
::: tip
-   演出场地 ID 查询: `/showstart/search/site/:keyword`, 如: [https://rsshub.app/showstart/search/site/酒球会](https://rsshub.app/showstart/search/site/酒球会)
:::

## Parameters
- `siteId`: 演出场地 (编号)


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
  - `www.showstart.com/venue/:id`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "::: tip\n-   演出场地 ID 查询: `/showstart/search/site/:keyword`, 如: [https://rsshub.app/showstart/search/site/酒球会](https://rsshub.app/showstart/search/site/酒球会)\n:::",
  "example": "/showstart/site/3583",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "site.ts",
  "maintainers": [
    "lchtao26"
  ],
  "module": "() => import('@/routes/showstart/site.ts')",
  "name": "按场地 - 演出更新",
  "parameters": {
    "siteId": "演出场地 (编号)"
  },
  "path": "/site/:siteId",
  "radar": [
    {
      "source": [
        "www.showstart.com/venue/:id"
      ]
    }
  ]
}
```
