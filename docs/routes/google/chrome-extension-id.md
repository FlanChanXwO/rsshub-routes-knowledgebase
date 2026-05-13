# Google - Extension Update

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/chrome/extension/:id`
- Route Name: `Extension Update`
- Example: `/google/chrome/extension/kefjpfngnndepjbopdmoebkipbgkggaa`
- URL: `www.google.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `DIYgod`
- Source Location: `extension.ts`
- Source Module: `() => import('@/routes/google/extension.ts')`

## Description
_None_

## Parameters
- `id`: Extension id, can be found in extension url


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
  - `chromewebstore.google.com/detail/:name/:id`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/google/chrome/extension/kefjpfngnndepjbopdmoebkipbgkggaa",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "extension.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/google/extension.ts')",
  "name": "Extension Update",
  "parameters": {
    "id": "Extension id, can be found in extension url"
  },
  "path": "/chrome/extension/:id",
  "radar": [
    {
      "source": [
        "chromewebstore.google.com/detail/:name/:id"
      ]
    }
  ]
}
```
