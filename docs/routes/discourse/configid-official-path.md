# Discourse - Official RSS

## Coverage
`index-only`

## Route
- Namespace: `discourse`
- Namespace Name: `Discourse`
- Route Path: `/:configId/official/:path{.+}`
- Route Name: `Official RSS`
- Example: `/discourse/0/official/latest`
- URL: `_None_`
- Language: `en`
- Categories: `bbs`
- Maintainers: `Raikyou, dzx-dzx`
- Source Location: `official.ts`
- Source Module: `() => import('@/routes/discourse/official.ts')`

## Description
_None_

## Parameters
- `configId`: Environment variable configuration id, see above
- `path`: Discourse RSS path between `domain` and `.rss`. All supported Rss path can be found in [https://meta.discourse.org/t/finding-discourse-rss-feeds/264134](https://meta.discourse.org/t/finding-discourse-rss-feeds/264134). For example: the path of [https://meta.discourse.org/top/all.rss](https://meta.discourse.org/top/all.rss) is `top/all`.


## Features
- `requireConfig`: [{"description": "Configure the Discourse environment variables referring to [https://docs.rsshub.app/deploy/config#discourse](https://docs.rsshub.app/deploy/config#discourse).", "name": "DISCOURSE_CONFIG_*"}]
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
    "bbs"
  ],
  "example": "/discourse/0/official/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Configure the Discourse environment variables referring to [https://docs.rsshub.app/deploy/config#discourse](https://docs.rsshub.app/deploy/config#discourse).",
        "name": "DISCOURSE_CONFIG_*"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "official.ts",
  "maintainers": [
    "Raikyou",
    "dzx-dzx"
  ],
  "module": "() => import('@/routes/discourse/official.ts')",
  "name": "Official RSS",
  "parameters": {
    "configId": "Environment variable configuration id, see above",
    "path": "Discourse RSS path between `domain` and `.rss`. All supported Rss path can be found in [https://meta.discourse.org/t/finding-discourse-rss-feeds/264134](https://meta.discourse.org/t/finding-discourse-rss-feeds/264134). For example: the path of [https://meta.discourse.org/top/all.rss](https://meta.discourse.org/top/all.rss) is `top/all`."
  },
  "path": "/:configId/official/:path{.+}"
}
```
