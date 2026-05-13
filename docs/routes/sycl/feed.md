# SYCL - Feeds

## Coverage
`index-only`

## Route
- Namespace: `sycl`
- Namespace Name: `SYCL`
- Route Path: `/:feed?`
- Route Name: `Feeds`
- Example: `/sycl/news`
- URL: `sycl.tech`
- Language: `en`
- Categories: `programming`
- Maintainers: `mocusez`
- Source Location: `feeds.ts`
- Source Module: `() => import('@/routes/sycl/feeds.ts')`

## Description
|  Events  | News |    Research Paper     |  Videos  |
| :----: | :--: | :-------------: | :----: |
| events | news | research_papers | videos |

## Parameters
- `feed`: Feed source, defaults to news, references https://feeds.sycl.tech/


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
    "programming"
  ],
  "description": "|  Events  | News |    Research Paper     |  Videos  |\n| :----: | :--: | :-------------: | :----: |\n| events | news | research_papers | videos |",
  "example": "/sycl/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "feeds.ts",
  "maintainers": [
    "mocusez"
  ],
  "module": "() => import('@/routes/sycl/feeds.ts')",
  "name": "Feeds",
  "parameters": {
    "feed": "Feed source, defaults to news, references https://feeds.sycl.tech/"
  },
  "path": "/:feed?"
}
```
