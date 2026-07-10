# 豆瓣 - 最新回应过的日记

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/replied/:uid`
- Route Name: `最新回应过的日记`
- Example: `/douban/replied/xiaoyaxiaoya`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `nczitzk`
- Source Location: `other/replied.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户id，可在用户日记页 URL 中找到


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
    "social-media"
  ],
  "example": "/douban/replied/xiaoyaxiaoya",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "other/replied.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "最新回应过的日记",
  "parameters": {
    "uid": "用户id，可在用户日记页 URL 中找到"
  },
  "path": "/replied/:uid",
  "topFeeds": []
}
```
