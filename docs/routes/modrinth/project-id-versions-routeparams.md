# Modrinth - Project versions

## Coverage
`index-only`

## Route
- Namespace: `modrinth`
- Namespace Name: `Modrinth`
- Route Path: `/project/:id/versions/:routeParams?`
- Route Name: `Project versions`
- Example: `/modrinth/project/sodium/versions`
- URL: `modrinth.com`
- Language: `en`
- Categories: `game`
- Maintainers: `SettingDust`
- Source Location: `versions.tsx`
- Source Module: `() => import('@/routes/modrinth/versions.tsx')`

## Description
| Name           | Example                                      |
| -------------- | -------------------------------------------- |
| loaders        | loaders=fabric&loaders=quilt&loaders=forge |
| game_versions | game_versions=1.20.1&game_versions=1.20.2 |
| featured       | featured=true                                |

## Parameters
- `id`: Id or slug of the Modrinth project
- `routeParams`: Extra route params. See the table below for options


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
  - `modrinth.com/mod/:id/*`
  - `modrinth.com/plugin/:id/*`
  - `modrinth.com/datapack/:id/*`
  - `modrinth.com/shader/:id/*`
  - `modrinth.com/resourcepack/:id/*`
  - `modrinth.com/modpack/:id/*`
  - `modrinth.com/mod/:id`
  - `modrinth.com/plugin/:id`
  - `modrinth.com/datapack/:id`
  - `modrinth.com/shader/:id`
  - `modrinth.com/resourcepack/:id`
  - `modrinth.com/modpack/:id`
- `target`: `/project/:id/versions`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| Name           | Example                                      |\n| -------------- | -------------------------------------------- |\n| loaders        | loaders=fabric&loaders=quilt&loaders=forge |\n| game_versions | game_versions=1.20.1&game_versions=1.20.2 |\n| featured       | featured=true                                |",
  "example": "/modrinth/project/sodium/versions",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "versions.tsx",
  "maintainers": [
    "SettingDust"
  ],
  "module": "() => import('@/routes/modrinth/versions.tsx')",
  "name": "Project versions",
  "parameters": {
    "id": "Id or slug of the Modrinth project",
    "routeParams": "Extra route params. See the table below for options"
  },
  "path": "/project/:id/versions/:routeParams?",
  "radar": [
    {
      "source": [
        "modrinth.com/mod/:id/*",
        "modrinth.com/plugin/:id/*",
        "modrinth.com/datapack/:id/*",
        "modrinth.com/shader/:id/*",
        "modrinth.com/resourcepack/:id/*",
        "modrinth.com/modpack/:id/*",
        "modrinth.com/mod/:id",
        "modrinth.com/plugin/:id",
        "modrinth.com/datapack/:id",
        "modrinth.com/shader/:id",
        "modrinth.com/resourcepack/:id",
        "modrinth.com/modpack/:id"
      ],
      "target": "/project/:id/versions"
    }
  ]
}
```
