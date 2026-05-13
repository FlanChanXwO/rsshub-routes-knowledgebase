# 爱奇艺 - 剧集

## Coverage
`index-only`

## Route
- Namespace: `iqiyi`
- Namespace Name: `爱奇艺`
- Route Path: `/album/:id`
- Route Name: `剧集`
- Example: `/iqiyi/album/神武天尊-2020-1b4lufwxd7h`
- URL: `iq.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `album.tsx`
- Source Module: `() => import('@/routes/iqiyi/album.tsx')`

## Description
::: tip
  可抓取內容根据服务器所在地区而定
:::

## Parameters
- `id`: 剧集 id, 可在该主页 URL 中找到


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
    "multimedia"
  ],
  "description": "::: tip\n  可抓取內容根据服务器所在地区而定\n:::",
  "example": "/iqiyi/album/神武天尊-2020-1b4lufwxd7h",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "album.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/iqiyi/album.tsx')",
  "name": "剧集",
  "parameters": {
    "id": "剧集 id, 可在该主页 URL 中找到"
  },
  "path": "/album/:id"
}
```
