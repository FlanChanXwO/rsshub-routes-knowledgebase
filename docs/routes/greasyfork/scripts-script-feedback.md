# Greasy Fork - Script Feedback

## Coverage
`index-only`

## Route
- Namespace: `greasyfork`
- Namespace Name: `Greasy Fork`
- Route Path: `/scripts/:script/feedback`
- Route Name: `Script Feedback`
- Example: `/greasyfork/scripts/431691-bypass-all-shortlinks/feedback`
- URL: `greasyfork.org`
- Language: `en`
- Categories: `program-update`
- Maintainers: `miles170`
- Source Location: `feedback.ts`
- Source Module: `() => import('@/routes/greasyfork/feedback.ts')`

## Description
_None_

## Parameters
- `script`: Script id, can be found in URL


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
  - `greasyfork.org/:language/scripts/:script/feedback`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/greasyfork/scripts/431691-bypass-all-shortlinks/feedback",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "feedback.ts",
  "maintainers": [
    "miles170"
  ],
  "module": "() => import('@/routes/greasyfork/feedback.ts')",
  "name": "Script Feedback",
  "parameters": {
    "script": "Script id, can be found in URL"
  },
  "path": "/scripts/:script/feedback",
  "radar": [
    {
      "source": [
        "greasyfork.org/:language/scripts/:script/feedback"
      ]
    }
  ]
}
```
