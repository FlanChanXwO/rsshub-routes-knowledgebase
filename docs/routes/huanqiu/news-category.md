# 环球网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `huanqiu`
- Namespace Name: `环球网`
- Route Path: `/news/:category?`
- Route Name: `分类`
- Example: `/huanqiu/news/china`
- URL: `huanqiu.com/`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `yuxinliu-alex`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/huanqiu/index.ts')`

## Description
| 国内新闻 | 国际新闻 | 军事 | 台海   | 评论    |
| -------- | -------- | ---- | ------ | ------- |
| china    | world    | mil  | taiwai | opinion |

## Parameters
- `category`: 类别，可以使用二级域名作为参数，默认为：china


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
  - `huanqiu.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 国内新闻 | 国际新闻 | 军事 | 台海   | 评论    |\n| -------- | -------- | ---- | ------ | ------- |\n| china    | world    | mil  | taiwai | opinion |",
  "example": "/huanqiu/news/china",
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
    "yuxinliu-alex"
  ],
  "module": "() => import('@/routes/huanqiu/index.ts')",
  "name": "分类",
  "parameters": {
    "category": "类别，可以使用二级域名作为参数，默认为：china"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "huanqiu.com/"
      ]
    }
  ],
  "url": "huanqiu.com/"
}
```
