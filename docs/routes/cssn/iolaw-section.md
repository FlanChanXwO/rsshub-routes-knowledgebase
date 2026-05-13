# Chinese Social Science Net - Institute of Law

## Coverage
`index-only`

## Route
- Namespace: `cssn`
- Namespace Name: `Chinese Social Science Net`
- Route Path: `/iolaw/:section?`
- Route Name: `Institute of Law`
- Example: `/cssn/iolaw/zxzp`
- URL: `iolaw.cssn.cn`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `HankChow`
- Source Location: `iolaw.ts`
- Source Module: `() => import('@/routes/cssn/iolaw.ts')`

## Description
_None_

## Parameters
- `section`: Section ID, can be found in the URL. For example, the Section ID of URL `http://iolaw.cssn.cn/zxzp/` is `zxzp`. The default value is `zxzp`


## Features
- `requireConfig`: false
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
    "study"
  ],
  "example": "/cssn/iolaw/zxzp",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "iolaw.ts",
  "maintainers": [
    "HankChow"
  ],
  "module": "() => import('@/routes/cssn/iolaw.ts')",
  "name": "Institute of Law",
  "parameters": {
    "section": "Section ID, can be found in the URL. For example, the Section ID of URL `http://iolaw.cssn.cn/zxzp/` is `zxzp`. The default value is `zxzp`"
  },
  "path": "/iolaw/:section?"
}
```
