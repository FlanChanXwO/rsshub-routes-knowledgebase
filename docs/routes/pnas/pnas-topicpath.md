# Proceedings of The National Academy of Sciences - Unknown

## Coverage
`index-only`

## Route
- Namespace: `pnas`
- Namespace Name: `Proceedings of The National Academy of Sciences`
- Route Path: `/pnas/:topicPath{.+}?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `pnas.org/*topicPath`
- Language: `_None_`
- Categories: `other`
- Maintainers: `None`
- Source Location: `index.tsx`
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
  - `pnas.org/*topicPath`
- `target`: `/:topicPath`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [],
  "name": "Unknown",
  "path": "/:topicPath{.+}?",
  "radar": [
    {
      "source": [
        "pnas.org/*topicPath"
      ],
      "target": "/:topicPath"
    }
  ],
  "topFeeds": [],
  "url": "pnas.org/*topicPath"
}
```
