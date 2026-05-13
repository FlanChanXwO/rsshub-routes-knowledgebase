# Civitai - User Article

## Coverage
`index-only`

## Route
- Namespace: `civitai`
- Namespace Name: `Civitai`
- Route Path: `/user/:username/articles`
- Route Name: `User Article`
- Example: `/civitai/user/Chenkin/articles`
- URL: `civitai.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/civitai/user.ts')`

## Description
_None_

## Parameters
- `username`: Username


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `civitai.com/user/:username`
  - `civitai.com/user/:username/articles`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/civitai/user/Chenkin/articles",
  "features": {
    "nsfw": true
  },
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/civitai/user.ts')",
  "name": "User Article",
  "parameters": {
    "username": "Username"
  },
  "path": "/user/:username/articles",
  "radar": [
    {
      "source": [
        "civitai.com/user/:username",
        "civitai.com/user/:username/articles"
      ]
    }
  ]
}
```
