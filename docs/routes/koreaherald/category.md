# The Korea Herald - News

## Coverage
`index-only`

## Route
- Namespace: `koreaherald`
- Namespace Name: `The Korea Herald`
- Route Path: `/:category{.+}?`
- Route Name: `News`
- Example: `/koreaherald/National`
- URL: `koreaherald.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/koreaherald/index.ts')`

## Description
::: tip
For example, the category for the page https://www.koreaherald.com/Business and https://www.koreaherald.com/Business/Market would be `/Business` and `/Business/Market` respectively. 
:::

## Parameters
- `category`: Category from the path of the URL of the corresponding site, `National` by default


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: false

## Radar
### Rule 1
- `source`:
  - `www.koreaherald.com/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "\n::: tip\nFor example, the category for the page https://www.koreaherald.com/Business and https://www.koreaherald.com/Business/Market would be `/Business` and `/Business/Market` respectively. \n:::\n",
  "example": "/koreaherald/National",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "module": "() => import('@/routes/koreaherald/index.ts')",
  "name": "News",
  "parameters": {
    "category": "Category from the path of the URL of the corresponding site, `National` by default"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.koreaherald.com/:category"
      ],
      "target": "/:category"
    }
  ]
}
```
