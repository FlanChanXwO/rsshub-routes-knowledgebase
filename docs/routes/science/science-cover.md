# Science Magazine - Cover Story

## Coverage
`index-only`

## Route
- Namespace: `science`
- Namespace Name: `Science Magazine`
- Route Path: `/science/cover`
- Route Name: `Cover Story`
- Example: `/science/cover`
- URL: `science.org/`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
- Source Location: `cover.tsx`
- Source Module: `_None_`

## Description
Subscribe to the cover images of Science journals, and get the latest publication updates in time.

Including 'Science', 'Science Advances', 'Science Immunology', 'Science Robotics', 'Science Signaling' and 'Science Translational Medicine'.

## Parameters
_None_


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
  - `science.org/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "Subscribe to the cover images of Science journals, and get the latest publication updates in time.\n\nIncluding 'Science', 'Science Advances', 'Science Immunology', 'Science Robotics', 'Science Signaling' and 'Science Translational Medicine'.",
  "example": "/science/cover",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "cover.tsx",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "name": "Cover Story",
  "parameters": {},
  "path": "/cover",
  "radar": [
    {
      "source": [
        "science.org/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-05-06T15:43:08.758Z",
      "errorMessage": "[GET] \"https://www.science.org/journals\": 403 Forbidden\n",
      "id": "142517145679905798",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://science/cover"
    }
  ],
  "url": "science.org/"
}
```
