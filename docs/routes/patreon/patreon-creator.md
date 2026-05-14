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
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Creating Christian Apologetic Videos - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "210727018282671128",
      "image": "https://c10.patreonusercontent.com/4/patreon-media/p/campaign/117296/187572e9f7ae4ecc84821947b944548c/eyJoIjoxMDgwLCJ3IjoxMDgwfQ%3D%3D/2.jpg?token-hash=wOM4bknUMvDzMRgkAo4IdseT6aaNA2Jhk0nlZJb6bqk%3D&token-time=1779926400",
      "ownerUserId": null,
      "siteUrl": "https://www.patreon.com/inspiringphilosophy",
      "title": "Inspiring Philosophy",
      "type": "feed",
      "url": "rsshub://patreon/inspiringphilosophy"
    },
    {
      "description": "Creating videos, blog posts, and a podcast - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "210727018282671124",
      "image": "https://c10.patreonusercontent.com/4/patreon-media/p/campaign/386335/5bfb46da077a4253a77bb46e612a0178/eyJoIjoxMDgwLCJ3IjoxMDgwfQ%3D%3D/2.jpeg?token-hash=HDLiQ5dBiar6xeQ-oUb3Zk_zc90TLSTvfAtNuDXeMeE%3D&token-time=1779840000",
      "ownerUserId": null,
      "siteUrl": "https://www.patreon.com/capturingchristianity",
      "title": "Capturing Christianity",
      "type": "feed",
      "url": "rsshub://patreon/capturingchristianity"
    }
  ]
}
```
