# Science Magazine - First Release

## Coverage
`index-only`

## Route
- Namespace: `science`
- Namespace Name: `Science Magazine`
- Route Path: `/science/early/:journal?`
- Route Name: `First Release`
- Example: `/science/early`
- URL: `science.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
- Source Location: `early.ts`
- Source Module: `_None_`

## Description
*only Science, Science Immunology and Science Translational Medicine have first release*

## Parameters
- `journal`: Short name for a journal


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `science.org/journal/:journal`
  - `science.org/toc/:journal/0/0`
- `target`: `/early/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "*only Science, Science Immunology and Science Translational Medicine have first release*",
  "example": "/science/early",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "heat": 14,
  "location": "early.ts",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "name": "First Release",
  "parameters": {
    "journal": "Short name for a journal"
  },
  "path": "/early/:journal?",
  "radar": [
    {
      "source": [
        "science.org/journal/:journal",
        "science.org/toc/:journal/0/0"
      ],
      "target": "/early/:journal"
    }
  ],
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-01T11:07:38.022Z",
      "errorMessage": "[GET] \"https://www.science.org/toc/science/0/0\": 403 Forbidden\n",
      "id": "151955931879114756",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://science/early"
    }
  ]
}
```
