# ELSEVIER - Unknown

## Coverage
`index-only`

## Route
- Namespace: `elsevier`
- Namespace Name: `ELSEVIER`
- Route Path: `/:journal/:issue`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `www.sciencedirect.com`
- Language: `en`
- Categories: `None`
- Maintainers: `None`
- Source Location: `issue.ts`
- Source Module: `() => import('@/routes/elsevier/issue.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.sciencedirect.com/journal/:journal/*`
- `target`: `/:journal`

## Raw JSON
```json
{
  "location": "issue.ts",
  "maintainers": [],
  "module": "() => import('@/routes/elsevier/issue.ts')",
  "name": "Unknown",
  "path": [
    "/:journal/vol/:issue",
    "/:journal/:issue"
  ],
  "radar": [
    {
      "source": [
        "www.sciencedirect.com/journal/:journal/*"
      ],
      "target": "/:journal"
    }
  ]
}
```
