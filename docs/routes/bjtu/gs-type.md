# Beijing Jiaotong University - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `bjtu`
- Namespace Name: `Beijing Jiaotong University`
- Route Path: `/gs/:type?`
- Route Name: `研究生院`
- Example: `/bjtu/gs/noti`
- URL: `bjtu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `E1nzbern`
- Source Location: `gs.ts`
- Source Module: `() => import('@/routes/bjtu/gs.ts')`

## Description
| 文章来源           | 参数         |
| ----------------- | ------------ |
| 通知公告_招生      | noti_zs      |
| 通知公告           | noti         |
| 新闻动态           | news         |
| 招生宣传           | zsxc         |
| 培养               | py           |
| 招生               | zs           |
| 学位               | xw           |
| 研工部             | ygb          |
| 通知公告 - 研工部   | ygbtzgg      |
| 新闻动态 - 研工部   | ygbnews      |
| 新闻封面 - 研工部   | ygbnewscover |
| 文章列表           | all          |
| 博士招生 - 招生专题 | bszs_zszt    |
| 硕士招生 - 招生专题 | sszs_zszt    |
| 招生简章 - 招生专题 | zsjz_zszt    |
| 政策法规 - 招生专题 | zcfg_zszt    |

::: tip
  文章来源的命名均来自研究生院网站标题。
  最常用的几项有“通知公告_招生”、“通知公告”、“博士招生 - 招生专题”、“硕士招生 - 招生专题”。
:::

## Parameters
- `type`: Article type


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `gs.bjtu.edu.cn`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "\n| 文章来源           | 参数         |\n| ----------------- | ------------ |\n| 通知公告_招生      | noti_zs      |\n| 通知公告           | noti         |\n| 新闻动态           | news         |\n| 招生宣传           | zsxc         |\n| 培养               | py           |\n| 招生               | zs           |\n| 学位               | xw           |\n| 研工部             | ygb          |\n| 通知公告 - 研工部   | ygbtzgg      |\n| 新闻动态 - 研工部   | ygbnews      |\n| 新闻封面 - 研工部   | ygbnewscover |\n| 文章列表           | all          |\n| 博士招生 - 招生专题 | bszs_zszt    |\n| 硕士招生 - 招生专题 | sszs_zszt    |\n| 招生简章 - 招生专题 | zsjz_zszt    |\n| 政策法规 - 招生专题 | zcfg_zszt    |\n\n::: tip\n  文章来源的命名均来自研究生院网站标题。\n  最常用的几项有“通知公告_招生”、“通知公告”、“博士招生 - 招生专题”、“硕士招生 - 招生专题”。\n:::",
  "example": "/bjtu/gs/noti",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gs.ts",
  "maintainers": [
    "E1nzbern"
  ],
  "module": "() => import('@/routes/bjtu/gs.ts')",
  "name": "研究生院",
  "parameters": {
    "type": "Article type"
  },
  "path": "/gs/:type?",
  "radar": [
    {
      "source": [
        "gs.bjtu.edu.cn"
      ]
    }
  ]
}
```
