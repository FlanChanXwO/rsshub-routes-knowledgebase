# 酷安 - 看看号

## Coverage
`index-only`

## Route
- Namespace: `coolapk`
- Namespace Name: `酷安`
- Route Path: `/dyh/:dyhId`
- Route Name: `看看号`
- Example: `/coolapk/dyh/1524`
- URL: `coolapk.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `xizeyoupan`
- Source Location: `dyh.ts`
- Source Module: `() => import('@/routes/coolapk/dyh.ts')`

## Description
::: tip
  仅限于采集**站内订阅**的看看号的内容。看看号 ID 可在看看号界面右上分享 - 复制链接得到。
:::

## Parameters
- `dyhId`: 看看号ID


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
  "description": "::: tip\n  仅限于采集**站内订阅**的看看号的内容。看看号 ID 可在看看号界面右上分享 - 复制链接得到。\n:::",
  "example": "/coolapk/dyh/1524",
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
  "location": "dyh.ts",
  "maintainers": [
    "xizeyoupan"
  ],
  "module": "() => import('@/routes/coolapk/dyh.ts')",
  "name": "看看号",
  "parameters": {
    "dyhId": "看看号ID"
  },
  "path": "/dyh/:dyhId"
}
```
