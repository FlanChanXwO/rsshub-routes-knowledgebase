# Tumblr - Posts

## Coverage
`index-only`

## Route
- Namespace: `tumblr`
- Namespace Name: `Tumblr`
- Route Path: `/posts/:blog`
- Route Name: `Posts`
- Example: `/tumblr/posts/biketouring-nearby`
- URL: `tumblr.com`
- Language: `en`
- Categories: `blog`
- Maintainers: `Rakambda, PolarisStarnor`
- Source Location: `posts.ts`
- Source Module: `() => import('@/routes/tumblr/posts.ts')`

## Description
::: tip
Tumblr provides official RSS feeds for non "dashboard only" blogs, for instance [https://biketouring-nearby.tumblr.com](https://biketouring-nearby.tumblr.com/rss).
:::

## Parameters
- `blog`: Blog identifier (see `https://www.tumblr.com/docs/en/api/v2#blog-identifiers`)


## Features
- `requireConfig`: [{"description": "Please see above for details.", "name": "TUMBLR_CLIENT_ID"}, {"description": "Please see above for details.", "name": "TUMBLR_CLIENT_SECRET"}, {"description": "Please see above for details.", "name": "TUMBLR_REFRESH_TOKEN"}]
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
    "blog"
  ],
  "description": "::: tip\nTumblr provides official RSS feeds for non \"dashboard only\" blogs, for instance [https://biketouring-nearby.tumblr.com](https://biketouring-nearby.tumblr.com/rss).\n:::",
  "example": "/tumblr/posts/biketouring-nearby",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Please see above for details.",
        "name": "TUMBLR_CLIENT_ID"
      },
      {
        "description": "Please see above for details.",
        "name": "TUMBLR_CLIENT_SECRET"
      },
      {
        "description": "Please see above for details.",
        "name": "TUMBLR_REFRESH_TOKEN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "posts.ts",
  "maintainers": [
    "Rakambda",
    "PolarisStarnor"
  ],
  "module": "() => import('@/routes/tumblr/posts.ts')",
  "name": "Posts",
  "parameters": {
    "blog": "Blog identifier (see `https://www.tumblr.com/docs/en/api/v2#blog-identifiers`)"
  },
  "path": "/posts/:blog",
  "radar": []
}
```
