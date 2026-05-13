# U.S. Food and Drug Administration - Unknown

## Coverage
`index-only`

## Route
- Namespace: `fda`
- Namespace Name: `U.S. Food and Drug Administration`
- Route Path: `/cdrh/:titleOnly?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `fda.gov/medical-devices/news-events-medical-devices/cdrhnew-news-and-updates`
- Language: `en`
- Categories: `None`
- Maintainers: `None`
- Source Location: `cdrh.ts`
- Source Module: `() => import('@/routes/fda/cdrh.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `fda.gov/medical-devices/news-events-medical-devices/cdrhnew-news-and-updates`
  - `fda.gov/`
- `target`: `/cdrh/:titleOnly`

## Raw JSON
```json
{
  "location": "cdrh.ts",
  "maintainers": [],
  "module": "() => import('@/routes/fda/cdrh.ts')",
  "name": "Unknown",
  "path": "/cdrh/:titleOnly?",
  "radar": [
    {
      "source": [
        "fda.gov/medical-devices/news-events-medical-devices/cdrhnew-news-and-updates",
        "fda.gov/"
      ],
      "target": "/cdrh/:titleOnly"
    }
  ],
  "url": "fda.gov/medical-devices/news-events-medical-devices/cdrhnew-news-and-updates"
}
```
