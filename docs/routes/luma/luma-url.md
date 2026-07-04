# LuMa - Events

## Coverage
`index-only`

## Route
- Namespace: `luma`
- Namespace Name: `LuMa`
- Route Path: `/luma/:url`
- Route Name: `Events`
- Example: `/luma/yieldnest`
- URL: `lu.ma`
- Language: `_None_`
- Categories: `other`
- Maintainers: `cxheng315`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `url`: LuMa URL


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
  - `lu.ma/:url`
- `target`: `/:url`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/luma/yieldnest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "index.ts",
  "maintainers": [
    "cxheng315"
  ],
  "name": "Events",
  "parameters": {
    "url": "LuMa URL"
  },
  "path": "/:url",
  "radar": [
    {
      "source": [
        "lu.ma/:url"
      ],
      "target": "/:url"
    }
  ],
  "topFeeds": [
    {
      "description": "LangChain Events - Powered by RSSHub",
      "errorAt": "2026-07-02T21:57:52.897Z",
      "errorMessage": "Failed to fetch\n",
      "id": "62716706890373120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://lu.ma/langchain",
      "title": "LangChain Events",
      "type": "feed",
      "url": "rsshub://luma/langchain"
    },
    {
      "description": "The AI Collective - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "265935647087177728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://lu.ma/genai-collective",
      "title": "The AI Collective",
      "type": "feed",
      "url": "rsshub://luma/genai-collective"
    }
  ],
  "url": "lu.ma"
}
```
