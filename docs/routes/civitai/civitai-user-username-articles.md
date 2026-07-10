# Civitai - User Article

## Coverage
`index-only`

## Route
- Namespace: `civitai`
- Namespace Name: `Civitai`
- Route Path: `/civitai/user/:username/articles`
- Route Name: `User Article`
- Example: `/civitai/user/Chenkin/articles`
- URL: `civitai.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
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
  ],
  "topFeeds": []
}
```
