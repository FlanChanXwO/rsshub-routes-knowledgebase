# THBWiki - Calendar

## Coverage
`index-only`

## Route
- Namespace: `thwiki`
- Namespace Name: `THBWiki`
- Route Path: `/calendar/:before?/:after?`
- Route Name: `Calendar`
- Example: `/thwiki/calendar`
- URL: `thwiki.cc/`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `aether17`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/thwiki/index.ts')`

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
  "location": "index.ts",
  "maintainers": [
    "aether17"
  ],
  "module": "() => import('@/routes/thwiki/index.ts')",
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
  "url": "thwiki.cc/"
}
```
