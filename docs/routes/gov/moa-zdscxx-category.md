# 国家能源局 - 中华人民共和国农业农村部数据

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/moa/zdscxx/:category{.+}?`
- Route Name: `中华人民共和国农业农村部数据`
- Example: `/gov/moa/zdscxx`
- URL: `www.moa.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `moa/zdscxx.ts`
- Source Module: `() => import('@/routes/gov/moa/zdscxx.ts')`

## Description
::: tip
  若订阅 [中华人民共和国农业农村部数据](http://zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp) 的 `价格指数` 报告主题。此时路由为 [`/gov/moa/zdscxx/价格指数`](https://rsshub.app/gov/moa/zdscxx/价格指数)。

  若订阅 `央视网` 报告来源 的 `蔬菜生产` 报告主题。此时路由为 [`/gov/moa/zdscxx/央视网/蔬菜生产`](https://rsshub.app/gov/moa/zdscxx/央视网/蔬菜生产)。
:::

| 价格指数 | 供需形势 | 分析报告周报 | 分析报告日报 | 日历信息 | 蔬菜生产 |
| -------- | -------- | ------------ | ------------ | -------- | -------- |

## Parameters
- `category`: 分类，默认为全部，见下表


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
- `title`: `价格指数`
- `source`:
  - `zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp`
- `target`: `/gov/moa/zdscxx/价格指数`
### Rule 2
- `title`: `供需形势`
- `source`:
  - `zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp`
- `target`: `/gov/moa/zdscxx/供需形势`
### Rule 3
- `title`: `分析报告周报`
- `source`:
  - `zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp`
- `target`: `/gov/moa/zdscxx/分析报告周报`
### Rule 4
- `title`: `分析报告日报`
- `source`:
  - `zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp`
- `target`: `/gov/moa/zdscxx/分析报告日报`
### Rule 5
- `title`: `日历信息`
- `source`:
  - `zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp`
- `target`: `/gov/moa/zdscxx/日历信息`
### Rule 6
- `title`: `蔬菜生产`
- `source`:
  - `zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp`
- `target`: `/gov/moa/zdscxx/蔬菜生产`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n  若订阅 [中华人民共和国农业农村部数据](http://zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp) 的 `价格指数` 报告主题。此时路由为 [`/gov/moa/zdscxx/价格指数`](https://rsshub.app/gov/moa/zdscxx/价格指数)。\n\n  若订阅 `央视网` 报告来源 的 `蔬菜生产` 报告主题。此时路由为 [`/gov/moa/zdscxx/央视网/蔬菜生产`](https://rsshub.app/gov/moa/zdscxx/央视网/蔬菜生产)。\n:::\n\n| 价格指数 | 供需形势 | 分析报告周报 | 分析报告日报 | 日历信息 | 蔬菜生产 |\n| -------- | -------- | ------------ | ------------ | -------- | -------- |\n    ",
  "example": "/gov/moa/zdscxx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "moa/zdscxx.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gov/moa/zdscxx.ts')",
  "name": "中华人民共和国农业农村部数据",
  "parameters": {
    "category": "分类，默认为全部，见下表"
  },
  "path": "/moa/zdscxx/:category{.+}?",
  "radar": [
    {
      "source": [
        "zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp"
      ],
      "target": "/gov/moa/zdscxx/价格指数",
      "title": "价格指数"
    },
    {
      "source": [
        "zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp"
      ],
      "target": "/gov/moa/zdscxx/供需形势",
      "title": "供需形势"
    },
    {
      "source": [
        "zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp"
      ],
      "target": "/gov/moa/zdscxx/分析报告周报",
      "title": "分析报告周报"
    },
    {
      "source": [
        "zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp"
      ],
      "target": "/gov/moa/zdscxx/分析报告日报",
      "title": "分析报告日报"
    },
    {
      "source": [
        "zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp"
      ],
      "target": "/gov/moa/zdscxx/日历信息",
      "title": "日历信息"
    },
    {
      "source": [
        "zdscxx.moa.gov.cn:8080/nyb/pc/messageList.jsp"
      ],
      "target": "/gov/moa/zdscxx/蔬菜生产",
      "title": "蔬菜生产"
    }
  ],
  "url": "www.moa.gov.cn"
}
```
