# 微信小程序 - 公众号（Wechat2RSS 来源）

## Coverage
`index-only`

## Route
- Namespace: `wechat`
- Namespace Name: `微信小程序`
- Route Path: `/wechat2rss/:id`
- Route Name: `公众号（Wechat2RSS 来源）`
- Example: `/wechat/wechat2rss/5b925323244e9737c39285596c53e3a2f4a30774`
- URL: `posts.careerengine.us`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `wechat2rss.ts`
- Source Module: `() => import('@/routes/wechat/wechat2rss.ts')`

## Description
_None_

## Parameters
- `id`: 公众号 id，打开 `https://wechat2rss.xlab.app/posts/list/`，在 URL 中找到 id；注意不是公众号页的 id，而是订阅的 id


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
    "new-media"
  ],
  "example": "/wechat/wechat2rss/5b925323244e9737c39285596c53e3a2f4a30774",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "wechat2rss.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/wechat/wechat2rss.ts')",
  "name": "公众号（Wechat2RSS 来源）",
  "parameters": {
    "id": "公众号 id，打开 `https://wechat2rss.xlab.app/posts/list/`，在 URL 中找到 id；注意不是公众号页的 id，而是订阅的 id"
  },
  "path": "/wechat2rss/:id"
}
```
