# MacMenuBar - Recently

## Coverage
`index-only`

## Route
- Namespace: `macmenubar`
- Namespace Name: `MacMenuBar`
- Route Path: `/macmenubar/recently/:category?`
- Route Name: `Recently`
- Example: `/macmenubar/recently/developer-apps,system-tools`
- URL: `macmenubar.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `5upernova-heng`
- Source Location: `recently.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category path name, seperate by comma, default is all categories. Category path name can be found in url


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
    "blog"
  ],
  "example": "/macmenubar/recently/developer-apps,system-tools",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "recently.ts",
  "maintainers": [
    "5upernova-heng"
  ],
  "name": "Recently",
  "parameters": {
    "category": "Category path name, seperate by comma, default is all categories. Category path name can be found in url"
  },
  "path": "/recently/:category?",
  "topFeeds": [
    {
      "description": "Recent Posts | MacMenuBar.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56446382044379136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://macmenubar.com/recently-added/",
      "title": "Recent Posts | MacMenuBar.com",
      "type": "feed",
      "url": "rsshub://macmenubar/recently"
    },
    {
      "description": "Recent Posts | MacMenuBar.com - Powered by RSSHub",
      "errorAt": "2026-02-26T14:17:23.668Z",
      "errorMessage": "e.tag_info.map is not a function\n",
      "id": "76813788023884800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://macmenubar.com/recently-added/",
      "title": "Recent Posts | MacMenuBar.com",
      "type": "feed",
      "url": "rsshub://macmenubar/recently/developer-apps,system-tools"
    }
  ]
}
```
