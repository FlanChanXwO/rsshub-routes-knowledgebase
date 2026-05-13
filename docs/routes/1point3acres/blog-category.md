# 一亩三分地 - 博客

## Coverage
`index-only`

## Route
- Namespace: `1point3acres`
- Namespace Name: `一亩三分地`
- Route Path: `/blog/:category?`
- Route Name: `博客`
- Example: `/1point3acres/blog`
- URL: `blog.1point3acres.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/1point3acres/blog.ts')`

## Description
| 留学申请   | 找工求职 | 生活攻略  | 投资理财 | 签证移民 | 时政要闻 |
| ---------- | -------- | --------- | -------- | -------- | -------- |
| studyinusa | career   | lifestyle | invest   | visa     | news     |

## Parameters
- `category`: 分类，见下表，可在对应分类页 URL 中找到


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
  - `blog.1point3acres.com/:category`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| 留学申请   | 找工求职 | 生活攻略  | 投资理财 | 签证移民 | 时政要闻 |\n| ---------- | -------- | --------- | -------- | -------- | -------- |\n| studyinusa | career   | lifestyle | invest   | visa     | news     |",
  "example": "/1point3acres/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/1point3acres/blog.ts')",
  "name": "博客",
  "parameters": {
    "category": "分类，见下表，可在对应分类页 URL 中找到"
  },
  "path": "/blog/:category?",
  "radar": [
    {
      "source": [
        "blog.1point3acres.com/:category"
      ]
    }
  ]
}
```
