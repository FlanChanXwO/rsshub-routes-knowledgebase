# Minecraft - Java Blocked Servers

## Coverage
`index-only`

## Route
- Namespace: `minecraft`
- Namespace Name: `Minecraft`
- Route Path: `/blockedservers`
- Route Name: `Java Blocked Servers`
- Example: `/minecraft/blockedservers`
- URL: `minecraft.net/`
- Language: `en`
- Categories: `game`
- Maintainers: `xtexChooser`
- Source Location: `blockedservers.ts`
- Source Module: `() => import('@/routes/minecraft/blockedservers.ts')`

## Description
Java 版中被 Mojang 通过 sessionserver 阻止的服务器域名的 SHA-1 散列

## Parameters
_None_


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
  "description": "Java 版中被 Mojang 通过 sessionserver 阻止的服务器域名的 SHA-1 散列",
  "example": "/minecraft/blockedservers",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blockedservers.ts",
  "maintainers": [
    "xtexChooser"
  ],
  "module": "() => import('@/routes/minecraft/blockedservers.ts')",
  "name": "Java Blocked Servers",
  "parameters": {},
  "path": "/blockedservers",
  "radar": [
    {
      "source": [
        "minecraft.net/"
      ]
    }
  ],
  "url": "minecraft.net/",
  "zh": {
    "name": "Java版被阻止的服务器域名散列"
  }
}
```
