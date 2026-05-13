# ResetEra - Thread latest posts (text & images)

## Coverage
`index-only`

## Route
- Namespace: `resetera`
- Namespace Name: `ResetEra`
- Route Path: `/thread/:id`
- Route Name: `Thread latest posts (text & images)`
- Example: `/resetera/thread/1076160`
- URL: `resetera.com`
- Language: `en`
- Categories: `bbs`
- Maintainers: `ZEN-GUO`
- Source Location: `thread.ts`
- Source Module: `() => import('@/routes/resetera/thread.ts')`

## Description
_None_

## Parameters
- `id`: Numeric thread ID at the end of the URL


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `resetera.com/threads/:slug.:id/`
- `target`: `/thread/:id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/resetera/thread/1076160",
  "location": "thread.ts",
  "maintainers": [
    "ZEN-GUO"
  ],
  "module": "() => import('@/routes/resetera/thread.ts')",
  "name": "Thread latest posts (text & images)",
  "parameters": {
    "id": "Numeric thread ID at the end of the URL"
  },
  "path": "/thread/:id",
  "radar": [
    {
      "source": [
        "resetera.com/threads/:slug.:id/"
      ],
      "target": "/thread/:id"
    }
  ],
  "url": "resetera.com"
}
```
