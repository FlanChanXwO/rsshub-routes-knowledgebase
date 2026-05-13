# 电子发烧友 - 资料

## Coverage
`index-only`

## Route
- Namespace: `elecfans`
- Namespace Name: `电子发烧友`
- Route Path: `/soft/:atype`
- Route Name: `资料`
- Example: `/elecfans/soft/special`
- URL: `www.elecfans.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `tian051011`
- Source Location: `soft.ts`
- Source Module: `() => import('@/routes/elecfans/soft.ts')`

## Description
_None_

## Parameters
- `atype`: 需获取资料的类别


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
  - `www.elecfans.com`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/elecfans/soft/special",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "soft.ts",
  "maintainers": [
    "tian051011"
  ],
  "module": "() => import('@/routes/elecfans/soft.ts')",
  "name": "资料",
  "parameters": {
    "atype": "需获取资料的类别"
  },
  "path": "/soft/:atype",
  "radar": [
    {
      "source": [
        "www.elecfans.com"
      ]
    }
  ]
}
```
