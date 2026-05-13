# 小红书 - 用户笔记/收藏

## Coverage
`index-only`

## Route
- Namespace: `xiaohongshu`
- Namespace Name: `小红书`
- Route Path: `/user/:user_id/:category/:routeParams?`
- Route Name: `用户笔记/收藏`
- Example: `/xiaohongshu/user/593032945e87e77791e03696/notes`
- URL: `xiaohongshu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `lotosbin, howerhe, rien7, dddaniel1, pseudoyu`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/xiaohongshu/user.ts')`

## Description
_None_

## Parameters
- `user_id`: user id, length 24 characters
- `category`: {"default": "notes", "description": "category, notes or collect", "options": [{"label": "notes", "value": "notes"}, {"label": "collect", "value": "collect"}]}
- `routeParams`: {"default": "0", "description": "displayLivePhoto,`/user/:user_id/notes/displayLivePhoto=0`,不限时LivePhoto显示为图片,`/user/:user_id/notes/displayLivePhoto=1`,取值不为0时LivePhoto显示为视频"}


## Features
- `antiCrawler`: true
- `requirePuppeteer`: true
- `requireConfig`: [{"description": "小红书 cookie 值，可在网络里面看到。", "name": "XIAOHONGSHU_COOKIE", "optional": true}]

## Radar
### Rule 1
- `source`:
  - `xiaohongshu.com/user/profile/:user_id`
- `target`: `/user/:user_id/notes`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/xiaohongshu/user/593032945e87e77791e03696/notes",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "小红书 cookie 值，可在网络里面看到。",
        "name": "XIAOHONGSHU_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": true
  },
  "location": "user.ts",
  "maintainers": [
    "lotosbin",
    "howerhe",
    "rien7",
    "dddaniel1",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/xiaohongshu/user.ts')",
  "name": "用户笔记/收藏",
  "parameters": {
    "category": {
      "default": "notes",
      "description": "category, notes or collect",
      "options": [
        {
          "label": "notes",
          "value": "notes"
        },
        {
          "label": "collect",
          "value": "collect"
        }
      ]
    },
    "routeParams": {
      "default": "0",
      "description": "displayLivePhoto,`/user/:user_id/notes/displayLivePhoto=0`,不限时LivePhoto显示为图片,`/user/:user_id/notes/displayLivePhoto=1`,取值不为0时LivePhoto显示为视频"
    },
    "user_id": "user id, length 24 characters"
  },
  "path": "/user/:user_id/:category/:routeParams?",
  "radar": [
    {
      "source": [
        "xiaohongshu.com/user/profile/:user_id"
      ],
      "target": "/user/:user_id/notes"
    }
  ],
  "view": 0
}
```
