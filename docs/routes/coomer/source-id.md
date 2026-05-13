# Coomer - Posts

## Coverage
`index-only`

## Route
- Namespace: `coomer`
- Namespace Name: `Coomer`
- Route Path: `/:source?/:id?`
- Route Name: `Posts`
- Example: `/coomer`
- URL: `coomer.st`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `nczitzk, AiraNadih`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/coomer/index.tsx')`

## Description
Sources

| Posts | OnlyFans | Fansly | CandFans |
| ----- | -------- | ------- | -------- |
| posts | onlyfans | fansly   | candfans |

::: tip
  When `posts` is selected as the value of the parameter **source**, the parameter **id** does not take effect.
  There is an optinal parameter **limit** which controls the number of posts to fetch, default value is 25.
:::

## Parameters
- `source`: Source, see below, Posts by default
- `id`: User id, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `coomer.st/`
- `target`: ``
### Rule 2
- `source`:
  - `coomer.st/:source/user/:id`
- `target`: `/:source/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "Sources\n\n| Posts | OnlyFans | Fansly | CandFans |\n| ----- | -------- | ------- | -------- |\n| posts | onlyfans | fansly   | candfans |\n\n::: tip\n  When `posts` is selected as the value of the parameter **source**, the parameter **id** does not take effect.\n  There is an optinal parameter **limit** which controls the number of posts to fetch, default value is 25.\n:::",
  "example": "/coomer",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "nczitzk",
    "AiraNadih"
  ],
  "module": "() => import('@/routes/coomer/index.tsx')",
  "name": "Posts",
  "parameters": {
    "id": "User id, can be found in URL",
    "source": "Source, see below, Posts by default"
  },
  "path": "/:source?/:id?",
  "radar": [
    {
      "source": [
        "coomer.st/"
      ],
      "target": ""
    },
    {
      "source": [
        "coomer.st/:source/user/:id"
      ],
      "target": "/:source/:id"
    }
  ]
}
```
