# Voronoi - Author Posts

## Coverage
`index-only`

## Route
- Namespace: `voronoiapp`
- Namespace Name: `Voronoi`
- Route Path: `/author/:username`
- Route Name: `Author Posts`
- Example: `/voronoiapp/author/visualcapitalist`
- URL: `voronoiapp.com`
- Language: `en`
- Categories: `picture`
- Maintainers: `Cesaryuan`
- Source Location: `author.ts`
- Source Module: `() => import('@/routes/voronoiapp/author.ts')`

## Description
_None_

## Parameters
- `username`: The username of the author


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.voronoiapp.com/author/:username`
- `target`: `/author/:username`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/voronoiapp/author/visualcapitalist",
  "location": "author.ts",
  "maintainers": [
    "Cesaryuan"
  ],
  "module": "() => import('@/routes/voronoiapp/author.ts')",
  "name": "Author Posts",
  "parameters": {
    "username": "The username of the author"
  },
  "path": "/author/:username",
  "radar": [
    {
      "source": [
        "www.voronoiapp.com/author/:username"
      ],
      "target": "/author/:username"
    }
  ],
  "url": "voronoiapp.com",
  "view": 2
}
```
