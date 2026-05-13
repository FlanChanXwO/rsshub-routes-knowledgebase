# 微信小程序 - 公众号（优读来源）

## Coverage
`index-only`

## Route
- Namespace: `wechat`
- Namespace Name: `微信小程序`
- Route Path: `/uread/:userid`
- Route Name: `公众号（优读来源）`
- Example: `/wechat/uread/shensing`
- URL: `posts.careerengine.us`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `kt286`
- Source Location: `uread.ts`
- Source Module: `() => import('@/routes/wechat/uread.ts')`

## Description
_None_

## Parameters
- `userid`: 公众号的微信号, 可在 微信-公众号-更多资料 中找到。并不是所有的都支持，能不能用随缘


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
  "example": "/wechat/uread/shensing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "uread.ts",
  "maintainers": [
    "kt286"
  ],
  "module": "() => import('@/routes/wechat/uread.ts')",
  "name": "公众号（优读来源）",
  "parameters": {
    "userid": "公众号的微信号, 可在 微信-公众号-更多资料 中找到。并不是所有的都支持，能不能用随缘"
  },
  "path": "/uread/:userid"
}
```
