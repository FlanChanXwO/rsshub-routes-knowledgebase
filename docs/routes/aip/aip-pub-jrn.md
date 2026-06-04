# American Institute of Physics - Journal

## Coverage
`index-only`

## Route
- Namespace: `aip`
- Namespace Name: `American Institute of Physics`
- Route Path: `/aip/:pub/:jrn`
- Route Name: `Journal`
- Example: `/aip/aapt/ajp`
- URL: `pubs.aip.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `Derekmini, auto-bot-ty`
- Source Location: `journal.ts`
- Source Module: `_None_`

## Description
Refer to the URL format `pubs.aip.org/:pub/:jrn`

::: tip
More jounals can be found in [AIP Publications](https://publishing.aip.org/publications/find-the-right-journal).
:::

## Parameters
- `pub`: Publisher id
- `jrn`: Journal id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `pubs.aip.org/:pub/:jrn`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "Refer to the URL format `pubs.aip.org/:pub/:jrn`\n\n::: tip\nMore jounals can be found in [AIP Publications](https://publishing.aip.org/publications/find-the-right-journal).\n:::",
  "example": "/aip/aapt/ajp",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "heat": 4,
  "location": "journal.ts",
  "maintainers": [
    "Derekmini",
    "auto-bot-ty"
  ],
  "name": "Journal",
  "parameters": {
    "jrn": "Journal id",
    "pub": "Publisher id"
  },
  "path": "/:pub/:jrn",
  "radar": [
    {
      "source": [
        "pubs.aip.org/:pub/:jrn"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2026-05-07T07:11:15.739Z",
      "errorMessage": "[GET] \"https://pubs.aip.org/journal/jap/issue\": 403 Forbidden\n",
      "id": "1100438337916633112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://aip/journal/jap"
    },
    {
      "description": null,
      "errorAt": "2026-05-07T16:08:31.514Z",
      "errorMessage": "[GET] \"https://pubs.aip.org/journal/apl/issue\": 403 Forbidden\n",
      "id": "1100438337916633111",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://aip/journal/apl"
    }
  ]
}
```
