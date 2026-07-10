# Hebei Museum - Temporary Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `hebeimuseum`
- Namespace Name: `Hebei Museum`
- Route Path: `/hebeimuseum/list/:type?`
- Route Name: `Temporary Exhibitions`
- Example: `/hebeimuseum/list/special`
- URL: `www.hebeimuseum.org.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `list.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: special（临时展览详情）. Default: All.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.hebeimuseum.org.cn/list-26-1.html`
- `target`: `/list`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/hebeimuseum/list/special",
  "heat": 0,
  "location": "list.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Temporary Exhibitions",
  "parameters": {
    "type": "Exhibition type, supported values: special（临时展览详情）. Default: All."
  },
  "path": "/list/:type?",
  "radar": [
    {
      "source": [
        "www.hebeimuseum.org.cn/list-26-1.html"
      ],
      "target": "/list"
    }
  ],
  "topFeeds": []
}
```
