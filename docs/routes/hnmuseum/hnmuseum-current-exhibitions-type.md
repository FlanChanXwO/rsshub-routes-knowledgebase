# Hunan Museum - Current Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `hnmuseum`
- Namespace Name: `Hunan Museum`
- Route Path: `/hnmuseum/current-exhibitions/:type?`
- Route Name: `Current Exhibitions`
- Example: `/hnmuseum/current-exhibitions/special`
- URL: `www.hnmuseum.com/zh-hans`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `exhibitions.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: special（临时展览 special+temporary）. Default: All exhibitions.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.hnmuseum.com/zh-hans/content/当前展览－基本陈列`
- `target`: `/current-exhibitions`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/hnmuseum/current-exhibitions/special",
  "heat": 0,
  "location": "exhibitions.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Current Exhibitions",
  "parameters": {
    "type": "Exhibition type, supported values: special（临时展览 special+temporary）. Default: All exhibitions."
  },
  "path": "/current-exhibitions/:type?",
  "radar": [
    {
      "source": [
        "www.hnmuseum.com/zh-hans/content/当前展览－基本陈列"
      ],
      "target": "/current-exhibitions"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
