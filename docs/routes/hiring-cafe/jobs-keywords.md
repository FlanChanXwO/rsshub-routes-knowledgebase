# HiringCafe - Jobs

## Coverage
`index-only`

## Route
- Namespace: `hiring.cafe`
- Namespace Name: `HiringCafe`
- Route Path: `/jobs/:keywords`
- Route Name: `Jobs`
- Example: `/hiring.cafe/jobs/sustainability`
- URL: `hiring.cafe`
- Language: `_None_`
- Categories: `other`
- Maintainers: `mintyfrankie`
- Source Location: `jobs.tsx`
- Source Module: `() => import('@/routes/hiring.cafe/jobs.tsx')`

## Description
_None_

## Parameters
- `keywords`: Keywords to search for


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
  - `hiring.cafe`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/hiring.cafe/jobs/sustainability",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jobs.tsx",
  "maintainers": [
    "mintyfrankie"
  ],
  "module": "() => import('@/routes/hiring.cafe/jobs.tsx')",
  "name": "Jobs",
  "parameters": {
    "keywords": "Keywords to search for"
  },
  "path": "/jobs/:keywords",
  "radar": [
    {
      "source": [
        "hiring.cafe"
      ]
    }
  ]
}
```
