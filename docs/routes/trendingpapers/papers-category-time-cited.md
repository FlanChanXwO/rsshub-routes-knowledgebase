# Trending Papers - Trending Papers on arXiv

## Coverage
`index-only`

## Route
- Namespace: `trendingpapers`
- Namespace Name: `Trending Papers`
- Route Path: `/papers/:category?/:time?/:cited?`
- Route Name: `Trending Papers on arXiv`
- Example: `/trendingpapers/papers`
- URL: `trendingpapers.com`
- Language: `en`
- Categories: `journal`
- Maintainers: `CookiePieWw`
- Source Location: `papers.ts`
- Source Module: `() => import('@/routes/trendingpapers/papers.ts')`

## Description
_None_

## Parameters
- `category`: Category of papers, can be found in URL. `All categories` by default.
- `time`: Time like `24 hours` to specify the duration of ranking, can be found in URL. `Since beginning` by default.
- `cited`: Cited or uncited papers, can be found in URL. `Cited and uncited papers` by default.


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
    "journal"
  ],
  "example": "/trendingpapers/papers",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "papers.ts",
  "maintainers": [
    "CookiePieWw"
  ],
  "module": "() => import('@/routes/trendingpapers/papers.ts')",
  "name": "Trending Papers on arXiv",
  "parameters": {
    "category": "Category of papers, can be found in URL. `All categories` by default.",
    "cited": "Cited or uncited papers, can be found in URL. `Cited and uncited papers` by default.",
    "time": "Time like `24 hours` to specify the duration of ranking, can be found in URL. `Since beginning` by default."
  },
  "path": "/papers/:category?/:time?/:cited?"
}
```
