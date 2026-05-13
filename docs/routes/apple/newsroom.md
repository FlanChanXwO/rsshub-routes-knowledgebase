# Apple - Newsroom (中国大陆)

## Coverage
`index-only`

## Route
- Namespace: `apple`
- Namespace Name: `Apple`
- Route Path: `/newsroom`
- Route Name: `Newsroom (中国大陆)`
- Example: `/apple/newsroom`
- URL: `www.apple.com.cn/newsroom`
- Language: `en`
- Categories: `new-media`
- Maintainers: `LinxHex`
- Source Location: `newsroom.ts`
- Source Module: `() => import('@/routes/apple/newsroom.ts')`

## Description
The official source for news about Apple, from Apple. Read press releases, get updates, watch video and download images.

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.apple.com.cn/newsroom`
  - `www.apple.com.cn/newsroom/:year/:month/:slug`
- `target`: `/newsroom`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "The official source for news about Apple, from Apple. Read press releases, get updates, watch video and download images.",
  "example": "/apple/newsroom",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "newsroom.ts",
  "maintainers": [
    "LinxHex"
  ],
  "module": "() => import('@/routes/apple/newsroom.ts')",
  "name": "Newsroom (中国大陆)",
  "path": "/newsroom",
  "radar": [
    {
      "source": [
        "www.apple.com.cn/newsroom",
        "www.apple.com.cn/newsroom/:year/:month/:slug"
      ],
      "target": "/newsroom"
    }
  ],
  "url": "www.apple.com.cn/newsroom",
  "view": 0,
  "zh": {
    "description": "Apple 新闻中心是 Apple 新闻的来源。阅读新闻稿、获取最新消息、观看视频和下载图片。",
    "example": "/apple/newsroom",
    "maintainers": [
      "LinxHex"
    ],
    "name": "新闻中心（中国大陆）",
    "path": "/newsroom",
    "url": "www.apple.com.cn/newsroom"
  }
}
```
