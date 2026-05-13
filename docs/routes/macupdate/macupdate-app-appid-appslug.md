# MacUpdate - Update

## Coverage
`index-only`

## Route
- Namespace: `macupdate`
- Namespace Name: `MacUpdate`
- Route Path: `/macupdate/app/:appId/:appSlug?`
- Route Name: `Update`
- Example: `/macupdate/app/11942`
- URL: `macupdate.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `TonyRL`
- Source Location: `app.ts`
- Source Module: `_None_`

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
  "heat": 1,
  "location": "app.ts",
  "maintainers": [
    "TonyRL"
  ],
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
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "<p><em>As of July 2012, Thunderbird has transitioned to a new governance model, with new features being developed by the broader free software and open source community, and security fixes and improvements handled by Mozilla.</em></p> <p><strong>Thunderbird</strong> is a free, open-source, cross-platform e-mail and news (NNTP) client developed by the Mozilla Foundation. The project strategy is modeled after Mozilla Firefox, a project aimed at creating a Web browser.</p> - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56763116661047296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.macupdate.com/",
      "title": "Thunderbird",
      "type": "feed",
      "url": "rsshub://macupdate/app/11942"
    }
  ]
}
```
