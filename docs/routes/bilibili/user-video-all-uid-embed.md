# 哔哩哔哩 bilibili - 用户所有视频

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/user/video-all/:uid/:embed?`
- Route Name: `用户所有视频`
- Example: `/bilibili/user/video-all/2267573`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `None`
- Source Location: `video-all.ts`
- Source Module: `() => import('@/routes/bilibili/video-all.ts')`

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
  "location": "video-all.ts",
  "maintainers": [],
  "module": "() => import('@/routes/bilibili/video-all.ts')",
  "name": "用户所有视频",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/video-all/:uid/:embed?"
}
```
