# Minecraft - Java Game Update

## Coverage
`index-only`

## Route
- Namespace: `minecraft`
- Namespace Name: `Minecraft`
- Route Path: `/version/:versionType?/:linkType?`
- Route Name: `Java Game Update`
- Example: `/minecraft/version`
- URL: `minecraft.net/`
- Language: `en`
- Categories: `game`
- Maintainers: `TheresaQWQ, xtexChooser`
- Source Location: `version.ts`
- Source Module: `() => import('@/routes/minecraft/version.ts')`

## Description
| Version                    | versionType |
| -------------------------- | ----------- |
| 正式版                     | release     |
| 快照                       | snapshot    |
| Alpha 及更早的版本         | old_alpha  |
| Beta 版                    | old_beta   |
| Target                     | linkType    |
| -------------------------- | --------    |
| minecraft.net              | official    |
| 英文 Minecraft Wiki 版本页 | enwiki      |
| 中文 Minecraft Wiki 版本页 | zhwiki      |

## Parameters
- `versionType`: Game version type, `all` by default
- `linkType`: Link added to feed, `official` by default


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
  - `minecraft.net/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "\n| Version                    | versionType |\n| -------------------------- | ----------- |\n| 正式版                     | release     |\n| 快照                       | snapshot    |\n| Alpha 及更早的版本         | old_alpha  |\n| Beta 版                    | old_beta   |\n| Target                     | linkType    |\n| -------------------------- | --------    |\n| minecraft.net              | official    |\n| 英文 Minecraft Wiki 版本页 | enwiki      |\n| 中文 Minecraft Wiki 版本页 | zhwiki      |\n",
  "example": "/minecraft/version",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "version.ts",
  "maintainers": [
    "TheresaQWQ",
    "xtexChooser"
  ],
  "module": "() => import('@/routes/minecraft/version.ts')",
  "name": "Java Game Update",
  "parameters": {
    "linkType": "Link added to feed, `official` by default",
    "versionType": "Game version type, `all` by default"
  },
  "path": "/version/:versionType?/:linkType?",
  "radar": [
    {
      "source": [
        "minecraft.net/"
      ]
    }
  ],
  "url": "minecraft.net/",
  "zh": {
    "name": "Java版游戏更新"
  }
}
```
