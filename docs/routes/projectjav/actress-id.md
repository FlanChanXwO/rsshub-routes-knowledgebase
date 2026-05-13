# ProjectJAV - Actress

## Coverage
`index-only`

## Route
- Namespace: `projectjav`
- Namespace Name: `ProjectJAV`
- Route Path: `/actress/:id`
- Route Name: `Actress`
- Example: `/projectjav/actress/rima-arai-22198`
- URL: `projectjav.com/`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `Exat1979`
- Source Location: `actress.ts`
- Source Module: `() => import('@/routes/projectjav/actress.ts')`

## Description
Fetches the latest movies from a specific actress page on ProjectJAV.

## Parameters
- `id`: Actress ID or slug, can be found in the actress page URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `projectjav.com/actress/:id`
- `target`: `/actress/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "Fetches the latest movies from a specific actress page on ProjectJAV.",
  "example": "/projectjav/actress/rima-arai-22198",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "actress.ts",
  "maintainers": [
    "Exat1979"
  ],
  "module": "() => import('@/routes/projectjav/actress.ts')",
  "name": "Actress",
  "parameters": {
    "id": "Actress ID or slug, can be found in the actress page URL"
  },
  "path": "/actress/:id",
  "radar": [
    {
      "source": [
        "projectjav.com/actress/:id"
      ],
      "target": "/actress/:id"
    }
  ],
  "url": "projectjav.com/"
}
```
