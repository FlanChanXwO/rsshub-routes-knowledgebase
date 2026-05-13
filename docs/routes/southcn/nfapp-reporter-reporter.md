# 南方网 - 南方 +（按作者）

## Coverage
`index-only`

## Route
- Namespace: `southcn`
- Namespace Name: `南方网`
- Route Path: `/nfapp/reporter/:reporter`
- Route Name: `南方 +（按作者）`
- Example: `/southcn/nfapp/reporter/969927791`
- URL: `nfapp.southcn.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `TimWu007`
- Source Location: `nfapp/reporter.ts`
- Source Module: `() => import('@/routes/southcn/nfapp/reporter.ts')`

## Description
作者的 UUID 只可通过 `static.nfapp.southcn.com` 下的文章页面获取。点击文章下方的作者介绍，进入该作者的个人主页，即可从 url 中获取。

## Parameters
- `reporter`: 作者 UUID


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
    "traditional-media"
  ],
  "description": "作者的 UUID 只可通过 `static.nfapp.southcn.com` 下的文章页面获取。点击文章下方的作者介绍，进入该作者的个人主页，即可从 url 中获取。",
  "example": "/southcn/nfapp/reporter/969927791",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "nfapp/reporter.ts",
  "maintainers": [
    "TimWu007"
  ],
  "module": "() => import('@/routes/southcn/nfapp/reporter.ts')",
  "name": "南方 +（按作者）",
  "parameters": {
    "reporter": "作者 UUID"
  },
  "path": "/nfapp/reporter/:reporter"
}
```
