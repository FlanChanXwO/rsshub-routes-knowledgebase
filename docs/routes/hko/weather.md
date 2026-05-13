# Hong Kong Observatory - Current Weather Report

## Coverage
`index-only`

## Route
- Namespace: `hko`
- Namespace Name: `Hong Kong Observatory`
- Route Path: `/weather`
- Route Name: `Current Weather Report`
- Example: `/hko/weather`
- URL: `www.weather.gov.hk/en/wxinfo/currwx/current.htm`
- Language: `zh-HK`
- Categories: `forecast`
- Maintainers: `calpa`
- Source Location: `weather.ts`
- Source Module: `() => import('@/routes/hko/weather.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.weather.gov.hk/en/wxinfo/currwx/current.htm`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/hko/weather",
  "location": "weather.ts",
  "maintainers": [
    "calpa"
  ],
  "module": "() => import('@/routes/hko/weather.ts')",
  "name": "Current Weather Report",
  "path": "/weather",
  "radar": [
    {
      "source": [
        "www.weather.gov.hk/en/wxinfo/currwx/current.htm"
      ]
    }
  ],
  "url": "www.weather.gov.hk/en/wxinfo/currwx/current.htm"
}
```
