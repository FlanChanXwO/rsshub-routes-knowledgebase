# 中国军网 - 中国人民解放军专业技术人才网

## Coverage
`index-only`

## Route
- Namespace: `81`
- Namespace Name: `中国军网`
- Route Path: `/81rc/:category{.+}?`
- Route Name: `中国人民解放军专业技术人才网`
- Example: `/81/81rc/sy/gzdt_210283`
- URL: `81rc.81.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `81rc/index.ts`
- Source Module: `() => import('@/routes/81/81rc/index.ts')`

## Description
::: tip
  若订阅 [工作动态](https://81rc.81.cn/sy/gzdt_210283)，网址为 `https://81rc.81.cn/sy/gzdt_210283`。截取 `https://81rc.81.cn/` 到末尾的部分 `sy/gzdt_210283` 作为参数填入，此时路由为 [`/81/81rc/sy/gzdt_210283`](https://rsshub.app/81/81rc/sy/gzdt_210283)。
:::

## Parameters
- `category`: 分类，默认为 `sy/gzdt_210283`，即工作动态，可在对应分类页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `81rc.81.cn/:category`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n  若订阅 [工作动态](https://81rc.81.cn/sy/gzdt_210283)，网址为 `https://81rc.81.cn/sy/gzdt_210283`。截取 `https://81rc.81.cn/` 到末尾的部分 `sy/gzdt_210283` 作为参数填入，此时路由为 [`/81/81rc/sy/gzdt_210283`](https://rsshub.app/81/81rc/sy/gzdt_210283)。\n:::\n  ",
  "example": "/81/81rc/sy/gzdt_210283",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "81rc/index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/81/81rc/index.ts')",
  "name": "中国人民解放军专业技术人才网",
  "parameters": {
    "category": "分类，默认为 `sy/gzdt_210283`，即工作动态，可在对应分类页 URL 中找到"
  },
  "path": "/81rc/:category{.+}?",
  "radar": [
    {
      "source": [
        "81rc.81.cn/:category"
      ]
    }
  ],
  "url": "81rc.81.cn"
}
```
