# PLAYNO.1 玩樂達人 - AV

## Coverage
`index-only`

## Route
- Namespace: `playno1`
- Namespace Name: `PLAYNO.1 玩樂達人`
- Route Path: `/av/:catid?`
- Route Name: `AV`
- Example: `/playno1/av`
- URL: `stno1.playno1.com`
- Language: `zh-TW`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `av.ts`
- Source Module: `() => import('@/routes/playno1/av.ts')`

## Description
::: warning
目前观测到该博客可能禁止日本 IP 访问。建议部署在日本区以外的服务器上。
:::

| 全部文章 | AV 新聞 | AV 導覽 |
| -------- | ------- | ------- |
| 78       | 3       | 5       |

## Parameters
- `catid`: 分类，见下表，默认为全部文章


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: warning\n目前观测到该博客可能禁止日本 IP 访问。建议部署在日本区以外的服务器上。\n:::\n\n| 全部文章 | AV 新聞 | AV 導覽 |\n| -------- | ------- | ------- |\n| 78       | 3       | 5       |",
  "example": "/playno1/av",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "av.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/playno1/av.ts')",
  "name": "AV",
  "parameters": {
    "catid": "分类，见下表，默认为全部文章"
  },
  "path": "/av/:catid?"
}
```
