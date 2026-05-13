# ManyVids - Creator Videos

## Coverage
`index-only`

## Route
- Namespace: `manyvids`
- Namespace Name: `ManyVids`
- Route Path: `/profile/vids/:uid`
- Route Name: `Creator Videos`
- Example: `/manyvids/profile/vids/1001213004`
- URL: `www.manyvids.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `video.tsx`
- Source Module: `() => import('@/routes/manyvids/video.tsx')`

## Description
_None_

## Parameters
- `uid`: User ID, can be found in the URL.


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.manyvids.com/Profile/:uid/:handle/Store/*`
  - `www.manyvids.com/Profile/:uid/:handle/Store`

## Raw JSON
```json
{
  "example": "/manyvids/profile/vids/1001213004",
  "features": {
    "nsfw": true
  },
  "location": "video.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/manyvids/video.tsx')",
  "name": "Creator Videos",
  "parameters": {
    "uid": "User ID, can be found in the URL."
  },
  "path": "/profile/vids/:uid",
  "radar": [
    {
      "source": [
        "www.manyvids.com/Profile/:uid/:handle/Store/*",
        "www.manyvids.com/Profile/:uid/:handle/Store"
      ]
    }
  ]
}
```
