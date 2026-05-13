# 微信小程序 - 公众号（搜狗来源）

## Coverage
`index-only`

## Route
- Namespace: `wechat`
- Namespace Name: `微信小程序`
- Route Path: `/sogou/:id`
- Route Name: `公众号（搜狗来源）`
- Example: `/wechat/sogou/qimao0908`
- URL: `posts.careerengine.us`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `EthanWng97, pseudoyu`
- Source Location: `sogou.ts`
- Source Module: `() => import('@/routes/wechat/sogou.ts')`

## Description
_None_

## Parameters
- `id`: 公众号 id, 打开 weixin.sogou.com 并搜索相应公众号， 在 URL 中找到 id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/wechat/sogou/qimao0908",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "sogou.ts",
  "maintainers": [
    "EthanWng97",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/wechat/sogou.ts')",
  "name": "公众号（搜狗来源）",
  "parameters": {
    "id": "公众号 id, 打开 weixin.sogou.com 并搜索相应公众号， 在 URL 中找到 id"
  },
  "path": "/sogou/:id"
}
```
