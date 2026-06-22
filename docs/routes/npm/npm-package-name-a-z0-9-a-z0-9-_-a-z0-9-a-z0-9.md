# NPM - Package

## Coverage
`index-only`

## Route
- Namespace: `npm`
- Namespace Name: `NPM`
- Route Path: `/npm/package/:name{(@[a-z0-9-~][a-z0-9-._~]*/)?[a-z0-9-~][a-z0-9-._~]*}`
- Route Name: `Package`
- Example: `/npm/package/rsshub`
- URL: `npmjs.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `Fatpandac`
- Source Location: `package.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.npmjs.com/package/:name`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/npm/package/rsshub",
  "heat": 11,
  "location": "package.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "Package",
  "path": "/package/:name{(@[a-z0-9-~][a-z0-9-._~]*/)?[a-z0-9-~][a-z0-9-._~]*}",
  "radar": [
    {
      "source": [
        "www.npmjs.com/package/:name"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "homebridge-miot - npm - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "92451467824140288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.npmjs.com/package/homebridge-miot",
      "title": "homebridge-miot - npm",
      "type": "feed",
      "url": "rsshub://npm/package/homebridge-miot"
    },
    {
      "description": "@antfu/eslint-config - npm - Powered by RSSHub",
      "errorAt": "2026-06-20T20:29:29.987Z",
      "errorMessage": "Failed to fetch\n",
      "id": "175925709458059264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.npmjs.com/package/@antfu/eslint-config",
      "title": "@antfu/eslint-config - npm",
      "type": "feed",
      "url": "rsshub://npm/package/@antfu/eslint-config"
    }
  ]
}
```
