# 中国知网 - 网络首发

## Coverage
`index-only`

## Route
- Namespace: `cnki`
- Namespace Name: `中国知网`
- Route Path: `/journals/debut/:name`
- Route Name: `网络首发`
- Example: `/cnki/journals/debut/LKGP`
- URL: `navi.cnki.net`
- Language: `zh-CN`
- Categories: `journal`
- Maintainers: `Fatpandac`
- Source Location: `debut.ts`
- Source Module: `() => import('@/routes/cnki/debut.ts')`

## Description
_None_

## Parameters
- `name`: 期刊缩写，可以在网址中得到


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
  - `navi.cnki.net/knavi/journals/:name/detail`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/cnki/journals/debut/LKGP",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "debut.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/cnki/debut.ts')",
  "name": "网络首发",
  "parameters": {
    "name": "期刊缩写，可以在网址中得到"
  },
  "path": "/journals/debut/:name",
  "radar": [
    {
      "source": [
        "navi.cnki.net/knavi/journals/:name/detail"
      ]
    }
  ]
}
```
