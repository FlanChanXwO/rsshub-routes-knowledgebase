# Yen Press - Series

## Coverage
`index-only`

## Route
- Namespace: `yenpress`
- Namespace Name: `Yen Press`
- Route Path: `/yenpress/series/:name`
- Route Name: `Series`
- Example: `/yenpress/series/alya-sometimes-hides-her-feelings-in-russian`
- URL: `yenpress.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `TonyRL`
- Source Location: `series.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: Series name


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `yenpress.com/series/:name`
- `target`: `/series/:name`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/yenpress/series/alya-sometimes-hides-her-feelings-in-russian",
  "heat": 0,
  "location": "series.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Series",
  "parameters": {
    "name": "Series name"
  },
  "path": "/series/:name",
  "radar": [
    {
      "source": [
        "yenpress.com/series/:name"
      ],
      "target": "/series/:name"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected -13209755035 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:37:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
