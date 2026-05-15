# BBC - Topics - BBC News 中文

## Coverage
`index-only`

## Route
- Namespace: `bbc`
- Namespace Name: `BBC`
- Route Path: `/bbc/zhongwen/topics/:topic/:variant?`
- Route Name: `Topics - BBC News 中文`
- Example: `/bbc/zhongwen/topics/ckr7mn6r003t`
- URL: `bbc.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `topic-zhongwen.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: The topic ID to fetch news for, can be found in the URL.
- `variant`: {"default": "trad", "description": "The language variant.", "options": [{"label": "简", "value": "simp"}, {"label": "繁", "value": "trad"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.bbc.com/zhongwen/topics/:topic/:variant`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/bbc/zhongwen/topics/ckr7mn6r003t",
  "heat": 9,
  "location": "topic-zhongwen.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Topics - BBC News 中文",
  "parameters": {
    "topic": "The topic ID to fetch news for, can be found in the URL.",
    "variant": {
      "default": "trad",
      "description": "The language variant.",
      "options": [
        {
          "label": "简",
          "value": "simp"
        },
        {
          "label": "繁",
          "value": "trad"
        }
      ]
    }
  },
  "path": "/zhongwen/topics/:topic/:variant?",
  "radar": [
    {
      "source": [
        "www.bbc.com/zhongwen/topics/:topic/:variant"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:37:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中国 - BBC News 中文 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "247863825203096576",
      "image": "https://www.bbc.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.bbc.com/zhongwen/topics/ckr7mn6r003t/simp",
      "title": "中国 - BBC News 中文",
      "type": "feed",
      "url": "rsshub://bbc/zhongwen/topics/ckr7mn6r003t/simp"
    }
  ]
}
```
