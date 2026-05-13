# 北京大学 - 研究生招生网

## Coverage
`index-only`

## Route
- Namespace: `pku`
- Namespace Name: `北京大学`
- Route Path: `/admission/sszs`
- Route Name: `研究生招生网`
- Example: `/pku/admission/sszs`
- URL: `admission.pku.edu.cn/zsxx/sszs/index.htm`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `pkuyjs`
- Source Location: `pkuyjs.ts`
- Source Module: `() => import('@/routes/pku/pkuyjs.ts')`

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
  - `admission.pku.edu.cn/zsxx/sszs/index.htm`
  - `admission.pku.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/pku/admission/sszs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "pkuyjs.ts",
  "maintainers": [
    "pkuyjs"
  ],
  "module": "() => import('@/routes/pku/pkuyjs.ts')",
  "name": "研究生招生网",
  "parameters": {},
  "path": "/admission/sszs",
  "radar": [
    {
      "source": [
        "admission.pku.edu.cn/zsxx/sszs/index.htm",
        "admission.pku.edu.cn/"
      ]
    }
  ],
  "url": "admission.pku.edu.cn/zsxx/sszs/index.htm"
}
```
