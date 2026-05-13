# 第一财经 - DT 财经

## Coverage
`index-only`

## Route
- Namespace: `yicai`
- Namespace Name: `第一财经`
- Route Path: `/dt/:column?/:category?`
- Route Name: `DT 财经`
- Example: `/yicai/dt/article`
- URL: `yicai.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `dt.ts`
- Source Module: `() => import('@/routes/yicai/dt.ts')`

## Description
#### [文章](https://dt.yicai.com/article)

| 分类     | ID         |
| -------- | ---------- |
| 全部     | article/0  |
| 新流行   | article/31 |
| 新趋势   | article/32 |
| 商业黑马 | article/33 |
| 新品     | article/34 |
| 营销     | article/35 |
| 大公司   | article/36 |
| 城市生活 | article/38 |

#### [报告](https://dt.yicai.com/report)

| 分类       | ID        |
| ---------- | --------- |
| 全部       | report/0  |
| 人群观念   | report/9  |
| 人群行为   | report/22 |
| 美妆个护   | report/23 |
| 3C 数码    | report/24 |
| 营销趋势   | report/25 |
| 服饰鞋包   | report/27 |
| 互联网     | report/28 |
| 城市与居住 | report/29 |
| 消费趋势   | report/30 |
| 生活趋势   | report/37 |

#### [可视化](https://dt.yicai.com/visualization)

| 分类     | ID               |
| -------- | ---------------- |
| 全部     | visualization/0  |
| 新流行   | visualization/39 |
| 新趋势   | visualization/40 |
| 商业黑马 | visualization/41 |
| 新品     | visualization/42 |
| 营销     | visualization/43 |
| 大公司   | visualization/44 |
| 城市生活 | visualization/45 |

## Parameters
- `column`: 栏目，见下表，默认为文章
- `category`: 分类，见下表，默认为全部


## Features
- `requireConfig`: false
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
    "traditional-media"
  ],
  "description": "#### [文章](https://dt.yicai.com/article)\n\n| 分类     | ID         |\n| -------- | ---------- |\n| 全部     | article/0  |\n| 新流行   | article/31 |\n| 新趋势   | article/32 |\n| 商业黑马 | article/33 |\n| 新品     | article/34 |\n| 营销     | article/35 |\n| 大公司   | article/36 |\n| 城市生活 | article/38 |\n\n#### [报告](https://dt.yicai.com/report)\n\n| 分类       | ID        |\n| ---------- | --------- |\n| 全部       | report/0  |\n| 人群观念   | report/9  |\n| 人群行为   | report/22 |\n| 美妆个护   | report/23 |\n| 3C 数码    | report/24 |\n| 营销趋势   | report/25 |\n| 服饰鞋包   | report/27 |\n| 互联网     | report/28 |\n| 城市与居住 | report/29 |\n| 消费趋势   | report/30 |\n| 生活趋势   | report/37 |\n\n#### [可视化](https://dt.yicai.com/visualization)\n\n| 分类     | ID               |\n| -------- | ---------------- |\n| 全部     | visualization/0  |\n| 新流行   | visualization/39 |\n| 新趋势   | visualization/40 |\n| 商业黑马 | visualization/41 |\n| 新品     | visualization/42 |\n| 营销     | visualization/43 |\n| 大公司   | visualization/44 |\n| 城市生活 | visualization/45 |",
  "example": "/yicai/dt/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/yicai/dt.ts')",
  "name": "DT 财经",
  "parameters": {
    "category": "分类，见下表，默认为全部",
    "column": "栏目，见下表，默认为文章"
  },
  "path": "/dt/:column?/:category?"
}
```
