# 财联社 - 话题

## Coverage
`index-only`

## Route
- Namespace: `cls`
- Namespace Name: `财联社`
- Route Path: `/subject/:id?`
- Route Name: `话题`
- Example: `/cls/subject/1103`
- URL: `www.cls.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `subject.ts`
- Source Module: `() => import('@/routes/cls/subject.ts')`

## Description
::: tip
  若订阅 [有声早报](https://www.cls.cn/subject/1151)，网址为 `https://www.cls.cn/subject/1151`。截取 `https://www.cls.cn/subject/` 到末尾的部分 `1151` 作为参数填入，此时路由为 [`/cls/subject/1151`](https://rsshub.app/cls/subject/1151)。
:::

## Parameters
- `category`: 分类，默认为 1103，即A股盘面直播，可在对应话题页 URL 中找到


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
- `source`:
  - `www.cls.cn/subject/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n  若订阅 [有声早报](https://www.cls.cn/subject/1151)，网址为 `https://www.cls.cn/subject/1151`。截取 `https://www.cls.cn/subject/` 到末尾的部分 `1151` 作为参数填入，此时路由为 [`/cls/subject/1151`](https://rsshub.app/cls/subject/1151)。\n:::\n    ",
  "example": "/cls/subject/1103",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "subject.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/cls/subject.ts')",
  "name": "话题",
  "parameters": {
    "category": "分类，默认为 1103，即A股盘面直播，可在对应话题页 URL 中找到"
  },
  "path": "/subject/:id?",
  "radar": [
    {
      "source": [
        "www.cls.cn/subject/:id"
      ]
    }
  ],
  "url": "www.cls.cn"
}
```
