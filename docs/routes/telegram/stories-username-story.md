# Telegram - Stories

## Coverage
`index-only`

## Route
- Namespace: `telegram`
- Namespace Name: `Telegram`
- Route Path: `/stories/:username/:story?`
- Route Name: `Stories`
- Example: `/telegram/stories/telegram`
- URL: `t.me`
- Language: `en`
- Categories: `social-media`
- Maintainers: `synchrone`
- Source Location: `stories.ts`
- Source Module: `() => import('@/routes/telegram/stories.ts')`

## Description
_None_

## Parameters
- `username`: entity name
- `story`: story


## Features
- `requireConfig`: [{"description": "Telegram API Authentication", "name": "TELEGRAM_SESSION", "optional": false}, {"description": "Telegram API ID", "name": "TELEGRAM_API_ID", "optional": true}, {"description": "Telegram API Hash", "name": "TELEGRAM_API_HASH", "optional": true}, {"description": "Telegram Max Concurrent Downloads", "name": "TELEGRAM_MAX_CONCURRENT_DOWNLOADS", "optional": true}, {"description": "Telegram Proxy Host", "name": "TELEGRAM_PROXY_HOST", "optional": true}, {"description": "Telegram Proxy Port", "name": "TELEGRAM_PROXY_PORT", "optional": true}, {"description": "Telegram Proxy Secret", "name": "TELEGRAM_PROXY_SECRET", "optional": true}]
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
    "social-media"
  ],
  "description": "",
  "example": "/telegram/stories/telegram",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Telegram API Authentication",
        "name": "TELEGRAM_SESSION",
        "optional": false
      },
      {
        "description": "Telegram API ID",
        "name": "TELEGRAM_API_ID",
        "optional": true
      },
      {
        "description": "Telegram API Hash",
        "name": "TELEGRAM_API_HASH",
        "optional": true
      },
      {
        "description": "Telegram Max Concurrent Downloads",
        "name": "TELEGRAM_MAX_CONCURRENT_DOWNLOADS",
        "optional": true
      },
      {
        "description": "Telegram Proxy Host",
        "name": "TELEGRAM_PROXY_HOST",
        "optional": true
      },
      {
        "description": "Telegram Proxy Port",
        "name": "TELEGRAM_PROXY_PORT",
        "optional": true
      },
      {
        "description": "Telegram Proxy Secret",
        "name": "TELEGRAM_PROXY_SECRET",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "stories.ts",
  "maintainers": [
    "synchrone"
  ],
  "module": "() => import('@/routes/telegram/stories.ts')",
  "name": "Stories",
  "parameters": {
    "story": "story",
    "username": "entity name"
  },
  "path": "/stories/:username/:story?",
  "radar": []
}
```
