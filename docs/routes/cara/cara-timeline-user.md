# Cara - Timeline

## Coverage
`index-only`

## Route
- Namespace: `cara`
- Namespace Name: `Cara`
- Route Path: `/cara/timeline/:user`
- Route Name: `Timeline`
- Example: `/cara/timeline/fengz`
- URL: `cara.app`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `timeline.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: username


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cara.app/:user`
  - `cara.app/:user/*`
- `target`: `/timeline/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/cara/timeline/fengz",
  "heat": 14,
  "location": "timeline.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "Timeline",
  "parameters": {
    "user": "username"
  },
  "path": [
    "/timeline/:user"
  ],
  "radar": [
    {
      "source": [
        "cara.app/:user",
        "cara.app/:user/*"
      ],
      "target": "/timeline/:user"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Timeline - NIKA LYNAS - Powered by RSSHub",
      "errorAt": "2025-11-21T13:47:28.301Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "127384810660678656",
      "image": "https://cdn.cara.app/production/profiles/f771718b-26f2-4d08-bda8-ddfbdac6a995/sf.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/cyberpunkova/all",
      "title": "Timeline - NIKA LYNAS",
      "type": "feed",
      "url": "rsshub://cara/timeline/cyberpunkova"
    },
    {
      "description": "Timeline - Olevus Art - Powered by RSSHub",
      "errorAt": "2025-11-26T13:56:41.091Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "127387927078266880",
      "image": "https://cdn.cara.app/production/profiles/328e10c7-adef-4eba-b86a-d847a0c7cb6a/17BE1A54-C420-41BC-954C-EB9123B82F2D.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/olevusart/all",
      "title": "Timeline - Olevus Art",
      "type": "feed",
      "url": "rsshub://cara/timeline/olevusart"
    }
  ]
}
```
