# 央视新闻 - 专题

## Coverage
`index-only`

## Route
- Namespace: `cctv`
- Namespace Name: `央视新闻`
- Route Path: `/:category`
- Route Name: `专题`
- Example: `/cctv/world`
- URL: `news.cctv.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `idealclover, xyqfer`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/cctv/category.ts')`

## Description
| 新闻 | 国内  | 国际  | 社会    | 法治 | 文娱 | 科技 | 生活 | 教育 | 每周质量报告 | 新闻 1+1  |
| ---- | ----- | ----- | ------- | ---- | ---- | ---- | ---- | ---- | ------------ | --------- |
| news | china | world | society | law  | ent  | tech | life | edu  | mzzlbg       | xinwen1j1 |

## Parameters
- `category`: 分类名


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
  - `news.cctv.com/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 新闻 | 国内  | 国际  | 社会    | 法治 | 文娱 | 科技 | 生活 | 教育 | 每周质量报告 | 新闻 1+1  |\n| ---- | ----- | ----- | ------- | ---- | ---- | ---- | ---- | ---- | ------------ | --------- |\n| news | china | world | society | law  | ent  | tech | life | edu  | mzzlbg       | xinwen1j1 |",
  "example": "/cctv/world",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "category.ts",
  "maintainers": [
    "idealclover",
    "xyqfer"
  ],
  "module": "() => import('@/routes/cctv/category.ts')",
  "name": "专题",
  "parameters": {
    "category": "分类名"
  },
  "path": "/:category",
  "radar": [
    {
      "source": [
        "news.cctv.com/:category"
      ]
    }
  ]
}
```
