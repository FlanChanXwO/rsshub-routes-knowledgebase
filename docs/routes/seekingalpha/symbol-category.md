# Seeking Alpha - Summary

## Coverage
`index-only`

## Route
- Namespace: `seekingalpha`
- Namespace Name: `Seeking Alpha`
- Route Path: `/:symbol/:category?`
- Route Name: `Summary`
- Example: `/seekingalpha/TSM/transcripts`
- URL: `seekingalpha.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/seekingalpha/index.tsx')`

## Description
| Analysis | News | Transcripts | Press Releases | Related Analysis |
| -------- | ---- | ----------- | -------------- | ---------------- |
| analysis | news | transcripts | press-releases | related-analysis |

## Parameters
- `symbol`: Stock symbol
- `category`: Category, see below, `news` by default


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `seekingalpha.com/symbol/:symbol/:category`
  - `seekingalpha.com/symbol/:symbol/earnings/:category`
- `target`: `/:symbol/:category`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| Analysis | News | Transcripts | Press Releases | Related Analysis |\n| -------- | ---- | ----------- | -------------- | ---------------- |\n| analysis | news | transcripts | press-releases | related-analysis |",
  "example": "/seekingalpha/TSM/transcripts",
  "features": {
    "antiCrawler": true
  },
  "location": "index.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/seekingalpha/index.tsx')",
  "name": "Summary",
  "parameters": {
    "category": "Category, see below, `news` by default",
    "symbol": "Stock symbol"
  },
  "path": "/:symbol/:category?",
  "radar": [
    {
      "source": [
        "seekingalpha.com/symbol/:symbol/:category",
        "seekingalpha.com/symbol/:symbol/earnings/:category"
      ],
      "target": "/:symbol/:category"
    }
  ]
}
```
