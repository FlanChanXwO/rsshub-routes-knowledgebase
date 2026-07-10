# 哔哩哔哩 bilibili - 用户所有视频

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/user/video-all/:uid/:embed?`
- Route Name: `用户所有视频`
- Example: `/bilibili/user/video-all/2267573`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `None`
- Source Location: `video-all.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `embed`: 默认为开启内嵌视频, 任意值为关闭


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/video-all/2267573",
  "heat": 1267,
  "location": "video-all.ts",
  "maintainers": [],
  "name": "用户所有视频",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/video-all/:uid/:embed?",
  "topFeeds": [
    {
      "description": "技术爬爬虾 的 bilibili 所有视频 - Powered by RSSHub",
      "errorAt": "2026-07-08T05:56:08.280Z",
      "errorMessage": "Failed to fetch\nCannot read properties of undefined (reading 'vlist')\n",
      "id": "82801159002601472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/316183842/video",
      "title": "技术爬爬虾",
      "type": "feed",
      "url": "rsshub://bilibili/user/video-all/316183842"
    },
    {
      "description": "小Lin说 的 bilibili 所有视频 - Powered by RSSHub",
      "errorAt": "2026-07-08T13:33:11.591Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://space.bilibili.com/520819684/video?tid=0&page=1&keyword=&order=pubdate\": 412 Precondition Failed\n[GET] \"https://api.bilibili.com/x/space/wbi/arc/search?mid=520819684&ps=30&tid=0&pn=1&keyword=&order=pubdate&platform=web&web_location=1550101&order_avoided=true&dm_img_list=[{\\\"x\\\":6317,\\\"y\\\":-1452,\\\"z\\\":0,\\\"timestamp\\\":34,\\\"type\\\":0}]&dm_img_str=bm8gd2ViZ2&dm_cover_img_str=bm8gd2ViZ2&w_rid=d4bbb35a37dbdaba624d05c6e86f203f&wts=1783570100\": 412 Precondition Failed\nCannot read properties of undefined (reading 'vlist')\n",
      "id": "69028952282503168",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/520819684/video",
      "title": "小Lin说",
      "type": "feed",
      "url": "rsshub://bilibili/user/video-all/520819684"
    }
  ]
}
```
