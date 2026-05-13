# 天使动漫论坛 - BD

## Coverage
`index-only`

## Route
- Namespace: `tsdm39`
- Namespace Name: `天使动漫论坛`
- Route Path: `/bd/:type?`
- Route Name: `BD`
- Example: `/tsdm39/bd`
- URL: `www.tsdm39.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `equt`
- Source Location: `bd.ts`
- Source Module: `() => import('@/routes/tsdm39/bd.ts')`

## Description
| 720P | 1080P | BDMV | 4K | AV1 |
| :--: | :--: | :--: | :--: | :--: |
| 403 | 404 | 405 | 4130 | 5815 |

## Parameters
- `type`: BD type, checkout the table below for details


## Features
- `requireConfig`: [{"description": "天使动漫论坛登陆后的 cookie 值，可在浏览器控制台通过 `document.cookie` 获取。", "name": "TSDM39_COOKIES", "optional": false}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "| 720P | 1080P | BDMV | 4K | AV1 |\n| :--: | :--: | :--: | :--: | :--: |\n| 403 | 404 | 405 | 4130 | 5815 |",
  "example": "/tsdm39/bd",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "天使动漫论坛登陆后的 cookie 值，可在浏览器控制台通过 `document.cookie` 获取。",
        "name": "TSDM39_COOKIES",
        "optional": false
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bd.ts",
  "maintainers": [
    "equt"
  ],
  "module": "() => import('@/routes/tsdm39/bd.ts')",
  "name": "BD",
  "parameters": {
    "type": "BD type, checkout the table below for details"
  },
  "path": "/bd/:type?"
}
```
