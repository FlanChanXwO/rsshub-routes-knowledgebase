# Mozilla - Add-ons Update

## Coverage
`index-only`

## Route
- Namespace: `firefox`
- Namespace Name: `Mozilla`
- Route Path: `/firefox/addons/:id`
- Route Name: `Add-ons Update`
- Example: `/firefox/addons/rsshub-radar`
- URL: `monitor.firefox.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `DIYgod`
- Source Location: `addons.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Add-ons id, can be found in add-ons url


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
  - `addons.mozilla.org/:lang/firefox/addon/:id/versions`
  - `addons.mozilla.org/:lang/firefox/addon/:id`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/firefox/addons/rsshub-radar",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "addons.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Add-ons Update",
  "parameters": {
    "id": "Add-ons id, can be found in add-ons url"
  },
  "path": "/addons/:id",
  "radar": [
    {
      "source": [
        "addons.mozilla.org/:lang/firefox/addon/:id/versions",
        "addons.mozilla.org/:lang/firefox/addon/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
