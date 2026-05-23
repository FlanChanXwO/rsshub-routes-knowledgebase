# Academia - interest

## Coverage
`index-only`

## Route
- Namespace: `academia`
- Namespace Name: `Academia`
- Route Path: `/academia/topic/:interest`
- Route Name: `interest`
- Example: `/academia/topic/Urban_History`
- URL: `academia.edu`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `K33k0, cscnk52`
- Source Location: `topics.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `interest`: interest


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `academia.edu/Documents/in/:interest`
- `target`: `/topic/:interest`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/academia/topic/Urban_History",
  "heat": 441,
  "location": "topics.ts",
  "maintainers": [
    "K33k0",
    "cscnk52"
  ],
  "name": "interest",
  "parameters": {
    "interest": "interest"
  },
  "path": "/topic/:interest",
  "radar": [
    {
      "source": [
        "academia.edu/Documents/in/:interest"
      ],
      "target": "/topic/:interest"
    }
  ],
  "topFeeds": [
    {
      "description": "academia.edu | Artificial_Intelligence documents - Powered by RSSHub",
      "errorAt": "2025-05-28T17:44:40.339Z",
      "errorMessage": "[GET] \"https://www.academia.edu/Documents/in/Artificial_Intelligence\": 403 Forbidden\n",
      "id": "69620974134739968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://academia.edu/Documents/in/Artificial_Intelligence",
      "title": "academia.edu | Artificial_Intelligence documents",
      "type": "feed",
      "url": "rsshub://academia/topic/Artificial_Intelligence"
    },
    {
      "description": "academia.edu | Machine_Learning documents - Powered by RSSHub",
      "errorAt": "2025-05-28T17:36:24.584Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "69620407260983296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://academia.edu/Documents/in/Machine_Learning",
      "title": "academia.edu | Machine_Learning documents",
      "type": "feed",
      "url": "rsshub://academia/topic/Machine_Learning"
    }
  ],
  "url": "academia.edu"
}
```
