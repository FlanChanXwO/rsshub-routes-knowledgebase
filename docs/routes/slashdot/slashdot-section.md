# Slashdot - News

## Coverage
`index-only`

## Route
- Namespace: `slashdot`
- Namespace Name: `Slashdot`
- Route Path: `/slashdot/:section?`
- Route Name: `News`
- Example: `/slashdot`
- URL: `slashdot.org`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `section`: Section name, can be found in the URL host, leave empty for the main page


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `slashdot.org`
### Rule 2
- `source`:
  - `devices.slashdot.org`
- `target`: `/devices`
### Rule 3
- `source`:
  - `build.slashdot.org`
- `target`: `/build`
### Rule 4
- `source`:
  - `entertainment.slashdot.org`
- `target`: `/entertainment`
### Rule 5
- `source`:
  - `technology.slashdot.org`
- `target`: `/technology`
### Rule 6
- `source`:
  - `science.slashdot.org`
- `target`: `/science`
### Rule 7
- `source`:
  - `yro.slashdot.org`
- `target`: `/yro`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/slashdot",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "News",
  "parameters": {
    "section": "Section name, can be found in the URL host, leave empty for the main page"
  },
  "path": "/:section?",
  "radar": [
    {
      "source": [
        "slashdot.org"
      ]
    },
    {
      "source": [
        "devices.slashdot.org"
      ],
      "target": "/devices"
    },
    {
      "source": [
        "build.slashdot.org"
      ],
      "target": "/build"
    },
    {
      "source": [
        "entertainment.slashdot.org"
      ],
      "target": "/entertainment"
    },
    {
      "source": [
        "technology.slashdot.org"
      ],
      "target": "/technology"
    },
    {
      "source": [
        "science.slashdot.org"
      ],
      "target": "/science"
    },
    {
      "source": [
        "yro.slashdot.org"
      ],
      "target": "/yro"
    }
  ],
  "topFeeds": []
}
```
