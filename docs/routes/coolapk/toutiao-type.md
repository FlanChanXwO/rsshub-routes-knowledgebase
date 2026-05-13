# 酷安 - 头条

## Coverage
`index-only`

## Route
- Namespace: `coolapk`
- Namespace Name: `酷安`
- Route Path: `/toutiao/:type?`
- Route Name: `头条`
- Example: `/coolapk/toutiao`
- URL: `coolapk.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `xizeyoupan`
- Source Location: `toutiao.ts`
- Source Module: `() => import('@/routes/coolapk/toutiao.ts')`

## Description
| 参数名称 | 历史头条 | 最新   |
| -------- | -------- | ------ |
| type     | history  | latest |

## Parameters
- `type`: 默认为history


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
  "description": "| 参数名称 | 历史头条 | 最新   |\n| -------- | -------- | ------ |\n| type     | history  | latest |",
  "example": "/coolapk/toutiao",
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
  "location": "toutiao.ts",
  "maintainers": [
    "xizeyoupan"
  ],
  "module": "() => import('@/routes/coolapk/toutiao.ts')",
  "name": "头条",
  "parameters": {
    "type": "默认为history"
  },
  "path": "/toutiao/:type?"
}
```
