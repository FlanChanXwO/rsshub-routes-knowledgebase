# The University of Chicago Press: Journals - Current Issue

## Coverage
`index-only`

## Route
- Namespace: `uchicago`
- Namespace Name: `The University of Chicago Press: Journals`
- Route Path: `/uchicago/journals/current/:journal`
- Route Name: `Current Issue`
- Example: `/uchicago/journals/current/jpe`
- URL: `journals.uchicago.edu`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `TonyRL`
- Source Location: `current.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `journal`: Journal id, can be found in URL. [Browse journals by title](https://www.journals.uchicago.edu/action/showPublications)


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
  - `journals.uchicago.edu/toc/:journal/current`
  - `journals.uchicago.edu/journal/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/uchicago/journals/current/jpe",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "current.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Current Issue",
  "parameters": {
    "journal": "Journal id, can be found in URL. [Browse journals by title](https://www.journals.uchicago.edu/action/showPublications)"
  },
  "path": "/journals/current/:journal",
  "radar": [
    {
      "source": [
        "journals.uchicago.edu/toc/:journal/current",
        "journals.uchicago.edu/journal/:journal"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "Lead Editor: Esteban Rossi-Hansberg Editors: John Asker, Andrew Atkeson, Leonardo Bursztyn, Gabriel Carroll, Melissa Dell, David Lagakos, Guido Lorenzoni, Francesca Molinari, Luigi Pistaferri, Bruno Strulovici, Christopher Taber, Christopher Walters - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74375516441159680",
      "image": "https://www.journals.uchicago.edu/cms/asset/531cc51e-483c-44ea-b14d-23dcdcec4b52/jpe.2026.134.issue-6.cover.png",
      "ownerUserId": null,
      "siteUrl": "https://www.journals.uchicago.edu/toc/jpe/current",
      "title": "Journal of Political Economy | Vol 134, No 6",
      "type": "feed",
      "url": "rsshub://uchicago/journals/current/jpe"
    },
    {
      "description": "Editors: Mary Evans, Teevrat Garg, Arik Levinson, and Andrew Plantinga Published for the Association of Environmental and Resource Economists - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75184870917658624",
      "image": "https://www.journals.uchicago.edu/cms/asset/5a38d4f1-b01f-4f38-830f-3718a574ab3d/default_cover.gif",
      "ownerUserId": null,
      "siteUrl": "https://www.journals.uchicago.edu/toc/jaere/current",
      "title": "Journal of the Association of Environmental and Resource Economists | Vol 13, No 4",
      "type": "feed",
      "url": "rsshub://uchicago/journals/current/jaere"
    }
  ]
}
```
