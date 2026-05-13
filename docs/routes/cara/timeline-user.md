# Cara - Timeline

## Coverage
`index-only`

## Route
- Namespace: `cara`
- Namespace Name: `Cara`
- Route Path: `/timeline/:user`
- Route Name: `Timeline`
- Example: `/cara/timeline/fengz`
- URL: `cara.app`
- Language: `en`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `timeline.ts`
- Source Module: `() => import('@/routes/cara/timeline.ts')`

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
- `target`: `/timeline/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/cara/timeline/fengz",
  "location": "timeline.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/cara/timeline.ts')",
  "name": "Timeline",
  "parameters": {
    "user": "username"
  },
  "path": [
    "/timeline/:user"
  ],
  "radar": [
    {
      "source": [
        "cara.app/:user",
        "cara.app/:user/*"
      ],
      "target": "/timeline/:user"
    }
  ]
}
```
