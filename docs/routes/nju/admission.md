# 南京大学 - 本科迎新

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/admission`
- Route Name: `本科迎新`
- Example: `/nju/admission`
- URL: `admission.nju.edu.cn/tzgg/index.html`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `admission.ts`
- Source Module: `() => import('@/routes/nju/admission.ts')`

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
  - `admission.nju.edu.cn/tzgg/index.html`
  - `admission.nju.edu.cn/tzgg`
  - `admission.nju.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/nju/admission",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "admission.ts",
  "maintainers": [
    "ret-1"
  ],
  "module": "() => import('@/routes/nju/admission.ts')",
  "name": "本科迎新",
  "parameters": {},
  "path": "/admission",
  "radar": [
    {
      "source": [
        "admission.nju.edu.cn/tzgg/index.html",
        "admission.nju.edu.cn/tzgg",
        "admission.nju.edu.cn/"
      ]
    }
  ],
  "url": "admission.nju.edu.cn/tzgg/index.html"
}
```
