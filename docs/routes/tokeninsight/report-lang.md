# TokenInsight - Research

## Coverage
`index-only`

## Route
- Namespace: `tokeninsight`
- Namespace Name: `TokenInsight`
- Route Path: `/report/:lang?`
- Route Name: `Research`
- Example: `/tokeninsight/report/en`
- URL: `tokeninsight.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `None`
- Source Location: `report.ts`
- Source Module: `() => import('@/routes/tokeninsight/report.ts')`

## Description
Language:

| Chinese | English |
| ------- | ------- |
| zh      | en      |

## Parameters
- `lang`: Language, see below, Chinese by default


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
  - `tokeninsight.com/:lang/report`
- `target`: `/report/:lang`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Language:\n\n| Chinese | English |\n| ------- | ------- |\n| zh      | en      |",
  "example": "/tokeninsight/report/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "report.ts",
  "maintainers": [],
  "module": "() => import('@/routes/tokeninsight/report.ts')",
  "name": "Research",
  "parameters": {
    "lang": "Language, see below, Chinese by default"
  },
  "path": "/report/:lang?",
  "radar": [
    {
      "source": [
        "tokeninsight.com/:lang/report"
      ],
      "target": "/report/:lang"
    }
  ]
}
```
