# UK Parliament - House of Lords Library

## Coverage
`index-only`

## Route
- Namespace: `parliament.uk`
- Namespace Name: `UK Parliament`
- Route Path: `/lordslibrary/type/:topic?`
- Route Name: `House of Lords Library`
- Example: `/parliament.uk/lordslibrary/type/research-briefing`
- URL: `parliament.uk`
- Language: `en`
- Categories: `government`
- Maintainers: `AntiKnot`
- Source Location: `lordslibrary.ts`
- Source Module: `() => import('@/routes/parliament.uk/lordslibrary.ts')`

## Description
_None_

## Parameters
- `topic`: research by topic, string, example: [research-briefing|buisness|economy]


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
    "government"
  ],
  "example": "/parliament.uk/lordslibrary/type/research-briefing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "lordslibrary.ts",
  "maintainers": [
    "AntiKnot"
  ],
  "module": "() => import('@/routes/parliament.uk/lordslibrary.ts')",
  "name": "House of Lords Library",
  "parameters": {
    "topic": "research by topic, string, example: [research-briefing|buisness|economy]"
  },
  "path": "/lordslibrary/type/:topic?"
}
```
