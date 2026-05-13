# Javtiful - Channel

## Coverage
`index-only`

## Route
- Namespace: `javtiful`
- Namespace Name: `Javtiful`
- Route Path: `/channel/:id`
- Route Name: `Channel`
- Example: `/javtiful/channel/madonna`
- URL: `javtiful.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `huanfe1`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/javtiful/channel.ts')`

## Description
_None_

## Parameters
- `id`: Channel name


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `javtiful.com/channel/:id`
  - `javtiful.com/channel/:id/*`
- `target`: `/channel/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/javtiful/channel/madonna",
  "features": {
    "nsfw": true
  },
  "location": "channel.ts",
  "maintainers": [
    "huanfe1"
  ],
  "module": "() => import('@/routes/javtiful/channel.ts')",
  "name": "Channel",
  "parameters": {
    "id": "Channel name"
  },
  "path": "/channel/:id",
  "radar": [
    {
      "source": [
        "javtiful.com/channel/:id",
        "javtiful.com/channel/:id/*"
      ],
      "target": "/channel/:id"
    }
  ]
}
```
