# Constitutional Court of Baden-Württemberg (Germany) - Press releases

## Coverage
`index-only`

## Route
- Namespace: `verfghbw`
- Namespace Name: `Constitutional Court of Baden-Württemberg (Germany)`
- Route Path: `/press/:keyword?`
- Route Name: `Press releases`
- Example: `/verfghbw/press`
- URL: `verfgh.baden-wuerttemberg.de/de/presse-und-service/pressemitteilungen/`
- Language: `de`
- Categories: `government`
- Maintainers: `quinn-dev`
- Source Location: `press.ts`
- Source Module: `() => import('@/routes/verfghbw/press.ts')`

## Description
_None_

## Parameters
- `keyword`: Keyword


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
  - `verfgh.baden-wuerttemberg.de/de/presse-und-service/pressemitteilungen/`
- `target`: `/press`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/verfghbw/press",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "press.ts",
  "maintainers": [
    "quinn-dev"
  ],
  "module": "() => import('@/routes/verfghbw/press.ts')",
  "name": "Press releases",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/press/:keyword?",
  "radar": [
    {
      "source": [
        "verfgh.baden-wuerttemberg.de/de/presse-und-service/pressemitteilungen/"
      ],
      "target": "/press"
    }
  ],
  "url": "verfgh.baden-wuerttemberg.de/de/presse-und-service/pressemitteilungen/"
}
```
