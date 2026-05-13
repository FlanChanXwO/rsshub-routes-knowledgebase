# The Economist - Global Business Review

## Coverage
`index-only`

## Route
- Namespace: `economist`
- Namespace Name: `The Economist`
- Route Path: `/global-business-review/:language?`
- Route Name: `Global Business Review`
- Example: `/economist/global-business-review/cn-en`
- URL: `businessreview.global/`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `prnake`
- Source Location: `global-business-review.ts`
- Source Module: `() => import('@/routes/economist/global-business-review.ts')`

## Description
_None_

## Parameters
- `language`: Language, `en`, `cn`, `tw` are supported, support multiple options, default to cn-en


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
  - `businessreview.global/`
- `target`: `/global-business-review`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/economist/global-business-review/cn-en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "global-business-review.ts",
  "maintainers": [
    "prnake"
  ],
  "module": "() => import('@/routes/economist/global-business-review.ts')",
  "name": "Global Business Review",
  "parameters": {
    "language": "Language, `en`, `cn`, `tw` are supported, support multiple options, default to cn-en"
  },
  "path": "/global-business-review/:language?",
  "radar": [
    {
      "source": [
        "businessreview.global/"
      ],
      "target": "/global-business-review"
    }
  ],
  "url": "businessreview.global/"
}
```
