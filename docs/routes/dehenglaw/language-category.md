# 德恒律师事务所 - 德恒探索

## Coverage
`index-only`

## Route
- Namespace: `dehenglaw`
- Namespace Name: `德恒律师事务所`
- Route Path: `/:language?/:category?`
- Route Name: `德恒探索`
- Example: `/dehenglaw/CN/paper`
- URL: `dehenglaw.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/dehenglaw/index.ts')`

## Description
::: tip
  若订阅 [专业文章](https://dehenglaw.com/)，网址为 `https://www.dehenglaw.com/CN/paper/0008/000902.aspx`。截取 `https://dehenglaw.com/` 到末尾 `/0008/000902.aspx` 的部分 `CN/paper` 作为参数填入，此时路由为 [`/dehenglaw/CN/paper`](https://rsshub.app/dehenglaw/CN/paper)。

| 专业文章 | 出版物  | 德恒论坛 |
| -------- | ------- | -------- |
| paper    | publish | luntan   |
:::

## Parameters
- `language`: 语言，默认为中文，即 CN，可在对应分类页 URL 中找到，可选 CN 和 EN
- `category`: 分类，默认为专业文章，即 paper，可在对应分类页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `专业文章`
- `source`:
  - `dehenglaw.com/:language/paper/0008/000902.aspx`
- `target`: `/:language/paper`
### Rule 2
- `title`: `出版物`
- `source`:
  - `dehenglaw.com/:language/publish/0008/000903.aspx`
- `target`: `/:language/publish`
### Rule 3
- `title`: `德恒论坛`
- `source`:
  - `dehenglaw.com/:language/luntan/0008/000901.aspx`
- `target`: `/:language/luntan`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n  若订阅 [专业文章](https://dehenglaw.com/)，网址为 `https://www.dehenglaw.com/CN/paper/0008/000902.aspx`。截取 `https://dehenglaw.com/` 到末尾 `/0008/000902.aspx` 的部分 `CN/paper` 作为参数填入，此时路由为 [`/dehenglaw/CN/paper`](https://rsshub.app/dehenglaw/CN/paper)。\n\n| 专业文章 | 出版物  | 德恒论坛 |\n| -------- | ------- | -------- |\n| paper    | publish | luntan   |\n:::",
  "example": "/dehenglaw/CN/paper",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/dehenglaw/index.ts')",
  "name": "德恒探索",
  "parameters": {
    "category": "分类，默认为专业文章，即 paper，可在对应分类页 URL 中找到",
    "language": "语言，默认为中文，即 CN，可在对应分类页 URL 中找到，可选 CN 和 EN"
  },
  "path": "/:language?/:category?",
  "radar": [
    {
      "source": [
        "dehenglaw.com/:language/paper/0008/000902.aspx"
      ],
      "target": "/:language/paper",
      "title": "专业文章"
    },
    {
      "source": [
        "dehenglaw.com/:language/publish/0008/000903.aspx"
      ],
      "target": "/:language/publish",
      "title": "出版物"
    },
    {
      "source": [
        "dehenglaw.com/:language/luntan/0008/000901.aspx"
      ],
      "target": "/:language/luntan",
      "title": "德恒论坛"
    }
  ],
  "url": "dehenglaw.com"
}
```
