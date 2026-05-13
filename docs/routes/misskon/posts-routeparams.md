# MissKON - Posts

## Coverage
`index-only`

## Route
- Namespace: `misskon`
- Namespace Name: `MissKON`
- Route Path: `/posts/:routeParams?`
- Route Name: `Posts`
- Example: `/misskon/posts/search=video&tags_exclude=353,3100&per_page=5`
- URL: `misskon.com`
- Language: `en`
- Categories: `picture`
- Maintainers: `Urabartin`
- Source Location: `posts.ts`
- Source Module: `() => import('@/routes/misskon/posts.ts')`

## Description
_None_

## Parameters
- `routeParams`: Additional parameters for filtering posts, refer to [WordPress API Reference](https://developer.wordpress.org/rest-api/reference/posts/#arguments) for details.


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `misskon.com/`
- `target`: `/posts`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/misskon/posts/search=video&tags_exclude=353,3100&per_page=5",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "posts.ts",
  "maintainers": [
    "Urabartin"
  ],
  "module": "() => import('@/routes/misskon/posts.ts')",
  "name": "Posts",
  "parameters": {
    "routeParams": "Additional parameters for filtering posts, refer to [WordPress API Reference](https://developer.wordpress.org/rest-api/reference/posts/#arguments) for details."
  },
  "path": "/posts/:routeParams?",
  "radar": [
    {
      "source": [
        "misskon.com/"
      ],
      "target": "/posts"
    }
  ]
}
```
