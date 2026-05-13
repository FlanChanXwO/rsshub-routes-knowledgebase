# ELSEVIER - Unknown

## Coverage
`index-only`

## Route
- Namespace: `elsevier`
- Namespace Name: `ELSEVIER`
- Route Path: `/elsevier/:journal/latest`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `www.sciencedirect.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `None`
- Source Location: `journal.ts`
- Source Module: `_None_`

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
  "categories": [
    "other"
  ],
  "heat": 0,
  "location": "journal.ts",
  "maintainers": [],
  "name": "Unknown",
  "path": [
    "/:journal/latest",
    "/:journal"
  ],
  "radar": [
    {
      "source": [
        "www.sciencedirect.com/journal/:journal/*"
      ],
      "target": "/:journal"
    }
  ],
  "topFeeds": []
}
```
