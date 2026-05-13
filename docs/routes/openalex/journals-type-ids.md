# OpenAlex - Works

## Coverage
`index-only`

## Route
- Namespace: `openalex`
- Namespace Name: `OpenAlex`
- Route Path: `/:journals/:type?/:ids?`
- Route Name: `Works`
- Example: `/openalex/s64187185/subfield/2604`
- URL: `openalex.org`
- Language: `en`
- Categories: `journal`
- Maintainers: `emdoe`
- Source Location: `works.ts`
- Source Module: `() => import('@/routes/openalex/works.ts')`

## Description
Get recent scientific publications from OpenAlex filtered by journal and optionally by topic classification (last 2 weeks).

Examples:
- /openalex/s64187185 - All works from a journal (no topic filter)
- /openalex/s64187185/subfield/2604 - Filter by subfield
- /openalex/s64187185|s123456/topic/T10001|T10002 - Filter by topic with multiple journals
- /openalex/s64187185/field/19 - Filter by field
- /openalex/s64187185/domain/1 - Filter by domain

## Parameters
- `journals`: Pipe-separated journal source IDs (e.g., s64187185|s123456789)
- `type`: Optional filter type: subfield, topic, field, or domain
- `ids`: Optional pipe-separated filter IDs matching the type (e.g., 2604|2605 for subfields)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `openalex.org/works`
- `target`: `/:journals/:type?/:ids?`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "Get recent scientific publications from OpenAlex filtered by journal and optionally by topic classification (last 2 weeks).\n\nExamples:\n- /openalex/s64187185 - All works from a journal (no topic filter)\n- /openalex/s64187185/subfield/2604 - Filter by subfield\n- /openalex/s64187185|s123456/topic/T10001|T10002 - Filter by topic with multiple journals\n- /openalex/s64187185/field/19 - Filter by field\n- /openalex/s64187185/domain/1 - Filter by domain",
  "example": "/openalex/s64187185/subfield/2604",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "works.ts",
  "maintainers": [
    "emdoe"
  ],
  "module": "() => import('@/routes/openalex/works.ts')",
  "name": "Works",
  "parameters": {
    "ids": "Optional pipe-separated filter IDs matching the type (e.g., 2604|2605 for subfields)",
    "journals": "Pipe-separated journal source IDs (e.g., s64187185|s123456789)",
    "type": "Optional filter type: subfield, topic, field, or domain"
  },
  "path": "/:journals/:type?/:ids?",
  "radar": [
    {
      "source": [
        "openalex.org/works"
      ],
      "target": "/:journals/:type?/:ids?"
    }
  ],
  "url": "openalex.org"
}
```
