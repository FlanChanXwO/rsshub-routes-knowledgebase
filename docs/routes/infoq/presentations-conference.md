# InfoQ 中文 - Presentations

## Coverage
`index-only`

## Route
- Namespace: `infoq`
- Namespace Name: `InfoQ 中文`
- Route Path: `/presentations/:conference?`
- Route Name: `Presentations`
- Example: `/infoq/presentations`
- URL: `www.infoq.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `presentations.ts`
- Source Module: `() => import('@/routes/infoq/presentations.ts')`

## Description
::: tip
  If you subscribe to [InfoQ Live Jan 2024](https://www.infoq.com/infoq-live-jan-2024/presentations/)，where the URL is `https://www.infoq.com/infoq-live-jan-2024/presentations/`, extract the part `https://www.infoq.com/` to the end, which is `/presentations/`, and use it as the parameter to fill in. Therefore, the route will be [`/infoq/presentations/infoq-live-jan-2024`](https://rsshub.app/infoq/presentations/infoq-live-jan-2024).
:::

## Parameters
- `conference`: Conference, all by default, can be found in URL


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
  - `www.infoq.com/presentations`
  - `www.infoq.com/:conference/presentations`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "::: tip\n  If you subscribe to [InfoQ Live Jan 2024](https://www.infoq.com/infoq-live-jan-2024/presentations/)，where the URL is `https://www.infoq.com/infoq-live-jan-2024/presentations/`, extract the part `https://www.infoq.com/` to the end, which is `/presentations/`, and use it as the parameter to fill in. Therefore, the route will be [`/infoq/presentations/infoq-live-jan-2024`](https://rsshub.app/infoq/presentations/infoq-live-jan-2024).\n:::\n    ",
  "example": "/infoq/presentations",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "presentations.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/infoq/presentations.ts')",
  "name": "Presentations",
  "parameters": {
    "conference": "Conference, all by default, can be found in URL"
  },
  "path": "/presentations/:conference?",
  "radar": [
    {
      "source": [
        "www.infoq.com/presentations",
        "www.infoq.com/:conference/presentations"
      ]
    }
  ],
  "url": "www.infoq.com"
}
```
