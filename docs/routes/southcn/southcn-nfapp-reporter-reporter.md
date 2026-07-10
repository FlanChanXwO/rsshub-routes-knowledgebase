# 南方网 - 南方 +（按作者）

## Coverage
`index-only`

## Route
- Namespace: `southcn`
- Namespace Name: `南方网`
- Route Path: `/southcn/nfapp/reporter/:reporter`
- Route Name: `南方 +（按作者）`
- Example: `/southcn/nfapp/reporter/969927791`
- URL: `nfapp.southcn.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TimWu007`
- Source Location: `nfapp/reporter.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "nfapp/reporter.ts",
  "maintainers": [
    "TimWu007"
  ],
  "name": "南方 +（按作者）",
  "parameters": {
    "reporter": "作者 UUID"
  },
  "path": "/nfapp/reporter/:reporter",
  "topFeeds": []
}
```
