# 清华大学 - 清华新闻

## Coverage
`index-only`

## Route
- Namespace: `tsinghua`
- Namespace Name: `清华大学`
- Route Path: `/news/:category?`
- Route Name: `清华新闻`
- Example: `/tsinghua/news`
- URL: `www.tsinghua.edu.cn/news.htm`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/tsinghua/news.ts')`

## Description
_None_

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到，留空为 `zxdt`


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
  - `www.tsinghua.edu.cn/news/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/tsinghua/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/tsinghua/news.ts')",
  "name": "清华新闻",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到，留空为 `zxdt`"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "www.tsinghua.edu.cn/news/:category"
      ]
    }
  ],
  "url": "www.tsinghua.edu.cn/news.htm"
}
```
