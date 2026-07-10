# BBC - Sport

## Coverage
`index-only`

## Route
- Namespace: `bbc`
- Namespace Name: `BBC`
- Route Path: `/bbc/sport/:sport`
- Route Name: `Sport`
- Example: `/bbc/sport/formula1`
- URL: `bbc.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `sport.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `sport`: The sport to fetch news for, can be found in the URL.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.bbc.com/sport/:sport`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/bbc/sport/formula1",
  "heat": 0,
  "location": "sport.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Sport",
  "parameters": {
    "sport": "The sport to fetch news for, can be found in the URL."
  },
  "path": "/sport/:sport",
  "radar": [
    {
      "source": [
        "www.bbc.com/sport/:sport"
      ]
    }
  ],
  "topFeeds": []
}
```
