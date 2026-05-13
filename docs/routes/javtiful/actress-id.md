# Javtiful - Actress

## Coverage
`index-only`

## Route
- Namespace: `javtiful`
- Namespace Name: `Javtiful`
- Route Path: `/actress/:id`
- Route Name: `Actress`
- Example: `/javtiful/actress/akari-tsumugi`
- URL: `javtiful.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `huanfe1`
- Source Location: `actress.ts`
- Source Module: `() => import('@/routes/javtiful/actress.ts')`

## Description
_None_

## Parameters
- `id`: Actress name


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `javtiful.com/actress/:id`
  - `javtiful.com/actress/:id/*`
- `target`: `/actress/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/javtiful/actress/akari-tsumugi",
  "features": {
    "nsfw": true
  },
  "location": "actress.ts",
  "maintainers": [
    "huanfe1"
  ],
  "module": "() => import('@/routes/javtiful/actress.ts')",
  "name": "Actress",
  "parameters": {
    "id": "Actress name"
  },
  "path": "/actress/:id",
  "radar": [
    {
      "source": [
        "javtiful.com/actress/:id",
        "javtiful.com/actress/:id/*"
      ],
      "target": "/actress/:id"
    }
  ]
}
```
