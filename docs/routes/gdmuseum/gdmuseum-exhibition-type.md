# Guangdong Museum - Current Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `gdmuseum`
- Namespace Name: `Guangdong Museum`
- Route Path: `/gdmuseum/exhibition/:type?`
- Route Name: `Current Exhibitions`
- Example: `/gdmuseum/exhibition/temp`
- URL: `gdmuseum.org.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `exhibition.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: temp(临时展览), default: All exhibitions.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.gdmuseum.org.cn/col9/list`
- `target`: `/exhibition`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/gdmuseum/exhibition/temp",
  "heat": 0,
  "location": "exhibition.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Current Exhibitions",
  "parameters": {
    "type": "Exhibition type, supported values: temp(临时展览), default: All exhibitions."
  },
  "path": "/exhibition/:type?",
  "radar": [
    {
      "source": [
        "www.gdmuseum.org.cn/col9/list"
      ],
      "target": "/exhibition"
    }
  ],
  "topFeeds": []
}
```
