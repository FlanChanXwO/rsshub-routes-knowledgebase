# 一亩三分地 - 录取结果

## Coverage
`index-only`

## Route
- Namespace: `1point3acres`
- Namespace Name: `一亩三分地`
- Route Path: `/offer/:year?/:major?/:school?`
- Route Name: `录取结果`
- Example: `/1point3acres/offer/12/null/CMU`
- URL: `offer.1point3acres.com/`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `EthanWng97`
- Source Location: `offer.tsx`
- Source Module: `() => import('@/routes/1point3acres/offer.tsx')`

## Description
::: tip 三个 id 获取方式
  1.  打开 [https://offer.1point3acres.com](https://offer.1point3acres.com)
  2.  打开控制台
  3.  切换到 Network 面板
  4.  点击 搜索 按钮
  5.  点击 results?ps=15&pg=1 POST 请求
  6.  找到 Request Payload 请求参数，例如 `filters: {planyr: "13", planmajor: "1", outname_w: "ACADIAU"}` ，则三个 id 分别为: 13,1,ACADIAU
:::

## Parameters
- `year`: 录取年份  id，空为null
- `major`: 录取专业 id，空为null
- `school`: 录取学校 id，空为null


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `offer.1point3acres.com/`
- `target`: `/offer`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: tip 三个 id 获取方式\n  1.  打开 [https://offer.1point3acres.com](https://offer.1point3acres.com)\n  2.  打开控制台\n  3.  切换到 Network 面板\n  4.  点击 搜索 按钮\n  5.  点击 results?ps=15&pg=1 POST 请求\n  6.  找到 Request Payload 请求参数，例如 `filters: {planyr: \"13\", planmajor: \"1\", outname_w: \"ACADIAU\"}` ，则三个 id 分别为: 13,1,ACADIAU\n:::",
  "example": "/1point3acres/offer/12/null/CMU",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "offer.tsx",
  "maintainers": [
    "EthanWng97"
  ],
  "module": "() => import('@/routes/1point3acres/offer.tsx')",
  "name": "录取结果",
  "parameters": {
    "major": "录取专业 id，空为null",
    "school": "录取学校 id，空为null",
    "year": "录取年份  id，空为null"
  },
  "path": "/offer/:year?/:major?/:school?",
  "radar": [
    {
      "source": [
        "offer.1point3acres.com/"
      ],
      "target": "/offer"
    }
  ],
  "url": "offer.1point3acres.com/"
}
```
