# 广西民族大学 - 图书馆最新消息

## Coverage
`index-only`

## Route
- Namespace: `gxmzu`
- Namespace Name: `广西民族大学`
- Route Path: `/libzxxx`
- Route Name: `图书馆最新消息`
- Example: `/gxmzu/libzxxx`
- URL: `library.gxmzu.edu.cn/news/news_list.jsp`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `real-jiakai`
- Source Location: `lib.ts`
- Source Module: `() => import('@/routes/gxmzu/lib.ts')`

## Description
_None_

## Parameters
_None_


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
  - `library.gxmzu.edu.cn/news/news_list.jsp`
  - `library.gxmzu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/gxmzu/libzxxx",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "lib.ts",
  "maintainers": [
    "real-jiakai"
  ],
  "module": "() => import('@/routes/gxmzu/lib.ts')",
  "name": "图书馆最新消息",
  "parameters": {},
  "path": "/libzxxx",
  "radar": [
    {
      "source": [
        "library.gxmzu.edu.cn/news/news_list.jsp",
        "library.gxmzu.edu.cn/"
      ]
    }
  ],
  "url": "library.gxmzu.edu.cn/news/news_list.jsp"
}
```
