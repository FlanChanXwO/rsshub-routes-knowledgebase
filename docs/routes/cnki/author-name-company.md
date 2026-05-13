# 中国知网 - 作者

## Coverage
`index-only`

## Route
- Namespace: `cnki`
- Namespace Name: `中国知网`
- Route Path: `/author/:name/:company`
- Route Name: `作者`
- Example: `/cnki/author/丁晓东/中国人民大学`
- URL: `navi.cnki.net`
- Language: `zh-CN`
- Categories: `journal`
- Maintainers: `Derekmini, harveyqiu`
- Source Location: `author.ts`
- Source Module: `() => import('@/routes/cnki/author.ts')`

## Description
::: tip
    可能仅限中国大陆服务器访问，以实际情况为准。
:::

## Parameters
- `name`: 作者姓名
- `company`: 作者单位


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
    "journal"
  ],
  "description": "::: tip\n    可能仅限中国大陆服务器访问，以实际情况为准。\n:::",
  "example": "/cnki/author/丁晓东/中国人民大学",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "author.ts",
  "maintainers": [
    "Derekmini",
    "harveyqiu"
  ],
  "module": "() => import('@/routes/cnki/author.ts')",
  "name": "作者",
  "parameters": {
    "company": "作者单位",
    "name": "作者姓名"
  },
  "path": "/author/:name/:company"
}
```
