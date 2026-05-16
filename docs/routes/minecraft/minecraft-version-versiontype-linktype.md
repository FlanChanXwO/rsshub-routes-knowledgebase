# Minecraft - Java Game Update

## Coverage
`index-only`

## Route
- Namespace: `minecraft`
- Namespace Name: `Minecraft`
- Route Path: `/minecraft/version/:versionType?/:linkType?`
- Route Name: `Java Game Update`
- Example: `/minecraft/version`
- URL: `minecraft.net/`
- Language: `_None_`
- Categories: `game`
- Maintainers: `TheresaQWQ, xtexChooser`
- Source Location: `version.ts`
- Source Module: `_None_`

## Description
| Version                    | versionType |
| -------------------------- | ----------- |
| 正式版                     | release     |
| 快照                       | snapshot    |
| Alpha 及更早的版本         | old\_alpha  |
| Beta 版                    | old\_beta   |
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
  "description": "| Version                    | versionType |\n| -------------------------- | ----------- |\n| 正式版                     | release     |\n| 快照                       | snapshot    |\n| Alpha 及更早的版本         | old\\_alpha  |\n| Beta 版                    | old\\_beta   |\n| Target                     | linkType    |\n| -------------------------- | --------    |\n| minecraft.net              | official    |\n| 英文 Minecraft Wiki 版本页 | enwiki      |\n| 中文 Minecraft Wiki 版本页 | zhwiki      |",
  "example": "/minecraft/version",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 61,
  "location": "version.ts",
  "maintainers": [
    "TheresaQWQ",
    "xtexChooser"
  ],
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
  "topFeeds": [
    {
      "description": "Minecraft Java版游戏更新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62456080663433216",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.minecraft.net/",
      "title": "Minecraft Java版游戏更新",
      "type": "feed",
      "url": "rsshub://minecraft/version"
    },
    {
      "description": "Minecraft Java版游戏更新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "154953137410003968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.minecraft.net/",
      "title": "Minecraft Java版游戏更新",
      "type": "feed",
      "url": "rsshub://minecraft/version/all/official"
    }
  ],
  "url": "minecraft.net/",
  "zh": {
    "name": "Java版游戏更新"
  }
}
```
