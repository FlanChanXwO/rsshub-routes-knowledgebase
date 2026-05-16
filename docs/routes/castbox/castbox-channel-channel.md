# Castbox - Channels

## Coverage
`index-only`

## Route
- Namespace: `castbox`
- Namespace Name: `Castbox`
- Route Path: `/castbox/channel/:channel`
- Route Name: `Channels`
- Example: `/castbox/channel/Lemonade-Stand-id6776228`
- URL: `castbox.fm`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `ananyatimalsina`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
Get the channel from the Castbox channel URL. For example, the URL of the channel "Lemonade Stand" is `https://castbox.fm/channel/Lemonade-Stand-id6776228`, where `Lemonade-Stand-id6776228` is the `channel` parameter.

You can use the RSSHub global `limit` query parameter to specify the maximum number of episodes to fetch from the Castbox API (defaults to 50). For example: `/castbox/channel/Lemonade-Stand-id6776228?limit=100`.

## Parameters
- `channel`: Channel


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `castbox.fm/channel/:channel`
- `target`: `/channel/:channel`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "Get the channel from the Castbox channel URL. For example, the URL of the channel \"Lemonade Stand\" is `https://castbox.fm/channel/Lemonade-Stand-id6776228`, where `Lemonade-Stand-id6776228` is the `channel` parameter.\n\nYou can use the RSSHub global `limit` query parameter to specify the maximum number of episodes to fetch from the Castbox API (defaults to 50). For example: `/castbox/channel/Lemonade-Stand-id6776228?limit=100`.",
  "example": "/castbox/channel/Lemonade-Stand-id6776228",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "channel.ts",
  "maintainers": [
    "ananyatimalsina"
  ],
  "name": "Channels",
  "parameters": {
    "channel": "Channel"
  },
  "path": "/channel/:channel",
  "radar": [
    {
      "source": [
        "castbox.fm/channel/:channel"
      ],
      "target": "/channel/:channel"
    }
  ],
  "topFeeds": []
}
```
