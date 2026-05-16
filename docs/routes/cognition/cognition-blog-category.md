# cognition - Blog

## Coverage
`index-only`

## Route
- Namespace: `cognition`
- Namespace Name: `cognition`
- Route Path: `/cognition/blog/:category?`
- Route Name: `Blog`
- Example: `/cognition/blog`
- URL: `cognition.ai/blog`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `Loongphy, ttttmr`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category name, e.g., Research, Tutorials


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
  - `cognition.ai/blog/1`
  - `cognition.ai/blog/:category/1`
- `target`: `/blog/:category?`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/cognition/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 3,
  "location": "blog.ts",
  "maintainers": [
    "Loongphy",
    "ttttmr"
  ],
  "name": "Blog",
  "parameters": {
    "category": "Category name, e.g., Research, Tutorials"
  },
  "path": "/blog/:category?",
  "radar": [
    {
      "source": [
        "cognition.ai/blog/1",
        "cognition.ai/blog/:category/1"
      ],
      "target": "/blog/:category?"
    }
  ],
  "topFeeds": [
    {
      "description": "The latest news and updates from Cognition - Powered by RSSHub",
      "errorAt": "2026-05-14T22:46:37.414Z",
      "errorMessage": "[GET] \"https://cognition.ai/blog/1\": 404 Not Found\n",
      "id": "207531896770078720",
      "image": "https://cognition.ai/assets/images/cover.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cognition.ai/blog/1",
      "title": "Cognition | Blog",
      "type": "feed",
      "url": "rsshub://cognition/blog"
    }
  ],
  "url": "cognition.ai/blog",
  "view": 0
}
```
