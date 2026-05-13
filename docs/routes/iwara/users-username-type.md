# iwara - User

## Coverage
`index-only`

## Route
- Namespace: `iwara`
- Namespace Name: `iwara`
- Route Path: `/users/:username/:type?`
- Route Name: `User`
- Example: `/iwara/users/kelpie/video`
- URL: `www.iwara.tv`
- Language: `en`
- Categories: `None`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/iwara/index.ts')`

## Description
_None_

## Parameters
- `username`: username, can find in userpage
- `type`: content type, can be video or image, default is video


## Features
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "example": "/iwara/users/kelpie/video",
  "features": {
    "nsfw": true
  },
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/iwara/index.ts')",
  "name": "User",
  "parameters": {
    "type": "content type, can be video or image, default is video",
    "username": "username, can find in userpage"
  },
  "path": "/users/:username/:type?"
}
```
