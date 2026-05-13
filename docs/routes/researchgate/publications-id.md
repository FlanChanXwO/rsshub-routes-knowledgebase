# ResearchGate - Unknown

## Coverage
`index-only`

## Route
- Namespace: `researchgate`
- Namespace Name: `ResearchGate`
- Route Path: `/publications/:id`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `researchgate.net`
- Language: `en`
- Categories: `None`
- Maintainers: `None`
- Source Location: `publications.ts`
- Source Module: `() => import('@/routes/researchgate/publications.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `researchgate.net/profile/:username`
- `target`: `/publications/:username`

## Raw JSON
```json
{
  "location": "publications.ts",
  "maintainers": [],
  "module": "() => import('@/routes/researchgate/publications.ts')",
  "name": "Unknown",
  "path": "/publications/:id",
  "radar": [
    {
      "source": [
        "researchgate.net/profile/:username"
      ],
      "target": "/publications/:username"
    }
  ]
}
```
