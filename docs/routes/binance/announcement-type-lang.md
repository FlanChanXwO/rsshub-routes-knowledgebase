# Binance - Announcement

## Coverage
`index-only`

## Route
- Namespace: `binance`
- Namespace Name: `Binance`
- Route Path: `/announcement/:type?/:lang?`
- Route Name: `Announcement`
- Example: `/binance/announcement/new-cryptocurrency-listing`
- URL: `binance.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `enpitsulin, DIYgod`
- Source Location: `announcement.ts`
- Source Module: `() => import('@/routes/binance/announcement.ts')`

## Description
Announcement list from Binance message center with language and type selection.

## Parameters
- `type`: {"default": "all", "description": "Announcement type. Omit for all categories.", "options": [{"label": "All", "value": "all"}, {"label": "New Cryptocurrency Listing", "value": "new-cryptocurrency-listing"}, {"label": "Latest Binance News", "value": "latest-binance-news"}, {"label": "Latest Activities", "value": "latest-activities"}, {"label": "New Fiat Listings", "value": "new-fiat-listings"}, {"label": "API Updates", "value": "api-updates"}, {"label": "Crypto Airdrop", "value": "crypto-airdrop"}, {"label": "Wallet Maintenance Updates", "value": "wallet-maintenance-updates"}, {"label": "Delisting", "value": "delisting"}]}
- `lang`: {"default": "zh-CN", "description": "Language code for the messages page.", "options": [{"label": "Simplified Chinese", "value": "zh-CN"}, {"label": "English", "value": "en"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.binance.com/:lang/messages/v2/group/announcement`
- `target`: `/binance/announcement/all/:lang`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Announcement list from Binance message center with language and type selection.",
  "example": "/binance/announcement/new-cryptocurrency-listing",
  "location": "announcement.ts",
  "maintainers": [
    "enpitsulin",
    "DIYgod"
  ],
  "module": "() => import('@/routes/binance/announcement.ts')",
  "name": "Announcement",
  "parameters": {
    "lang": {
      "default": "zh-CN",
      "description": "Language code for the messages page.",
      "options": [
        {
          "label": "Simplified Chinese",
          "value": "zh-CN"
        },
        {
          "label": "English",
          "value": "en"
        }
      ]
    },
    "type": {
      "default": "all",
      "description": "Announcement type. Omit for all categories.",
      "options": [
        {
          "label": "All",
          "value": "all"
        },
        {
          "label": "New Cryptocurrency Listing",
          "value": "new-cryptocurrency-listing"
        },
        {
          "label": "Latest Binance News",
          "value": "latest-binance-news"
        },
        {
          "label": "Latest Activities",
          "value": "latest-activities"
        },
        {
          "label": "New Fiat Listings",
          "value": "new-fiat-listings"
        },
        {
          "label": "API Updates",
          "value": "api-updates"
        },
        {
          "label": "Crypto Airdrop",
          "value": "crypto-airdrop"
        },
        {
          "label": "Wallet Maintenance Updates",
          "value": "wallet-maintenance-updates"
        },
        {
          "label": "Delisting",
          "value": "delisting"
        }
      ]
    }
  },
  "path": "/announcement/:type?/:lang?",
  "radar": [
    {
      "source": [
        "www.binance.com/:lang/messages/v2/group/announcement"
      ],
      "target": "/binance/announcement/all/:lang"
    }
  ],
  "view": 0
}
```
