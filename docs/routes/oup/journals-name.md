# Oxford University Press - Oxford Academic - Journal

## Coverage
`index-only`

## Route
- Namespace: `oup`
- Namespace Name: `Oxford University Press`
- Route Path: `/journals/:name`
- Route Name: `Oxford Academic - Journal`
- Example: `/oup/journals/adaptation`
- URL: `academic.oup.com/`
- Language: `en`
- Categories: `journal`
- Maintainers: `Fatpandac`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/oup/index.tsx')`

## Description
_None_

## Parameters
- `name`: short name for a journal, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `academic.oup.com/`
  - `academic.oup.com/:name/issue`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/oup/journals/adaptation",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/oup/index.tsx')",
  "name": "Oxford Academic - Journal",
  "parameters": {
    "name": "short name for a journal, can be found in URL"
  },
  "path": "/journals/:name",
  "radar": [
    {
      "source": [
        "academic.oup.com/",
        "academic.oup.com/:name/issue"
      ]
    }
  ],
  "url": "academic.oup.com/"
}
```
