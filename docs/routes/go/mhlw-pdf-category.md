# JapanGov - PDF

## Coverage
`index-only`

## Route
- Namespace: `go`
- Namespace Name: `JapanGov`
- Route Path: `/mhlw/pdf/:category{.+}?`
- Route Name: `PDF`
- Example: `/go/mhlw/pdf/stf/seisakunitsuite/bunya/houkokusuunosuii`
- URL: `www.mhlw.go.jp`
- Language: `ja`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `mhlw/pdf.ts`
- Source Module: `() => import('@/routes/go/mhlw/pdf.ts')`

## Description
::: tip
  Subscribing to this route will give you access to all PDF files on this page.

  If you subscribe to [新型コロナウイルス感染症の定点当たり報告数の推移](https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/houkokusuunosuii.html)，where the URL is `https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/houkokusuunosuii.html`, extract the part `https://www.mhlw.go.jp/` to the end, which is `.html`, and use it as the parameter to fill in. Therefore, the route will be [`/go/mhlw/stf/seisakunitsuite/bunya/houkokusuunosuii`](https://rsshub.app/go/mhlw/stf/seisakunitsuite/bunya/houkokusuunosuii).
:::

## Parameters
- `category`: Category, `stf/seisakunitsuite/bunya/houkokusuunosuii` as 新型コロナウイルス感染症の定点当たり報告数の推移 by default


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
  - `www.mhlw.go.jp`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n  Subscribing to this route will give you access to all PDF files on this page.\n\n  If you subscribe to [新型コロナウイルス感染症の定点当たり報告数の推移](https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/houkokusuunosuii.html)，where the URL is `https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/houkokusuunosuii.html`, extract the part `https://www.mhlw.go.jp/` to the end, which is `.html`, and use it as the parameter to fill in. Therefore, the route will be [`/go/mhlw/stf/seisakunitsuite/bunya/houkokusuunosuii`](https://rsshub.app/go/mhlw/stf/seisakunitsuite/bunya/houkokusuunosuii).\n:::\n  ",
  "example": "/go/mhlw/pdf/stf/seisakunitsuite/bunya/houkokusuunosuii",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "mhlw/pdf.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/go/mhlw/pdf.ts')",
  "name": "PDF",
  "parameters": {
    "category": "Category, `stf/seisakunitsuite/bunya/houkokusuunosuii` as 新型コロナウイルス感染症の定点当たり報告数の推移 by default"
  },
  "path": "/mhlw/pdf/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.mhlw.go.jp"
      ]
    }
  ],
  "url": "www.mhlw.go.jp"
}
```
