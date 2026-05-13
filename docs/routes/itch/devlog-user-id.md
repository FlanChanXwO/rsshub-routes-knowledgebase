# itch.io - Developer Logs

## Coverage
`index-only`

## Route
- Namespace: `itch`
- Namespace Name: `itch.io`
- Route Path: `/devlog/:user/:id`
- Route Name: `Developer Logs`
- Example: `/itch/devlog/teamterrible/the-baby-in-yellow`
- URL: `itch.io`
- Language: `en`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `devlog.ts`
- Source Module: `() => import('@/routes/itch/devlog.ts')`

## Description
`User id` is the field before `.itch.io` in the URL of the corresponding page, e.g. the URL of [The Baby In Yellow Devlog](https://teamterrible.itch.io/the-baby-in-yellow/devlog) is `https://teamterrible.itch.io/the-baby-in-yellow/devlog`, where the field before `.itch.io` is `teamterrible`.

  `Item id` is the field between `itch.io` and `/devlog` in the URL of the corresponding page, e.g. the URL for [The Baby In Yellow Devlog](https://teamterrible.itch.io/the-baby-in-yellow/devlog) is `https://teamterrible.itch.io/the-baby-in-yellow/devlog`, where the field between `itch.io` and `/devlog` is `the-baby-in-yellow`.

  So the route is [`/itch/devlogs/teamterrible/the-baby-in-yellow`](https://rsshub.app/itch/devlogs/teamterrible/the-baby-in-yellow).

## Parameters
- `user`: User id, can be found in URL
- `id`: Item id, can be found in URL


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
    "game"
  ],
  "description": "`User id` is the field before `.itch.io` in the URL of the corresponding page, e.g. the URL of [The Baby In Yellow Devlog](https://teamterrible.itch.io/the-baby-in-yellow/devlog) is `https://teamterrible.itch.io/the-baby-in-yellow/devlog`, where the field before `.itch.io` is `teamterrible`.\n\n  `Item id` is the field between `itch.io` and `/devlog` in the URL of the corresponding page, e.g. the URL for [The Baby In Yellow Devlog](https://teamterrible.itch.io/the-baby-in-yellow/devlog) is `https://teamterrible.itch.io/the-baby-in-yellow/devlog`, where the field between `itch.io` and `/devlog` is `the-baby-in-yellow`.\n\n  So the route is [`/itch/devlogs/teamterrible/the-baby-in-yellow`](https://rsshub.app/itch/devlogs/teamterrible/the-baby-in-yellow).",
  "example": "/itch/devlog/teamterrible/the-baby-in-yellow",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "devlog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/itch/devlog.ts')",
  "name": "Developer Logs",
  "parameters": {
    "id": "Item id, can be found in URL",
    "user": "User id, can be found in URL"
  },
  "path": "/devlog/:user/:id"
}
```
