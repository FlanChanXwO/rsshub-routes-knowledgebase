# 东方财富 - 天天基金用户动态

## Coverage
`index-only`

## Route
- Namespace: `eastmoney`
- Namespace Name: `东方财富`
- Route Path: `/ttjj/user/:uid`
- Route Name: `天天基金用户动态`
- Example: `/eastmoney/ttjj/user/6551094298949188`
- URL: `data.eastmoney.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `zidekuls`
- Source Location: `ttjj/user.ts`
- Source Module: `() => import('@/routes/eastmoney/ttjj/user.ts')`

## Description
_None_

## Parameters
- `uid`: 用户id, 可以通过天天基金App分享用户主页到浏览器，在相应的URL中找到


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
    "finance"
  ],
  "example": "/eastmoney/ttjj/user/6551094298949188",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ttjj/user.ts",
  "maintainers": [
    "zidekuls"
  ],
  "module": "() => import('@/routes/eastmoney/ttjj/user.ts')",
  "name": "天天基金用户动态",
  "parameters": {
    "uid": "用户id, 可以通过天天基金App分享用户主页到浏览器，在相应的URL中找到"
  },
  "path": "/ttjj/user/:uid",
  "view": 1
}
```
