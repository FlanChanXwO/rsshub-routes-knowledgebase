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
      "errorAt": null,
      "errorMessage": null,
      "id": "62716706890373120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://lu.ma/langchain",
      "title": "LangChain Events",
      "type": "feed",
      "url": "rsshub://luma/langchain"
    },
    {
      "description": "Deep Tech Week - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "265966907590378496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://lu.ma/deep-tech-week",
      "title": "Deep Tech Week",
      "type": "feed",
      "url": "rsshub://luma/deep-tech-week"
    }
  ],
  "url": "lu.ma"
}
```
