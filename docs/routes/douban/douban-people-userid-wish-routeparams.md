# 豆瓣 - 用户想看

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/people/:userid/wish/:routeParams?`
- Route Name: `用户想看`
- Example: `/douban/people/exherb/wish`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `exherb`
- Source Location: `people/wish.ts`
- Source Module: `_None_`

## Description
对于豆瓣用户想看的内容，在 `routeParams` 参数中以 query string 格式设置如下选项可以控制输出的样式

| 键         | 含义       | 接受的值 | 默认值 |
| ---------- | ---------- | -------- | ------ |
| pagesCount | 查询页面数 |          | 1      |

## Parameters
- `userid`: 用户id
- `routeParams`: 额外参数；见下


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
  "description": "对于豆瓣用户想看的内容，在 `routeParams` 参数中以 query string 格式设置如下选项可以控制输出的样式\n\n| 键         | 含义       | 接受的值 | 默认值 |\n| ---------- | ---------- | -------- | ------ |\n| pagesCount | 查询页面数 |          | 1      |",
  "example": "/douban/people/exherb/wish",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "people/wish.ts",
  "maintainers": [
    "exherb"
  ],
  "name": "用户想看",
  "parameters": {
    "routeParams": "额外参数；见下",
    "userid": "用户id"
  },
  "path": "/people/:userid/wish/:routeParams?",
  "topFeeds": [
    {
      "description": "豆瓣想看 - kiki - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "169385164284093440",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://movie.douban.com/people/46349710/wish",
      "title": "豆瓣想看 - kiki",
      "type": "feed",
      "url": "rsshub://douban/people/46349710/wish"
    },
    {
      "description": "豆瓣想看 - 白Rap的DJ - Powered by RSSHub",
      "errorAt": "2025-11-04T02:38:56.520Z",
      "errorMessage": "Failed to fetch\n",
      "id": "186422945668491341",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://movie.douban.com/people/270652243/wish",
      "title": "豆瓣想看 - 白Rap的DJ",
      "type": "feed",
      "url": "rsshub://douban/people/270652243/wish"
    }
  ]
}
```
