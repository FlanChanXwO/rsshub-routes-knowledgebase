# THBWiki - Calendar

## Coverage
`index-only`

## Route
- Namespace: `thwiki`
- Namespace Name: `THBWiki`
- Route Path: `/thwiki/calendar/:before?/:after?`
- Route Name: `Calendar`
- Example: `/thwiki/calendar`
- URL: `thwiki.cc/`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `aether17`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `before`: From how many days ago (default 30)
- `after`: To how many days after (default 30)


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
  - `thwiki.cc/`
  - `thwiki.cc/日程表`
- `target`: `/calendar`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/thwiki/calendar",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "index.ts",
  "maintainers": [
    "aether17"
  ],
  "name": "Calendar",
  "parameters": {
    "after": "To how many days after (default 30)",
    "before": "From how many days ago (default 30)"
  },
  "path": "/calendar/:before?/:after?",
  "radar": [
    {
      "source": [
        "thwiki.cc/",
        "thwiki.cc/日程表"
      ],
      "target": "/calendar"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "A Touhou related events calendar api from THBWiki - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60280539896619008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://calendar.thwiki.cc/",
      "title": "Touhou events calendar (THBWiki)",
      "type": "feed",
      "url": "rsshub://thwiki/calendar"
    }
  ],
  "url": "thwiki.cc/"
}
```
