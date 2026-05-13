# 南方都市报 - 南都客户端（按记者）

## Coverage
`index-only`

## Route
- Namespace: `oeeee`
- Namespace Name: `南方都市报`
- Route Path: `/app/reporter/:id`
- Route Name: `南都客户端（按记者）`
- Example: `/oeeee/app/reporter/249`
- URL: `oeeee.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `TimWu007`
- Source Location: `app/reporter.ts`
- Source Module: `() => import('@/routes/oeeee/app/reporter.ts')`

## Description
记者的 UID 可通过 `m.mp.oeeee.com` 下的文章页面获取。点击文章下方的作者头像，进入该作者的个人主页，即可从 url 中获取。

## Parameters
- `id`: 记者 UID


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
  "description": "记者的 UID 可通过 `m.mp.oeeee.com` 下的文章页面获取。点击文章下方的作者头像，进入该作者的个人主页，即可从 url 中获取。",
  "example": "/oeeee/app/reporter/249",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "app/reporter.ts",
  "maintainers": [
    "TimWu007"
  ],
  "module": "() => import('@/routes/oeeee/app/reporter.ts')",
  "name": "南都客户端（按记者）",
  "parameters": {
    "id": "记者 UID"
  },
  "path": "/app/reporter/:id"
}
```
