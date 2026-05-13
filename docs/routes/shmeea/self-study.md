# 上海市教育考试院 - 自学考试通知公告

## Coverage
`index-only`

## Route
- Namespace: `shmeea`
- Namespace Name: `上海市教育考试院`
- Route Path: `/self-study`
- Route Name: `自学考试通知公告`
- Example: `/shmeea/self-study`
- URL: `www.shmeea.edu.cn/page/04000/index.html`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `h2ws`
- Source Location: `self-study.ts`
- Source Module: `() => import('@/routes/shmeea/self-study.ts')`

## Description
_None_

## Parameters
_None_


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
  - `www.shmeea.edu.cn/page/04000/index.html`
  - `www.shmeea.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/shmeea/self-study",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "self-study.ts",
  "maintainers": [
    "h2ws"
  ],
  "module": "() => import('@/routes/shmeea/self-study.ts')",
  "name": "自学考试通知公告",
  "parameters": {},
  "path": "/self-study",
  "radar": [
    {
      "source": [
        "www.shmeea.edu.cn/page/04000/index.html",
        "www.shmeea.edu.cn/"
      ]
    }
  ],
  "url": "www.shmeea.edu.cn/page/04000/index.html"
}
```
