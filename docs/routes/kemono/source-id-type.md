# Kemono - Posts

## Coverage
`index-only`

## Route
- Namespace: `kemono`
- Namespace Name: `Kemono`
- Route Path: `/:source?/:id?/:type?`
- Route Name: `Posts`
- Example: `/kemono`
- URL: `kemono.cr`
- Language: `en`
- Categories: `anime`
- Maintainers: `nczitzk, AiraNadih`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/kemono/index.tsx')`

## Description
Sources

| Posts | Patreon | Pixiv Fanbox | Gumroad | SubscribeStar | DLsite | Discord | Fantia |
| ----- | ------- | ------------ | ------- | ------------- | ------ | ------- | ------ |
| posts | patreon | fanbox       | gumroad | subscribestar | dlsite | discord | fantia |

::: tip
  When `posts` is selected as the value of the parameter **source**, the parameter **id** does not take effect.
  There is an optinal parameter **limit** which controls the number of posts to fetch, default value is 25.

  Support for announcements and fancards:
  - Use `/:source/:id/announcements` to get announcements
  - Use `/:source/:id/fancards` to get fancards
:::

## Parameters
- `source`: Source, see below, Posts by default
- `id`: User id, can be found in URL
- `type`: Content type: announcements or fancards


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
  - `kemono.cr/`
- `target`: ``
### Rule 2
- `source`:
  - `kemono.cr/:source/user/:id`
- `target`: `/:source/:id`
### Rule 3
- `source`:
  - `kemono.cr/:source/user/:id/announcements`
- `target`: `/:source/:id/announcements`
### Rule 4
- `source`:
  - `kemono.cr/:source/user/:id/fancards`
- `target`: `/:source/:id/fancards`
### Rule 5
- `source`:
  - `kemono.cr/discord/server/:id`
- `target`: `/discord/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "Sources\n\n| Posts | Patreon | Pixiv Fanbox | Gumroad | SubscribeStar | DLsite | Discord | Fantia |\n| ----- | ------- | ------------ | ------- | ------------- | ------ | ------- | ------ |\n| posts | patreon | fanbox       | gumroad | subscribestar | dlsite | discord | fantia |\n\n::: tip\n  When `posts` is selected as the value of the parameter **source**, the parameter **id** does not take effect.\n  There is an optinal parameter **limit** which controls the number of posts to fetch, default value is 25.\n\n  Support for announcements and fancards:\n  - Use `/:source/:id/announcements` to get announcements\n  - Use `/:source/:id/fancards` to get fancards\n:::",
  "example": "/kemono",
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
  "module": "() => import('@/routes/kemono/index.tsx')",
  "name": "Posts",
  "parameters": {
    "id": "User id, can be found in URL",
    "source": "Source, see below, Posts by default",
    "type": "Content type: announcements or fancards"
  },
  "path": "/:source?/:id?/:type?",
  "radar": [
    {
      "source": [
        "kemono.cr/"
      ],
      "target": ""
    },
    {
      "source": [
        "kemono.cr/:source/user/:id"
      ],
      "target": "/:source/:id"
    },
    {
      "source": [
        "kemono.cr/:source/user/:id/announcements"
      ],
      "target": "/:source/:id/announcements"
    },
    {
      "source": [
        "kemono.cr/:source/user/:id/fancards"
      ],
      "target": "/:source/:id/fancards"
    },
    {
      "source": [
        "kemono.cr/discord/server/:id"
      ],
      "target": "/discord/:id"
    }
  ]
}
```
