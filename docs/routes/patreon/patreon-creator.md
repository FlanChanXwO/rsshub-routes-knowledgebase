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
      "description": "Yaoi/Gay AI artworks. (NSFW) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "107187512318883840",
      "image": "https://c10.patreonusercontent.com/4/patreon-media/p/campaign/12481247/88cace64bc5f4c1581085f33ed4e684d/eyJoIjoxMDgwLCJ3IjoxMDgwfQ%3D%3D/7.png?token-hash=_O_4LmFdnZEUvLwvv-kTbI1tWZMi-XUjO665lA64KGA%3D&token-time=1780185600",
      "ownerUserId": null,
      "siteUrl": "https://www.patreon.com/Valarant",
      "title": "Valarant",
      "type": "feed",
      "url": "rsshub://patreon/Valarant"
    },
    {
      "description": "老雷｜投資人 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "248768060163265536",
      "image": "https://c10.patreonusercontent.com/4/patreon-media/p/campaign/7369407/b41e9121743d43228402964949ffc646/eyJoIjoxMDgwLCJ3IjoxMDgwfQ%3D%3D/6.jpeg?token-hash=vAGokXNu3gVVhr8ltQVb3K_c93ErzU4m8Ic_l_xpgGw%3D&token-time=1778284800",
      "ownerUserId": null,
      "siteUrl": "https://www.patreon.com/themarketmemo",
      "title": "交易筆記 · TheMarketMemo",
      "type": "feed",
      "url": "rsshub://patreon/themarketmemo"
    }
  ]
}
```
