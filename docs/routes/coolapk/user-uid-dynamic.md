# 酷安 - 用户

## Coverage
`index-only`

## Route
- Namespace: `coolapk`
- Namespace Name: `酷安`
- Route Path: `/user/:uid/dynamic`
- Route Name: `用户`
- Example: `/coolapk/user/3177668/dynamic`
- URL: `coolapk.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `xizeyoupan`
- Source Location: `user-dynamic.ts`
- Source Module: `() => import('@/routes/coolapk/user-dynamic.ts')`

## Description
_None_

## Parameters
- `uid`: 在个人界面右上分享-复制链接获取


## Features
- `requireConfig`: [{"description": "设置为`true`并添加`image_hotlink_template`参数来代理图片", "name": "ALLOW_USER_HOTLINK_TEMPLATE", "optional": true}]
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
  "example": "/coolapk/user/3177668/dynamic",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "设置为`true`并添加`image_hotlink_template`参数来代理图片",
        "name": "ALLOW_USER_HOTLINK_TEMPLATE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user-dynamic.ts",
  "maintainers": [
    "xizeyoupan"
  ],
  "module": "() => import('@/routes/coolapk/user-dynamic.ts')",
  "name": "用户",
  "parameters": {
    "uid": "在个人界面右上分享-复制链接获取"
  },
  "path": "/user/:uid/dynamic"
}
```
