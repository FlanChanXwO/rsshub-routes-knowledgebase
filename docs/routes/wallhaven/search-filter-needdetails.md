# wallhaven - Search

## Coverage
`index-only`

## Route
- Namespace: `wallhaven`
- Namespace Name: `wallhaven`
- Route Path: `/search/:filter?/:needDetails?`
- Route Name: `Search`
- Example: `/wallhaven/search/categories=110&purity=110&sorting=date_added&order=desc`
- URL: `wallhaven.cc/`
- Language: `en`
- Categories: `picture`
- Maintainers: `nczitzk, Fatpandac`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/wallhaven/index.ts')`

## Description
::: tip
  Subscribe pages starting with `https://wallhaven.cc/search`, fill the text after `?` as `filter` in the route. The following is an example:

  The text after `?` is `q=id%3A711&sorting=random&ref=fp&seed=8g0dgd` for [Wallpaper Search: #landscape - wallhaven.cc](https://wallhaven.cc/search?q=id%3A711&sorting=random&ref=fp&seed=8g0dgd), so the route is [/wallhaven/q=id%3A711&sorting=random&ref=fp&seed=8g0dgd](https://rsshub.app/wallhaven/q=id%3A711&sorting=random&ref=fp&seed=8g0dgd)
:::

## Parameters
- `filter`: Filter, empty by default
- `needDetails`: Need Details, `true`/`yes` as yes, no by default


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
  - `wallhaven.cc/`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "::: tip\n  Subscribe pages starting with `https://wallhaven.cc/search`, fill the text after `?` as `filter` in the route. The following is an example:\n\n  The text after `?` is `q=id%3A711&sorting=random&ref=fp&seed=8g0dgd` for [Wallpaper Search: #landscape - wallhaven.cc](https://wallhaven.cc/search?q=id%3A711&sorting=random&ref=fp&seed=8g0dgd), so the route is [/wallhaven/q=id%3A711&sorting=random&ref=fp&seed=8g0dgd](https://rsshub.app/wallhaven/q=id%3A711&sorting=random&ref=fp&seed=8g0dgd)\n:::",
  "example": "/wallhaven/search/categories=110&purity=110&sorting=date_added&order=desc",
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
    "nczitzk",
    "Fatpandac"
  ],
  "module": "() => import('@/routes/wallhaven/index.ts')",
  "name": "Search",
  "parameters": {
    "filter": "Filter, empty by default",
    "needDetails": "Need Details, `true`/`yes` as yes, no by default"
  },
  "path": [
    "/search/:filter?/:needDetails?",
    "/:filter?/:needDetails?"
  ],
  "radar": [
    {
      "source": [
        "wallhaven.cc/"
      ]
    }
  ],
  "url": "wallhaven.cc/"
}
```
