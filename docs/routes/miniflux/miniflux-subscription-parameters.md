# MiniFlux - Subscriptions

## Coverage
`index-only`

## Route
- Namespace: `miniflux`
- Namespace Name: `MiniFlux`
- Route Path: `/miniflux/subscription/:parameters?`
- Route Name: `Subscriptions`
- Example: `/miniflux/subscription/categories=test`
- URL: `miniflux.app`
- Language: `_None_`
- Categories: `other`
- Maintainers: `emdoe, DIYgod`
- Source Location: `subscription.ts`
- Source Module: `_None_`

## Description
1. If no specific parameters are specified, all subscription sources will be output by default.
2. Please obtain the Category ID or Subscription Source ID on the `Category` (shortcut `g` `c`) or `Source` (shortcut `g` `f`) page. The URL of each category (or subscription source) will display its ID information.
3. Support for category names and category IDs, to output multiple categories, please repeat entering `category=` and connect with `&`, or directly use **English** commas between different category names. For example, you can subscribe through `/miniflux/subscription/category=technology&category=1` or `/miniflux/subscription/categories=technology,1`.
4. Support specifying the subscription source name or subscription source ID, similar to setting categories. For example, you can subscribe through `/miniflux/subscription/feed=1&feed=Archdaily` or `/miniflux/subscription/feeds=1,Archdaily`.
5. Support simultaneously specifying subscription source information and category information; it will output subscription sources that meet the selected categories' criteria. Consider an example: by using `/miniflux/subscription/feeds=1,archdaily&category=art,7`, if the Subscription Source ID is 1 or the Subscription Source Name is ArchDaily indeed falls under Category 'art' or has a Category ID of 7, then output that subscription source information.

## Parameters
- `parameters`: Category name or category ID or/and subscription source name or subscription source ID


## Features
- `requireConfig`: [{"description": "The instance used by the user, by default, is the official MiniFlux [paid service address](https://reader.miniflux.app)", "name": "MINIFLUX_INSTANCE"}, {"description": "User's API key, please log in to the instance used and go to `Settings` -> `API Key` -> `Create a new API key` to obtain.", "name": "MINIFLUX_TOKEN"}]
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
    "other"
  ],
  "description": "1. If no specific parameters are specified, all subscription sources will be output by default.\n2. Please obtain the Category ID or Subscription Source ID on the `Category` (shortcut `g` `c`) or `Source` (shortcut `g` `f`) page. The URL of each category (or subscription source) will display its ID information.\n3. Support for category names and category IDs, to output multiple categories, please repeat entering `category=` and connect with `&`, or directly use **English** commas between different category names. For example, you can subscribe through `/miniflux/subscription/category=technology&category=1` or `/miniflux/subscription/categories=technology,1`.\n4. Support specifying the subscription source name or subscription source ID, similar to setting categories. For example, you can subscribe through `/miniflux/subscription/feed=1&feed=Archdaily` or `/miniflux/subscription/feeds=1,Archdaily`.\n5. Support simultaneously specifying subscription source information and category information; it will output subscription sources that meet the selected categories' criteria. Consider an example: by using `/miniflux/subscription/feeds=1,archdaily&category=art,7`, if the Subscription Source ID is 1 or the Subscription Source Name is ArchDaily indeed falls under Category 'art' or has a Category ID of 7, then output that subscription source information.",
  "example": "/miniflux/subscription/categories=test",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "The instance used by the user, by default, is the official MiniFlux [paid service address](https://reader.miniflux.app)",
        "name": "MINIFLUX_INSTANCE"
      },
      {
        "description": "User's API key, please log in to the instance used and go to `Settings` -> `API Key` -> `Create a new API key` to obtain.",
        "name": "MINIFLUX_TOKEN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "subscription.ts",
  "maintainers": [
    "emdoe",
    "DIYgod"
  ],
  "name": "Subscriptions",
  "parameters": {
    "parameters": "Category name or category ID or/and subscription source name or subscription source ID"
  },
  "path": "/subscription/:parameters?",
  "topFeeds": []
}
```
