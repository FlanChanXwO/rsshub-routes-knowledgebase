# 观察者网 - 首页

## Coverage
`index-only`

## Route
- Namespace: `guancha`
- Namespace Name: `观察者网`
- Route Path: `/:category?`
- Route Name: `首页`
- Example: `/guancha`
- URL: `guancha.cn/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk, Jeason0228`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/guancha/index.ts')`

## Description
| 全部 | 评论 & 研究 | 要闻  | 风闻    | 热点新闻 | 滚动新闻 |
| ---- | ----------- | ----- | ------- | -------- | -------- |
| all  | review      | story | fengwen | redian   | gundong  |

  home = 评论 & 研究 + 要闻 + 风闻

  others = 热点新闻 + 滚动新闻

::: tip
  观察者网首页左中右的三个 column 分别对应 **评论 & 研究**、**要闻**、**风闻** 三个部分。
:::

## Parameters
- `category`: 分类，见下表，默认为全部


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
  - `guancha.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 全部 | 评论 & 研究 | 要闻  | 风闻    | 热点新闻 | 滚动新闻 |\n| ---- | ----------- | ----- | ------- | -------- | -------- |\n| all  | review      | story | fengwen | redian   | gundong  |\n\n  home = 评论 & 研究 + 要闻 + 风闻\n\n  others = 热点新闻 + 滚动新闻\n\n::: tip\n  观察者网首页左中右的三个 column 分别对应 **评论 & 研究**、**要闻**、**风闻** 三个部分。\n:::",
  "example": "/guancha",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "Jeason0228"
  ],
  "module": "() => import('@/routes/guancha/index.ts')",
  "name": "首页",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "guancha.cn/"
      ]
    }
  ],
  "url": "guancha.cn/"
}
```
