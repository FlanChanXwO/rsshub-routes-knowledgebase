# Gadget Flow - Category

## Coverage
`index-only`

## Route
- Namespace: `thegadgetflow`
- Namespace Name: `Gadget Flow`
- Route Path: `/thegadgetflow/:category?`
- Route Name: `Category`
- Example: `/thegadgetflow/cool-gadgets-gifts`
- URL: `thegadgetflow.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `EthanWng97`
- Source Location: `rss.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: category name, can be found in url


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
  - `thegadgetflow.com/categories/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/thegadgetflow/cool-gadgets-gifts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "rss.tsx",
  "maintainers": [
    "EthanWng97"
  ],
  "name": "Category",
  "parameters": {
    "category": "category name, can be found in url"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "thegadgetflow.com/categories/:category"
      ],
      "target": "/:category"
    }
  ],
  "topFeeds": [
    {
      "description": "Gadget Flow - Powered by RSSHub",
      "errorAt": "2026-05-23T00:27:08.675Z",
      "errorMessage": "[GET] \"https://thegadgetflow.com/wp-json/wp/v2/posts?per_page=10&_embed\": 403 Forbidden\n",
      "id": "186353461477534720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://thegadgetflow.com/",
      "title": "Gadget Flow",
      "type": "feed",
      "url": "rsshub://thegadgetflow"
    }
  ]
}
```
