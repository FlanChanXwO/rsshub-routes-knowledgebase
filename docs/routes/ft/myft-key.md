# Financial Times - myFT personal RSS

## Coverage
`index-only`

## Route
- Namespace: `ft`
- Namespace Name: `Financial Times`
- Route Path: `/myft/:key`
- Route Name: `myFT personal RSS`
- Example: `/ft/myft/rss-key`
- URL: `ft.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `HenryQW`
- Source Location: `myft.ts`
- Source Module: `() => import('@/routes/ft/myft.ts')`

## Description
::: tip
  -   Visit ft.com -> myFT -> Contact Preferences to enable personal RSS feed, see [help.ft.com](https://help.ft.com/faq/email-alerts-and-contact-preferences/what-is-myft-rss-feed/)
  -   Obtain the key from the personal RSS address, it looks like `12345678-abcd-4036-82db-vdv20db024b8`
:::

## Parameters
- `key`: the last part of myFT personal RSS address


## Features
- `requireConfig`: false
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
    "traditional-media"
  ],
  "description": "::: tip\n  -   Visit ft.com -> myFT -> Contact Preferences to enable personal RSS feed, see [help.ft.com](https://help.ft.com/faq/email-alerts-and-contact-preferences/what-is-myft-rss-feed/)\n  -   Obtain the key from the personal RSS address, it looks like `12345678-abcd-4036-82db-vdv20db024b8`\n:::",
  "example": "/ft/myft/rss-key",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "myft.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/ft/myft.ts')",
  "name": "myFT personal RSS",
  "parameters": {
    "key": "the last part of myFT personal RSS address"
  },
  "path": "/myft/:key"
}
```
