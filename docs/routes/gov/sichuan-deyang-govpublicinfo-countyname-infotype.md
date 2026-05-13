# 国家能源局 - 政府公开信息

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/sichuan/deyang/govpublicinfo/:countyName/:infoType?`
- Route Name: `政府公开信息`
- Example: `/gov/sichuan/deyang/govpublicinfo/绵竹市`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `zytomorrow`
- Source Location: `sichuan/deyang/govpublicinfo.tsx`
- Source Module: `() => import('@/routes/gov/sichuan/deyang/govpublicinfo.tsx')`

## Description
| 法定主动内容 | 公示公告 |
| :----------: | :------: |
|    fdzdnr    |   gsgg   |

## Parameters
- `countyName`: 区县名（**其他区县整改中，暂时只支持`绵竹市`**）。德阳市、绵竹市、广汉市、什邡市、中江县、罗江区、旌阳区、高新区
- `infoType`: 信息类型。默认值:fdzdnr-“法定主动内容”


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
    "government"
  ],
  "description": "| 法定主动内容 | 公示公告 |\n| :----------: | :------: |\n|    fdzdnr    |   gsgg   |",
  "example": "/gov/sichuan/deyang/govpublicinfo/绵竹市",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "sichuan/deyang/govpublicinfo.tsx",
  "maintainers": [
    "zytomorrow"
  ],
  "module": "() => import('@/routes/gov/sichuan/deyang/govpublicinfo.tsx')",
  "name": "政府公开信息",
  "parameters": {
    "countyName": "区县名（**其他区县整改中，暂时只支持`绵竹市`**）。德阳市、绵竹市、广汉市、什邡市、中江县、罗江区、旌阳区、高新区",
    "infoType": "信息类型。默认值:fdzdnr-“法定主动内容”"
  },
  "path": "/sichuan/deyang/govpublicinfo/:countyName/:infoType?"
}
```
