# Matters - Latest, heat, essence

## Coverage
`index-only`

## Route
- Namespace: `matters`
- Namespace Name: `Matters`
- Route Path: `/latest/:type?`
- Route Name: `Latest, heat, essence`
- Example: `/matters/latest/heat`
- URL: `matters.town`
- Language: `en`
- Categories: `new-media`
- Maintainers: `xyqfer, Cerebrater, xosdy`
- Source Location: `latest.ts`
- Source Module: `() => import('@/routes/matters/latest.ts')`

## Description
| 最新   | 热门 | 精华    |
| ------ | ---- | ------- |
| latest | heat | essence |

## Parameters
- `uid`: Defaults to latest, see table below


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `matters.town`

## Raw JSON
```json
{
  "description": "| 最新   | 热门 | 精华    |\n| ------ | ---- | ------- |\n| latest | heat | essence |",
  "example": "/matters/latest/heat",
  "location": "latest.ts",
  "maintainers": [
    "xyqfer",
    "Cerebrater",
    "xosdy"
  ],
  "module": "() => import('@/routes/matters/latest.ts')",
  "name": "Latest, heat, essence",
  "parameters": {
    "uid": "Defaults to latest, see table below"
  },
  "path": "/latest/:type?",
  "radar": [
    {
      "source": [
        "matters.town"
      ]
    }
  ]
}
```
