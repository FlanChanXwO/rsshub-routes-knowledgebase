# 新榜 - 微信公众号

## Coverage
`index-only`

## Route
- Namespace: `newrank`
- Namespace Name: `新榜`
- Route Path: `/wechat/:wxid`
- Route Name: `微信公众号`
- Example: `/newrank/wechat/chijiread`
- URL: `newrank.cn`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `lessmoe, pseudoyu`
- Source Location: `wechat.ts`
- Source Module: `() => import('@/routes/newrank/wechat.ts')`

## Description
_None_

## Parameters
- `wxid`: 微信号，若微信号与新榜信息不一致，以新榜为准


## Features
- `requireConfig`: [{"description": "", "name": "NEWRANK_COOKIE"}]
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
    "social-media"
  ],
  "example": "/newrank/wechat/chijiread",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "NEWRANK_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "wechat.ts",
  "maintainers": [
    "lessmoe",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/newrank/wechat.ts')",
  "name": "微信公众号",
  "parameters": {
    "wxid": "微信号，若微信号与新榜信息不一致，以新榜为准"
  },
  "path": "/wechat/:wxid"
}
```
