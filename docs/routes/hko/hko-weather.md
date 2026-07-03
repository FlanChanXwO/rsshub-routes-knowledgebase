# Hong Kong Observatory - Current Weather Report

## Coverage
`index-only`

## Route
- Namespace: `hko`
- Namespace Name: `Hong Kong Observatory`
- Route Path: `/hko/weather`
- Route Name: `Current Weather Report`
- Example: `/hko/weather`
- URL: `www.weather.gov.hk/en/wxinfo/currwx/current.htm`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `calpa`
- Source Location: `weather.ts`
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
  - `www.weather.gov.hk/en/wxinfo/currwx/current.htm`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/hko/weather",
  "heat": 5,
  "location": "weather.ts",
  "maintainers": [
    "calpa"
  ],
  "name": "Current Weather Report",
  "path": "/weather",
  "radar": [
    {
      "source": [
        "www.weather.gov.hk/en/wxinfo/currwx/current.htm"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "provided by the Hong Kong Observatory: Wed, 01 Jul 2026 18:02:00 GMT - Powered by RSSHub",
      "errorAt": "2026-07-02T03:02:52.373Z",
      "errorMessage": "Failed query: select \"id\", \"guid\", \"media\" from \"entries\" \"entries\" where \"entries\".\"feed_id\" = $1\nparams: 69176555091531776",
      "id": "69176555091531776",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.weather.gov.hk/en/wxinfo/currwx/current.htm",
      "title": "Current Weather Report",
      "type": "feed",
      "url": "rsshub://hko/weather"
    }
  ],
  "url": "www.weather.gov.hk/en/wxinfo/currwx/current.htm"
}
```
