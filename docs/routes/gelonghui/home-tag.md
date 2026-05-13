# 格隆汇 - 首页

## Coverage
`index-only`

## Route
- Namespace: `gelonghui`
- Namespace Name: `格隆汇`
- Route Path: `/home/:tag?`
- Route Name: `首页`
- Example: `/gelonghui/home`
- URL: `gelonghui.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `home.ts`
- Source Module: `() => import('@/routes/gelonghui/home.ts')`

## Description
| 推荐            | 股票  | 基金 | 新股       | 研报     |
| --------------- | ----- | ---- | ---------- | -------- |
| web_home_page | stock | fund | new_stock | research |

## Parameters
- `tag`: {"description": "分类标签，见下表，默认为 `web_home_page`", "options": [{"label": "推荐", "value": "web_home_page"}, {"label": "股票", "value": "stock"}, {"label": "基金", "value": "fund"}, {"label": "新股", "value": "new_stock"}, {"label": "研报", "value": "research"}]}


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
    "finance"
  ],
  "description": "| 推荐            | 股票  | 基金 | 新股       | 研报     |\n| --------------- | ----- | ---- | ---------- | -------- |\n| web_home_page | stock | fund | new_stock | research |",
  "example": "/gelonghui/home",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "home.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/gelonghui/home.ts')",
  "name": "首页",
  "parameters": {
    "tag": {
      "description": "分类标签，见下表，默认为 `web_home_page`",
      "options": [
        {
          "label": "推荐",
          "value": "web_home_page"
        },
        {
          "label": "股票",
          "value": "stock"
        },
        {
          "label": "基金",
          "value": "fund"
        },
        {
          "label": "新股",
          "value": "new_stock"
        },
        {
          "label": "研报",
          "value": "research"
        }
      ]
    }
  },
  "path": "/home/:tag?",
  "view": 0
}
```
