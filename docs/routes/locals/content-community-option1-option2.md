# Locals - Content Feed

## Coverage
`index-only`

## Route
- Namespace: `locals`
- Namespace Name: `Locals`
- Route Path: `/content/:community/:option1?/:option2?`
- Route Name: `Content Feed`
- Example: `/locals/content/mattfradd/video`
- URL: `locals.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `luckycold`
- Source Location: `feed.ts`
- Source Module: `() => import('@/routes/locals/feed.ts')`

## Description
Fetches the Locals content library with an authenticated session cookie. By default it merges regular content and content+ posts, and it can be filtered by access tier and media type.

## Parameters
- `community`: Community slug from `locals.com/:community/feed?mode=content`
- `option1`: Filter or content type. Filters: `plus`, `nonplus`. Content types: `video`, `live`, `audio`, `podcast`, `article`, `document`, `pdf`
- `option2`: Content type when `option1` is a filter


## Features
- `requireConfig`: [{"description": "The value of the `locals2.v3.session` cookie after logging in to Locals", "name": "LOCALS_SESSION"}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `locals.com/:community/feed`
- `target`: `/content/:community`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "Fetches the Locals content library with an authenticated session cookie. By default it merges regular content and content+ posts, and it can be filtered by access tier and media type.",
  "example": "/locals/content/mattfradd/video",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "The value of the `locals2.v3.session` cookie after logging in to Locals",
        "name": "LOCALS_SESSION"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "feed.ts",
  "maintainers": [
    "luckycold"
  ],
  "module": "() => import('@/routes/locals/feed.ts')",
  "name": "Content Feed",
  "parameters": {
    "community": "Community slug from `locals.com/:community/feed?mode=content`",
    "option1": "Filter or content type. Filters: `plus`, `nonplus`. Content types: `video`, `live`, `audio`, `podcast`, `article`, `document`, `pdf`",
    "option2": "Content type when `option1` is a filter"
  },
  "path": "/content/:community/:option1?/:option2?",
  "radar": [
    {
      "source": [
        "locals.com/:community/feed"
      ],
      "target": "/content/:community"
    }
  ]
}
```
