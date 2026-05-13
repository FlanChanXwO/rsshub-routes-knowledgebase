# MacUpdate - Update

## Coverage
`index-only`

## Route
- Namespace: `macupdate`
- Namespace Name: `MacUpdate`
- Route Path: `/app/:appId/:appSlug?`
- Route Name: `Update`
- Example: `/macupdate/app/11942`
- URL: `macupdate.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `TonyRL`
- Source Location: `app.ts`
- Source Module: `() => import('@/routes/macupdate/app.ts')`

## Description
_None_

## Parameters
- `appId`: Application unique ID, can be found in URL
- `appSlug`: Application slug, can be found in URL


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
  - `macupdate.com/app/mac/:appId/:appSlug`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/macupdate/app/11942",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "app.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/macupdate/app.ts')",
  "name": "Update",
  "parameters": {
    "appId": "Application unique ID, can be found in URL",
    "appSlug": "Application slug, can be found in URL"
  },
  "path": "/app/:appId/:appSlug?",
  "radar": [
    {
      "source": [
        "macupdate.com/app/mac/:appId/:appSlug"
      ]
    }
  ]
}
```
