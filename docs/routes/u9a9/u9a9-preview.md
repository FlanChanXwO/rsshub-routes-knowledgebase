# U9A9 - Search

## Coverage
`index-only`

## Route
- Namespace: `u9a9`
- Namespace Name: `U9A9`
- Route Path: `/u9a9/:preview?`
- Route Name: `Search`
- Example: `/u9a9/search/新片速递`
- URL: `u9a9.com/`
- Language: `_None_`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `u9a9.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/u9a9/search/新片速递",
  "heat": 10,
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Search",
  "path": [
    "/:preview?",
    "/search/:keyword/:preview?"
  ],
  "radar": [
    {
      "source": [
        "u9a9.com/"
      ],
      "target": ""
    }
  ],
  "topFeeds": [
    {
      "description": "U9A9 - Powered by RSSHub",
      "errorAt": "2026-05-20T00:33:54.579Z",
      "errorMessage": "Failed to fetch\n",
      "id": "75777045788956696",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://u9a9.com/",
      "title": "U9A9",
      "type": "feed",
      "url": "rsshub://u9a9/1"
    },
    {
      "description": "U9A9 - Powered by RSSHub",
      "errorAt": "2026-05-20T01:03:20.909Z",
      "errorMessage": "Failed query: select \"id\", \"guid\", \"media\" from \"entries\" \"entries\" where \"entries\".\"feed_id\" = $1\nparams: 69603631408900096",
      "id": "69603631408900096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://u9a9.com/",
      "title": "U9A9",
      "type": "feed",
      "url": "rsshub://u9a9"
    }
  ],
  "url": "u9a9.com/"
}
```
