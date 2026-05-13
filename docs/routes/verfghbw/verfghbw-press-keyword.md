# Constitutional Court of Baden-Württemberg (Germany) - Press releases

## Coverage
`index-only`

## Route
- Namespace: `verfghbw`
- Namespace Name: `Constitutional Court of Baden-Württemberg (Germany)`
- Route Path: `/verfghbw/press/:keyword?`
- Route Name: `Press releases`
- Example: `/verfghbw/press`
- URL: `verfgh.baden-wuerttemberg.de/de/presse-und-service/pressemitteilungen/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `quinn-dev`
- Source Location: `press.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "press.ts",
  "maintainers": [
    "quinn-dev"
  ],
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
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "verfgh.baden-wuerttemberg.de/de/presse-und-service/pressemitteilungen/"
}
```
