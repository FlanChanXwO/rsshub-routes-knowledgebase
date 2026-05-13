# GIS Reports - 报告

## Coverage
`index-only`

## Route
- Namespace: `gisreportsonline`
- Namespace Name: `GIS Reports`
- Route Path: `/:path{.*}`
- Route Name: `报告`
- Example: `/gis/c/security-challenges/`
- URL: `www.gisreportsonline.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `dzx-dzx`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/gisreportsonline/index.ts')`

## Description
_None_

## Parameters
- `path`: 包含"Reports"页面下的路径


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.gisreportsonline.com`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/gis/c/security-challenges/",
  "location": "index.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "module": "() => import('@/routes/gisreportsonline/index.ts')",
  "name": "报告",
  "parameters": {
    "path": "包含\"Reports\"页面下的路径"
  },
  "path": "/:path{.*}",
  "radar": [
    {
      "source": [
        "www.gisreportsonline.com"
      ]
    }
  ]
}
```
