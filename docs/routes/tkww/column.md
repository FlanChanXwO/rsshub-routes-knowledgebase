# 大公文匯網 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `tkww`
- Namespace Name: `大公文匯網`
- Route Path: `/:column{.+}?`
- Route Name: `新聞`
- Example: `/tkww/hong_kong`
- URL: `www.tkww.hk`
- Language: `zh-HK`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/tkww/index.ts')`

## Description
::: tip
欄目可用`名稱`或對應網頁的`path`，
如 `https://www.tkww.hk/hong_kong` 的欄目可以填`香港`或是`hong_kong`
而 `https://www.tkww.hk/china/shanghai` 的欄目則需填`china/shanghai`
:::

## Parameters
- `column`: 欄目，默認為 home (首頁)


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.tkww.hk/:column`
- `target`: `/:column`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "\n::: tip\n欄目可用`名稱`或對應網頁的`path`，\n如 `https://www.tkww.hk/hong_kong` 的欄目可以填`香港`或是`hong_kong`\n而 `https://www.tkww.hk/china/shanghai` 的欄目則需填`china/shanghai`\n:::",
  "example": "/tkww/hong_kong",
  "features": {
    "antiCrawler": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "module": "() => import('@/routes/tkww/index.ts')",
  "name": "新聞",
  "parameters": {
    "column": "欄目，默認為 home (首頁)"
  },
  "path": "/:column{.+}?",
  "radar": [
    {
      "source": [
        "www.tkww.hk/:column"
      ],
      "target": "/:column"
    }
  ]
}
```
