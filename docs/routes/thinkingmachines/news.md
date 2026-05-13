# Thinking Machines Lab - News

## Coverage
`index-only`

## Route
- Namespace: `thinkingmachines`
- Namespace Name: `Thinking Machines Lab`
- Route Path: `/news`
- Route Name: `News`
- Example: `/thinkingmachines/news`
- URL: `thinkingmachines.ai/news`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `w3nhao`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/thinkingmachines/news.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false

## Radar
### Rule 1
- `source`:
  - `thinkingmachines.ai/news`
  - `thinkingmachines.ai/news/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/thinkingmachines/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false
  },
  "location": "news.ts",
  "maintainers": [
    "w3nhao"
  ],
  "module": "() => import('@/routes/thinkingmachines/news.ts')",
  "name": "News",
  "path": "/news",
  "radar": [
    {
      "source": [
        "thinkingmachines.ai/news",
        "thinkingmachines.ai/news/"
      ],
      "target": "/news"
    }
  ],
  "url": "thinkingmachines.ai/news"
}
```
