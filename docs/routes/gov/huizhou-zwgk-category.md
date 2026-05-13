# 国家能源局 - 惠州市人民政府

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/huizhou/zwgk/:category?`
- Route Name: `惠州市人民政府`
- Example: `/gov/huizhou/zwgk/jgdt`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `huizhou/zwgk/index.ts`
- Source Module: `() => import('@/routes/gov/huizhou/zwgk/index.ts')`

## Description
#### 政务公开 {#guang-dong-sheng-ren-min-zheng-fu-hui-zhou-shi-ren-min-zheng-fu-zheng-wu-gong-kai}

## Parameters
- `category`: 资讯类别，可以从网址中得到，默认为政务要闻


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
  "description": "#### 政务公开 {#guang-dong-sheng-ren-min-zheng-fu-hui-zhou-shi-ren-min-zheng-fu-zheng-wu-gong-kai}",
  "example": "/gov/huizhou/zwgk/jgdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "huizhou/zwgk/index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/gov/huizhou/zwgk/index.ts')",
  "name": "惠州市人民政府",
  "parameters": {
    "category": "资讯类别，可以从网址中得到，默认为政务要闻"
  },
  "path": "/huizhou/zwgk/:category?"
}
```
