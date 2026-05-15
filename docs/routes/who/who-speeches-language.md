# World Health Organization | WHO - Speeches

## Coverage
`index-only`

## Route
- Namespace: `who`
- Namespace Name: `World Health Organization | WHO`
- Route Path: `/who/speeches/:language?`
- Route Name: `Speeches`
- Example: `/who/speeches`
- URL: `who.int/director-general/speeches`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `speeches.ts`
- Source Module: `_None_`

## Description
Language

| English | العربية | 中文 | Français | Русский | Español | Português |
| ------- | ------- | ---- | -------- | ------- | ------- | --------- |
| en      | ar      | zh   | fr       | ru      | es      | pt        |

## Parameters
- `language`: Language, see below, English by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `who.int/director-general/speeches`
- `target`: `/speeches`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "Language\n\n| English | العربية | 中文 | Français | Русский | Español | Português |\n| ------- | ------- | ---- | -------- | ------- | ------- | --------- |\n| en      | ar      | zh   | fr       | ru      | es      | pt        |",
  "example": "/who/speeches",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "speeches.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Speeches",
  "parameters": {
    "language": "Language, see below, English by default"
  },
  "path": "/speeches/:language?",
  "radar": [
    {
      "source": [
        "who.int/director-general/speeches"
      ],
      "target": "/speeches"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Speeches - WHO - Powered by RSSHub",
      "errorAt": "2025-11-18T18:06:11.847Z",
      "errorMessage": "[GET] \"https://www.who.int/director-general/speeches/detail//who-director-general-s-opening-remarks-at-the-resumed-sixth-meeting-of-the-intergovernmental-working-group-(igwg)-on-the-who-pandemic-agreement-27-april-2026\": 404 Not Found\n[GET] \"https://www.who.int/director-general/speeches/detail//who-director-general-s-opening-remarks-at-the-media-briefing-on-hantavirus---12-may-2026\": 404 Not Found\n",
      "id": "65765818076625920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.who.int/director-general/speeches",
      "title": "Speeches - WHO",
      "type": "feed",
      "url": "rsshub://who/speeches"
    }
  ],
  "url": "who.int/director-general/speeches"
}
```
