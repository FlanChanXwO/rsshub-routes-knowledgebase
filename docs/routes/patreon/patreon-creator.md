# Patreon - Home

## Coverage
`index-only`

## Route
- Namespace: `patreon`
- Namespace Name: `Patreon`
- Route Path: `/patreon/:creator`
- Route Name: `Home`
- Example: `/patreon/straightupsisters`
- URL: `www.patreon.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `feed.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `creator`: Patreon creator id, can be found in the url


## Features
- `requireConfig`: [{"description": "The value of the session_id cookie after logging in to Patreon, required to access paid posts", "name": "PATREON_SESSION_ID", "optional": true}]
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `patreon.com/:creator`
  - `www.patreon.com/cw/:creator`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/patreon/straightupsisters",
  "features": {
    "nsfw": true,
    "requireConfig": [
      {
        "description": "The value of the session_id cookie after logging in to Patreon, required to access paid posts",
        "name": "PATREON_SESSION_ID",
        "optional": true
      }
    ]
  },
  "heat": 12,
  "location": "feed.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Home",
  "parameters": {
    "creator": "Patreon creator id, can be found in the url"
  },
  "path": "/:creator",
  "radar": [
    {
      "source": [
        "patreon.com/:creator",
        "www.patreon.com/cw/:creator"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "Yaoi & Gay NSFW | Fanarts & Original | Not accepting commissions - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "103451624702321664",
      "image": "https://c10.patreonusercontent.com/4/patreon-media/p/campaign/12375285/4dd3ab4d5eb1433d972b076a325d0bce/eyJoIjoxMDgwLCJ3IjoxMDgwfQ%3D%3D/90.png?token-hash=eWOL6m0U8As1A-ZCAin9INHFX2N2EuCdaNX_QXWa94U%3D&token-time=1780099200",
      "ownerUserId": null,
      "siteUrl": "https://www.patreon.com/tianyu6671",
      "title": "tianyu",
      "type": "feed",
      "url": "rsshub://patreon/tianyu6671"
    },
    {
      "description": "AI works - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81524136027649024",
      "image": "https://c10.patreonusercontent.com/4/patreon-media/p/campaign/12359229/aca4ec32602741ba9464516d187dff8a/eyJoIjoxMDgwLCJ3IjoxMDgwfQ%3D%3D/4.png?token-hash=iPgsUQqkdLhOBGJD68W6Cihq9DrHjMq898LmsF8Th4o%3D&token-time=1780099200",
      "ownerUserId": null,
      "siteUrl": "https://www.patreon.com/boys926",
      "title": "boys share",
      "type": "feed",
      "url": "rsshub://patreon/boys926"
    }
  ]
}
```
