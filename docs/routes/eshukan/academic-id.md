# 万维书刊网 - 学术资讯

## Coverage
`index-only`

## Route
- Namespace: `eshukan`
- Namespace Name: `万维书刊网`
- Route Path: `/academic/:id?`
- Route Name: `学术资讯`
- Example: `/eshukan/academic/1`
- URL: `www.eshukan.com`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `academic.ts`
- Source Module: `() => import('@/routes/eshukan/academic.ts')`

## Description
::: tip
  若订阅 [期刊动态](https://www.eshukan.com/academic/index.aspx?cid=1)，网址为 `https://www.eshukan.com/academic/index.aspx?cid=1`。截取 `https://www.eshukan.com/academic/index.aspx?cid=` 到末尾的部分 `1` 作为参数填入，此时路由为 [`/eshukan/academic/1`](https://rsshub.app/eshukan/academic/1)。
:::

## Parameters
- `category`: 栏目 id，默认为 `1`，即期刊动态，可在对应栏目页 URL 中找到


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
  - `www.eshukan.com/academic/index.aspx`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "::: tip\n  若订阅 [期刊动态](https://www.eshukan.com/academic/index.aspx?cid=1)，网址为 `https://www.eshukan.com/academic/index.aspx?cid=1`。截取 `https://www.eshukan.com/academic/index.aspx?cid=` 到末尾的部分 `1` 作为参数填入，此时路由为 [`/eshukan/academic/1`](https://rsshub.app/eshukan/academic/1)。\n:::\n    ",
  "example": "/eshukan/academic/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "academic.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/eshukan/academic.ts')",
  "name": "学术资讯",
  "parameters": {
    "category": "栏目 id，默认为 `1`，即期刊动态，可在对应栏目页 URL 中找到"
  },
  "path": "/academic/:id?",
  "radar": [
    {
      "source": [
        "www.eshukan.com/academic/index.aspx"
      ]
    }
  ],
  "url": "www.eshukan.com"
}
```
