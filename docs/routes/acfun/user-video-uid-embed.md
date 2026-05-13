# AcFun - 用户投稿

## Coverage
`index-only`

## Route
- Namespace: `acfun`
- Namespace Name: `AcFun`
- Route Path: `/user/video/:uid/:embed?`
- Route Name: `用户投稿`
- Example: `/acfun/user/video/6102`
- URL: `www.acfun.cn`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `wdssmq`
- Source Location: `video.ts`
- Source Module: `() => import('@/routes/acfun/video.ts')`

## Description
_None_

## Parameters
- `uid`: 用户 UID
- `embed`: 默认为开启内嵌视频, 任意值为关闭


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.acfun.cn/u/:id`
- `target`: `/user/video/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/acfun/user/video/6102",
  "location": "video.ts",
  "maintainers": [
    "wdssmq"
  ],
  "module": "() => import('@/routes/acfun/video.ts')",
  "name": "用户投稿",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 UID"
  },
  "path": "/user/video/:uid/:embed?",
  "radar": [
    {
      "source": [
        "www.acfun.cn/u/:id"
      ],
      "target": "/user/video/:id"
    }
  ],
  "view": 3
}
```
