# Mozilla - Add-ons Update

## Coverage
`index-only`

## Route
- Namespace: `firefox`
- Namespace Name: `Mozilla`
- Route Path: `/addons/:id`
- Route Name: `Add-ons Update`
- Example: `/firefox/addons/rsshub-radar`
- URL: `monitor.firefox.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `DIYgod`
- Source Location: `addons.ts`
- Source Module: `() => import('@/routes/firefox/addons.ts')`

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
  "location": "addons.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/firefox/addons.ts')",
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
  ]
}
```
