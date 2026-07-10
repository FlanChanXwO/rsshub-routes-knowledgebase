# 灰豚数据 - 小红书笔记

## Coverage
`index-only`

## Route
- Namespace: `huitun`
- Namespace Name: `灰豚数据`
- Route Path: `/huitun/xiaohongshu/:user_id`
- Route Name: `小红书笔记`
- Example: `/huitun/xiaohongshu/52d8c541b4c4d60e6c867480`
- URL: `www.huitun.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Skylwn`
- Source Location: `xiaohongshu.ts`
- Source Module: `_None_`

## Description
免费版账户每天查询次数为 10 次，若需增加查询次数请购买灰豚数据红薯版会员

## Parameters
- `user_id`: 小红书用户号，需登录小红书网页端查询


## Features
- `requireConfig`: [{"description": "灰豚数据 cookie 值", "name": "HUITUN_COOKIE"}]
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
  "description": "免费版账户每天查询次数为 10 次，若需增加查询次数请购买灰豚数据红薯版会员",
  "example": "/huitun/xiaohongshu/52d8c541b4c4d60e6c867480",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "灰豚数据 cookie 值",
        "name": "HUITUN_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "xiaohongshu.ts",
  "maintainers": [
    "Skylwn"
  ],
  "name": "小红书笔记",
  "parameters": {
    "user_id": "小红书用户号，需登录小红书网页端查询"
  },
  "path": "/xiaohongshu/:user_id",
  "topFeeds": []
}
```
