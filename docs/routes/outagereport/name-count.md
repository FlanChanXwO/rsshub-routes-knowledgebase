# Outage.Report - Report

## Coverage
`index-only`

## Route
- Namespace: `outagereport`
- Namespace Name: `Outage.Report`
- Route Path: `/:name/:count?`
- Route Name: `Report`
- Example: `/outagereport/ubisoft/5`
- URL: `outage.report`
- Language: `en`
- Categories: `forecast`
- Maintainers: `cxumol, nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/outagereport/index.ts')`

## Description
Please skip the local service area code for `name`, for example `https://outage.report/us/verizon-wireless` to `verizon-wireless`.

## Parameters
- `name`: Service name, spelling format must be consistent with URL
- `count`: Counting threshold, will only be written in RSS if the number of people who report to stop serving is not less than this number


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "description": "Please skip the local service area code for `name`, for example `https://outage.report/us/verizon-wireless` to `verizon-wireless`.",
  "example": "/outagereport/ubisoft/5",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "cxumol",
    "nczitzk"
  ],
  "module": "() => import('@/routes/outagereport/index.ts')",
  "name": "Report",
  "parameters": {
    "count": "Counting threshold, will only be written in RSS if the number of people who report to stop serving is not less than this number",
    "name": "Service name, spelling format must be consistent with URL"
  },
  "path": "/:name/:count?"
}
```
