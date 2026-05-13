# Digital Policy Alert - Activity Tracker

## Coverage
`index-only`

## Route
- Namespace: `digitalpolicyalert`
- Namespace Name: `Digital Policy Alert`
- Route Path: `/activity-tracker/:filters?`
- Route Name: `Activity Tracker`
- Example: `/digitalpolicyalert/activity-tracker`
- URL: `digitalpolicyalert.org`
- Language: `en`
- Categories: `other`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `activity-tracker.ts`
- Source Module: `() => import('@/routes/digitalpolicyalert/activity-tracker.ts')`

## Description
::: tip
To subscribe to [Activity Tracker - International trade](https://digitalpolicyalert.org/activity-tracker?policy=1), where the source URL is `https://digitalpolicyalert.org/activity-tracker?policy=1`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/digitalpolicyalert/activity-tracker/policy=1`](https://rsshub.app/digitalpolicyalert/activity-tracker/policy=1).
:::

## Parameters
- `filter`: {"description": "Filter, all by default"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `digitalpolicyalert.org`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "::: tip\nTo subscribe to [Activity Tracker - International trade](https://digitalpolicyalert.org/activity-tracker?policy=1), where the source URL is `https://digitalpolicyalert.org/activity-tracker?policy=1`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/digitalpolicyalert/activity-tracker/policy=1`](https://rsshub.app/digitalpolicyalert/activity-tracker/policy=1).\n:::\n",
  "example": "/digitalpolicyalert/activity-tracker",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "activity-tracker.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/digitalpolicyalert/activity-tracker.ts')",
  "name": "Activity Tracker",
  "parameters": {
    "filter": {
      "description": "Filter, all by default"
    }
  },
  "path": "/activity-tracker/:filters?",
  "radar": [
    {
      "source": [
        "digitalpolicyalert.org"
      ]
    }
  ],
  "url": "digitalpolicyalert.org",
  "view": 0
}
```
