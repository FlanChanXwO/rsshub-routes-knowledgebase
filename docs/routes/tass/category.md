# Russian News Agency TASS - News

## Coverage
`index-only`

## Route
- Namespace: `tass`
- Namespace Name: `Russian News Agency TASS`
- Route Path: `/:category?`
- Route Name: `News`
- Example: `/tass/politics`
- URL: `tass.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/tass/news.ts')`

## Description
| Russian Politics & Diplomacy | World | Business & Economy | Military & Defense | Science & Space | Emergencies | Society & Culture | Press Review | Sports |
| ---------------------------- | ----- | ------------------ | ------------------ | --------------- | ----------- | ----------------- | ------------ | ------ |
| politics                     | world | economy            | defense            | science         | emergencies | society           | pressreview  | sports |

## Parameters
- `category`: Category, can be found in URL, `politics` by default


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
  - `tass.com/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| Russian Politics & Diplomacy | World | Business & Economy | Military & Defense | Science & Space | Emergencies | Society & Culture | Press Review | Sports |\n| ---------------------------- | ----- | ------------------ | ------------------ | --------------- | ----------- | ----------------- | ------------ | ------ |\n| politics                     | world | economy            | defense            | science         | emergencies | society           | pressreview  | sports |",
  "example": "/tass/politics",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/tass/news.ts')",
  "name": "News",
  "parameters": {
    "category": "Category, can be found in URL, `politics` by default"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "tass.com/:category"
      ],
      "target": "/:category"
    }
  ]
}
```
