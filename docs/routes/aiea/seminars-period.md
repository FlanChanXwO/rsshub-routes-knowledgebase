# Asian Innovation and Entrepreneurship Association - Seminar Series

## Coverage
`index-only`

## Route
- Namespace: `aiea`
- Namespace Name: `Asian Innovation and Entrepreneurship Association`
- Route Path: `/seminars/:period`
- Route Name: `Seminar Series`
- Example: `/aiea/seminars/upcoming`
- URL: `www.aiea.org`
- Language: `en`
- Categories: `study`
- Maintainers: `zxx-457`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/aiea/index.ts')`

## Description
| Time frame |
| ---------- |
| upcoming   |
| past       |
| both       |

## Parameters
- `period`: Time frame


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
    "study"
  ],
  "description": "| Time frame |\n| ---------- |\n| upcoming   |\n| past       |\n| both       |",
  "example": "/aiea/seminars/upcoming",
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
    "zxx-457"
  ],
  "module": "() => import('@/routes/aiea/index.ts')",
  "name": "Seminar Series",
  "parameters": {
    "period": "Time frame"
  },
  "path": "/seminars/:period"
}
```
