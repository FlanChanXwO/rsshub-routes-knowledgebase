# 酷安 - 话题

## Coverage
`index-only`

## Route
- Namespace: `coolapk`
- Namespace Name: `酷安`
- Route Path: `/huati/:tag`
- Route Name: `话题`
- Example: `/coolapk/huati/iPhone`
- URL: `coolapk.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `xizeyoupan`
- Source Location: `huati.ts`
- Source Module: `() => import('@/routes/coolapk/huati.ts')`

## Description
_None_

## Parameters
- `tag`: 话题名称


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
  "example": "/coolapk/huati/iPhone",
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
  "location": "huati.ts",
  "maintainers": [
    "xizeyoupan"
  ],
  "module": "() => import('@/routes/coolapk/huati.ts')",
  "name": "话题",
  "parameters": {
    "tag": "话题名称"
  },
  "path": "/huati/:tag"
}
```
