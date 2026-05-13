# Cara - Likes

## Coverage
`index-only`

## Route
- Namespace: `cara`
- Namespace Name: `Cara`
- Route Path: `/likes/:user`
- Route Name: `Likes`
- Example: `/cara/likes/fengz`
- URL: `cara.app`
- Language: `en`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `likes.ts`
- Source Module: `() => import('@/routes/cara/likes.ts')`

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
- `target`: `/likes/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/cara/likes/fengz",
  "location": "likes.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/cara/likes.ts')",
  "name": "Likes",
  "parameters": {
    "user": "username"
  },
  "path": [
    "/likes/:user"
  ],
  "radar": [
    {
      "source": [
        "cara.app/:user",
        "cara.app/:user/*"
      ],
      "target": "/likes/:user"
    }
  ]
}
```
