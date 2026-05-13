# American Institute of Physics - Journal

## Coverage
`index-only`

## Route
- Namespace: `aip`
- Namespace Name: `American Institute of Physics`
- Route Path: `/:pub/:jrn`
- Route Name: `Journal`
- Example: `/aip/aapt/ajp`
- URL: `pubs.aip.org`
- Language: `en`
- Categories: `journal`
- Maintainers: `Derekmini, auto-bot-ty`
- Source Location: `journal.ts`
- Source Module: `() => import('@/routes/aip/journal.ts')`

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
  "description": "Refer to the URL format `pubs.aip.org/:pub/:jrn`\n\n::: tip\n  More jounals can be found in [AIP Publications](https://publishing.aip.org/publications/find-the-right-journal).\n:::",
  "example": "/aip/aapt/ajp",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "location": "journal.ts",
  "maintainers": [
    "Derekmini",
    "auto-bot-ty"
  ],
  "module": "() => import('@/routes/aip/journal.ts')",
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
  ]
}
```
