# 中国知网 - 期刊

## Coverage
`index-only`

## Route
- Namespace: `cnki`
- Namespace Name: `中国知网`
- Route Path: `/journals/:name`
- Route Name: `期刊`
- Example: `/cnki/journals/LKGP`
- URL: `navi.cnki.net`
- Language: `zh-CN`
- Categories: `journal`
- Maintainers: `Fatpandac, Derekmini, pseudoyu`
- Source Location: `journals.ts`
- Source Module: `() => import('@/routes/cnki/journals.ts')`

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
  "example": "/cnki/journals/LKGP",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "journals.ts",
  "maintainers": [
    "Fatpandac",
    "Derekmini",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/cnki/journals.ts')",
  "name": "期刊",
  "parameters": {
    "name": "期刊缩写，可以在网址中得到"
  },
  "path": "/journals/:name",
  "radar": [
    {
      "source": [
        "navi.cnki.net/knavi/journals/:name/detail"
      ]
    }
  ]
}
```
