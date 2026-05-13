# TiddlyWiki - Releases

## Coverage
`index-only`

## Route
- Namespace: `tiddlywiki`
- Namespace Name: `TiddlyWiki`
- Route Path: `/releases`
- Route Name: `Releases`
- Example: `/tiddlywiki/releases`
- URL: `tiddlywiki.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `p3psi-boo`
- Source Location: `releases.ts`
- Source Module: `() => import('@/routes/tiddlywiki/releases.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `github.com/TiddlyWiki/TiddlyWiki5`
- `target`: `/releases`
### Rule 2
- `source`:
  - `tiddlywiki.com`
- `target`: `/releases`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/tiddlywiki/releases",
  "location": "releases.ts",
  "maintainers": [
    "p3psi-boo"
  ],
  "module": "() => import('@/routes/tiddlywiki/releases.ts')",
  "name": "Releases",
  "path": "/releases",
  "radar": [
    {
      "source": [
        "github.com/TiddlyWiki/TiddlyWiki5"
      ],
      "target": "/releases"
    },
    {
      "source": [
        "tiddlywiki.com"
      ],
      "target": "/releases"
    }
  ],
  "url": "tiddlywiki.com"
}
```
