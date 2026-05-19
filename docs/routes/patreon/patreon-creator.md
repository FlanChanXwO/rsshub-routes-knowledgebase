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
  "heat": 14,
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
      "description": "Creating Erotic Games - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "160927229421421568",
      "image": "https://c10.patreonusercontent.com/4/patreon-media/p/campaign/1718915/cd306e172aa64f2b9c0fcefb033bdd03/eyJoIjoxMDgwLCJ3IjoxMDgwfQ%3D%3D/2.png?token-hash=d5U1PmCVYm72EHp64wKWpyrTXf1gL9s-wUY8dSFgnRM%3D&token-time=1778284800",
      "ownerUserId": null,
      "siteUrl": "https://www.patreon.com/hizorgames",
      "title": "Hizor Games",
      "type": "feed",
      "url": "rsshub://patreon/hizorgames"
    },
    {
      "description": "Creating Artworks with AI - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126027477923179520",
      "image": "https://c10.patreonusercontent.com/4/patreon-media/p/campaign/12912371/799d4e2072584883a7a1d44a7cffe58a/eyJoIjoxMDgwLCJ3IjoxMDgwfQ%3D%3D/15.jpg?token-hash=3bzG1WE6PrlM5sxwpScJn9DiQBIdpgAc1T_ntqEEuZ4%3D&token-time=1780099200",
      "ownerUserId": null,
      "siteUrl": "https://www.patreon.com/aikira758",
      "title": "AIKira",
      "type": "feed",
      "url": "rsshub://patreon/aikira758"
    }
  ]
}
```
