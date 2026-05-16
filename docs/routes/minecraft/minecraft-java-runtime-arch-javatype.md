# Minecraft - Java Runtimes

## Coverage
`index-only`

## Route
- Namespace: `minecraft`
- Namespace Name: `Minecraft`
- Route Path: `/minecraft/java-runtime/:arch?/:javaType?`
- Route Name: `Java Runtimes`
- Example: `/minecraft/java-runtime`
- URL: `minecraft.net/`
- Language: `_None_`
- Categories: `game`
- Maintainers: `xtexChooser`
- Source Location: `java-runtime.ts`
- Source Module: `_None_`

## Description
arch:

- gamecore (Currently not used by Mojang)
- linux
- linux-i386
- mac-os
- mac-os-arm64
- windows-arm64
- windows-x64
- windows-x86

javaType:

- java-runtime-alpha
- java-runtime-beta
- java-runtime-delta
- java-runtime-gamma
- java-runtime-gamma-snapshot
- jre-legacy
- minecraft-java-exe (Only on Windows)

## Parameters
- `arch`: Arch, `all` by default
- `javaType`: Java runtime type, `all` by default


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
  "description": "arch:\n\n- gamecore (Currently not used by Mojang)\n- linux\n- linux-i386\n- mac-os\n- mac-os-arm64\n- windows-arm64\n- windows-x64\n- windows-x86\n\njavaType:\n\n- java-runtime-alpha\n- java-runtime-beta\n- java-runtime-delta\n- java-runtime-gamma\n- java-runtime-gamma-snapshot\n- jre-legacy\n- minecraft-java-exe (Only on Windows)",
  "example": "/minecraft/java-runtime",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "java-runtime.ts",
  "maintainers": [
    "xtexChooser"
  ],
  "name": "Java Runtimes",
  "parameters": {
    "arch": "Arch, `all` by default",
    "javaType": "Java runtime type, `all` by default"
  },
  "path": "/java-runtime/:arch?/:javaType?",
  "radar": [
    {
      "source": [
        "minecraft.net/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "Minecraft Java运行时 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "164180124215687168",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.minecraft.net/",
      "title": "Minecraft Java运行时",
      "type": "feed",
      "url": "rsshub://minecraft/java-runtime"
    }
  ],
  "url": "minecraft.net/",
  "zh": {
    "name": "Java运行时"
  }
}
```
