# 国家能源局 - 最新政策

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/zhengce/zuixin`
- Route Name: `最新政策`
- Example: `/gov/zhengce/zuixin`
- URL: `www.gov.cn/zhengce/zuixin.htm`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `SettingDust, nczitzk`
- Source Location: `zhengce/index.ts`
- Source Module: `() => import('@/routes/gov/zhengce/index.ts')`

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
  - `www.gov.cn/zhengce/zuixin.htm`
  - `www.gov.cn/`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/zhengce/zuixin",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "zhengce/index.ts",
  "maintainers": [
    "SettingDust",
    "nczitzk"
  ],
  "module": "() => import('@/routes/gov/zhengce/index.ts')",
  "name": "最新政策",
  "parameters": {},
  "path": [
    "/zhengce/zuixin",
    "/zhengce/:category{.+}?"
  ],
  "radar": [
    {
      "source": [
        "www.gov.cn/zhengce/zuixin.htm",
        "www.gov.cn/"
      ]
    }
  ],
  "url": "www.gov.cn/zhengce/zuixin.htm"
}
```
