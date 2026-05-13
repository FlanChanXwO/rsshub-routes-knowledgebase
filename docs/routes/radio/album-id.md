# 云听 - 专辑

## Coverage
`index-only`

## Route
- Namespace: `radio`
- Namespace Name: `云听`
- Route Path: `/album/:id`
- Route Name: `专辑`
- Example: `/radio/album/15682090498666`
- URL: `radio.cn`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `album.ts`
- Source Module: `() => import('@/routes/radio/album.ts')`

## Description
如果订阅 [中国相声榜](https://www.radio.cn/pc-portal/sanji/detail.html?columnId=15682090498666)，其 URL 为 `https://www.radio.cn/pc-portal/sanji/detail.html?columnId=15682090498666`，可以得到 `columnId` 为 `15682090498666`

  所以对应路由为 [`/radio/album/15682090498666`](https://rsshub.app/radio/album/15682090498666)

::: tip
  部分专辑不适用该路由，此时可以尝试 [节目](#yun-ting-jie-mu) 路由
:::

## Parameters
- `id`: 专辑 id，可在对应专辑页面的 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "如果订阅 [中国相声榜](https://www.radio.cn/pc-portal/sanji/detail.html?columnId=15682090498666)，其 URL 为 `https://www.radio.cn/pc-portal/sanji/detail.html?columnId=15682090498666`，可以得到 `columnId` 为 `15682090498666`\n\n  所以对应路由为 [`/radio/album/15682090498666`](https://rsshub.app/radio/album/15682090498666)\n\n::: tip\n  部分专辑不适用该路由，此时可以尝试 [节目](#yun-ting-jie-mu) 路由\n:::",
  "example": "/radio/album/15682090498666",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "album.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/radio/album.ts')",
  "name": "专辑",
  "parameters": {
    "id": "专辑 id，可在对应专辑页面的 URL 中找到"
  },
  "path": "/album/:id"
}
```
