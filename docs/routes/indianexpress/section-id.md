# The Indian Express - Section

## Coverage
`index-only`

## Route
- Namespace: `indianexpress`
- Namespace Name: `The Indian Express`
- Route Path: `/section/:id{.+}?`
- Route Name: `Section`
- Example: `/indianexpress/section/explained`
- URL: `indianexpress.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `section.ts`
- Source Module: `() => import('@/routes/indianexpress/section.ts')`

## Description
:::tip
To subscribe to [Section](https://indianexpress.com/), where the source URL is `https://indianexpress.com/`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/indianexpress/section/explained`](https://rsshub.app/indianexpress/section/explained).
:::

## Parameters
- `id`: {"description": "Section ID, `trending` as Trending by default"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `indianexpress.com/section/:id`
- `target`: `/section/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": ":::tip\nTo subscribe to [Section](https://indianexpress.com/), where the source URL is `https://indianexpress.com/`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/indianexpress/section/explained`](https://rsshub.app/indianexpress/section/explained).\n:::\n",
  "example": "/indianexpress/section/explained",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "section.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/indianexpress/section.ts')",
  "name": "Section",
  "parameters": {
    "id": {
      "description": "Section ID, `trending` as Trending by default"
    }
  },
  "path": "/section/:id{.+}?",
  "radar": [
    {
      "source": [
        "indianexpress.com/section/:id"
      ],
      "target": "/section/:id"
    }
  ],
  "url": "indianexpress.com",
  "view": 0
}
```
