# Henan Museum - Special Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `chnmus`
- Namespace Name: `Henan Museum`
- Route Path: `/chnmus/information/exhibition/:type?`
- Route Name: `Special Exhibitions`
- Example: `/chnmus/information/exhibition/special`
- URL: `www.chnmus.net`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `exhibition.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: special（特展详情）. Default: All.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.chnmus.net/ch/information/exhibition/index.html`
- `target`: `/information/exhibition`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/chnmus/information/exhibition/special",
  "heat": 0,
  "location": "exhibition.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Special Exhibitions",
  "parameters": {
    "type": "Exhibition type, supported values: special（特展详情）. Default: All."
  },
  "path": "/information/exhibition/:type?",
  "radar": [
    {
      "source": [
        "www.chnmus.net/ch/information/exhibition/index.html"
      ],
      "target": "/information/exhibition"
    }
  ],
  "topFeeds": []
}
```
