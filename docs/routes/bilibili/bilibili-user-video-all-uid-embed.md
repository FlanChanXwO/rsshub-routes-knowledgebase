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
  "heat": 1264,
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
      "errorAt": "2026-02-20T11:45:38.308Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://api.bilibili.com/x/space/wbi/arc/search?mid=316183842&ps=30&tid=0&pn=1&keyword=&order=pubdate&platform=web&web_location=1550101&order_avoided=true&dm_img_list=[{\\\"x\\\":6341,\\\"y\\\":-1512,\\\"z\\\":0,\\\"timestamp\\\":36,\\\"type\\\":0}]&dm_img_str=bm8gd2ViZ2&dm_cover_img_str=bm8gd2ViZ2&w_rid=900dc3add1212fd3f06d38b52f8dd9d8&wts=1780298868\": <no response> fetch failed\n",
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
      "errorAt": "2026-02-20T14:10:00.367Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://space.bilibili.com/520819684/video?tid=0&page=1&keyword=&order=pubdate\": 412 Precondition Failed\n[GET] \"https://api.bilibili.com/x/space/wbi/arc/search?mid=520819684&ps=30&tid=0&pn=1&keyword=&order=pubdate&platform=web&web_location=1550101&order_avoided=true&dm_img_list=[{\\\"x\\\":6290,\\\"y\\\":-1442,\\\"z\\\":0,\\\"timestamp\\\":36,\\\"type\\\":0}]&dm_img_str=bm8gd2ViZ2&dm_cover_img_str=bm8gd2ViZ2&w_rid=9895df7ad0d4b51b5099d3ef08593980&wts=1780264368\": <no response> fetch failed\n",
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
