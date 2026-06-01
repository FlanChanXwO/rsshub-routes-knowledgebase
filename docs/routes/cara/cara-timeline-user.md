# Cara - Timeline

## Coverage
`index-only`

## Route
- Namespace: `cara`
- Namespace Name: `Cara`
- Route Path: `/cara/timeline/:user`
- Route Name: `Timeline`
- Example: `/cara/timeline/fengz`
- URL: `cara.app`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `timeline.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: username


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cara.app/:user`
  - `cara.app/:user/*`
- `target`: `/timeline/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/cara/timeline/fengz",
  "heat": 14,
  "location": "timeline.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "Timeline",
  "parameters": {
    "user": "username"
  },
  "path": [
    "/timeline/:user"
  ],
  "radar": [
    {
      "source": [
        "cara.app/:user",
        "cara.app/:user/*"
      ],
      "target": "/timeline/:user"
    }
  ],
  "topFeeds": [
    {
      "description": "Timeline - Nathan Fowkes - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "131922100224243712",
      "image": "https://cdn.cara.app/production/profiles/e3934f00-3471-41dc-9700-11b58cfd4044/facebook-profile2.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/nathanfowkesart/all",
      "title": "Timeline - Nathan Fowkes",
      "type": "feed",
      "url": "rsshub://cara/timeline/nathanfowkesart"
    },
    {
      "description": "Timeline - Poltorykhina Anna - Powered by RSSHub",
      "errorAt": "2025-11-26T14:15:25.443Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "127388130140915712",
      "image": "https://cdn.cara.app/production/profiles/b17122f7-1148-4a05-a9e4-8be52eb9b189/n5dm6Wqudi8-copy.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/polanya/all",
      "title": "Timeline - Poltorykhina Anna",
      "type": "feed",
      "url": "rsshub://cara/timeline/polanya"
    }
  ]
}
```
