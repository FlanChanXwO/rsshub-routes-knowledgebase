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
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Lead Editor: Esteban Rossi-Hansberg Editors: John Asker, Andrew Atkeson, Leonardo Bursztyn, Gabriel Carroll, Melissa Dell, Rachel Griffith, David Lagakos, John List, Guido Lorenzoni, Francesca Molinari, Luigi Pistaferri, Bruno Strulovici, Christopher Walters - Powered by RSSHub",
      "errorAt": "2026-04-18T15:56:33.654Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "74375516441159680",
      "image": "https://www.journals.uchicago.edu/na101/home/literatum/publisher/uchicago/journals/content/jpe/2026/jpe.2026.134.issue-4/jpe.2026.134.issue-4/20260406/jpe.2026.134.issue-4.cover.png",
      "ownerUserId": null,
      "siteUrl": "https://www.journals.uchicago.edu/toc/jpe/current",
      "title": "Journal of Political Economy | Vol 134, No 4",
      "type": "feed",
      "url": "rsshub://uchicago/journals/current/jpe"
    },
    {
      "description": "Editors: Mary Evans, Teevrat Garg, Arik Levinson, and Andrew Plantinga Published for the Association of Environmental and Resource Economists - Powered by RSSHub",
      "errorAt": "2026-04-19T02:52:43.307Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "75184870917658624",
      "image": "https://www.journals.uchicago.edu/na101/home/literatum/publisher/uchicago/journals/covergifs/jaere/cover.gif",
      "ownerUserId": null,
      "siteUrl": "https://www.journals.uchicago.edu/toc/jaere/current",
      "title": "Journal of the Association of Environmental and Resource Economists | Vol 13, No 3",
      "type": "feed",
      "url": "rsshub://uchicago/journals/current/jaere"
    }
  ]
}
```
