# Wikipedia - Current Events

## Coverage
`index-only`

## Route
- Namespace: `wikipedia`
- Namespace Name: `Wikipedia`
- Route Path: `/current-events/:includeToday?`
- Route Name: `Current Events`
- Example: `/wikipedia/current-events`
- URL: `en.wikipedia.org`
- Language: `en`
- Categories: `new-media`
- Maintainers: `aavanian`
- Source Location: `current-events.ts`
- Source Module: `() => import('@/routes/wikipedia/current-events.ts')`

## Description
Wikipedia Portal: Current events - Latest news and events from the past 7 days

## Parameters
- `includeToday`: {"default": "auto", "description": "Include current day events (may be incomplete early in the day)", "options": [{"label": "Auto (include after 18:00 UTC)", "value": "auto"}, {"label": "Always include current day", "value": "always"}, {"label": "Never include current day", "value": "never"}, {"label": "Include after specific UTC hour (0-23)", "value": "0-23"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `en.wikipedia.org/wiki/Portal:Current_events`
- `target`: `/wikipedia/current-events`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Wikipedia Portal: Current events - Latest news and events from the past 7 days",
  "example": "/wikipedia/current-events",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "current-events.ts",
  "maintainers": [
    "aavanian"
  ],
  "module": "() => import('@/routes/wikipedia/current-events.ts')",
  "name": "Current Events",
  "parameters": {
    "includeToday": {
      "default": "auto",
      "description": "Include current day events (may be incomplete early in the day)",
      "options": [
        {
          "label": "Auto (include after 18:00 UTC)",
          "value": "auto"
        },
        {
          "label": "Always include current day",
          "value": "always"
        },
        {
          "label": "Never include current day",
          "value": "never"
        },
        {
          "label": "Include after specific UTC hour (0-23)",
          "value": "0-23"
        }
      ]
    }
  },
  "path": "/current-events/:includeToday?",
  "radar": [
    {
      "source": [
        "en.wikipedia.org/wiki/Portal:Current_events"
      ],
      "target": "/wikipedia/current-events"
    }
  ]
}
```
