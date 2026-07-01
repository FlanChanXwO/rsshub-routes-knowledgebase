# 豆瓣 - 用户想看

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/people/:userid/wish`
- Route Name: `用户想看`
- Example: `/douban/people/exherb/wish`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `exherb`
- Source Location: `people/wish.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `userid`: 用户id


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
  "example": "/douban/people/exherb/wish",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "people/wish.ts",
  "maintainers": [
    "exherb"
  ],
  "name": "用户想看",
  "parameters": {
    "userid": "用户id"
  },
  "path": "/people/:userid/wish",
  "topFeeds": [
    {
      "description": "豆瓣想看 - Tredici - Powered by RSSHub",
      "errorAt": "2026-06-29T21:46:33.107Z",
      "errorMessage": "[GET] \"https://movie.douban.com/people/171811323/wish\": 403 Forbidden\n",
      "id": "242962409053608960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://movie.douban.com/people/171811323/wish",
      "title": "豆瓣想看 - Tredici",
      "type": "feed",
      "url": "rsshub://douban/people/171811323/wish"
    }
  ]
}
```
