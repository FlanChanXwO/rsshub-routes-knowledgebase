# Podwise - Episodes

## Coverage
`index-only`

## Route
- Namespace: `podwise`
- Namespace Name: `Podwise`
- Route Path: `/explore/:type`
- Route Name: `Episodes`
- Example: `/podwise/explore/latest`
- URL: `podwise.ai`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `lyling`
- Source Location: `episodes.ts`
- Source Module: `() => import('@/routes/podwise/episodes.ts')`

## Description
_None_

## Parameters
- `type`: latest or all episodes.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `podwise.ai/explore/:type`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/podwise/explore/latest",
  "location": "episodes.ts",
  "maintainers": [
    "lyling"
  ],
  "module": "() => import('@/routes/podwise/episodes.ts')",
  "name": "Episodes",
  "parameters": {
    "type": "latest or all episodes."
  },
  "path": "/explore/:type",
  "radar": [
    {
      "source": [
        "podwise.ai/explore/:type"
      ]
    }
  ]
}
```
