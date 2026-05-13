# Mastodon - Hashtag timeline

## Coverage
`index-only`

## Route
- Namespace: `mastodon`
- Namespace Name: `Mastodon`
- Route Path: `/tag/:site/:hashtag/:only_media?`
- Route Name: `Hashtag timeline`
- Example: `/mastodon/tag/mastodon.social/gochisou/true`
- URL: `mastodon.social`
- Language: `en`
- Categories: `social-media`
- Maintainers: `yuikisaito`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/mastodon/tag.ts')`

## Description
_None_

## Parameters
- `site`: instance address, only domain, no `http://` or `https://` protocol header
- `hashtag`: Hashtag you want to subscribe to (without the # symbol)
- `only_media`: {"default": "false", "description": "whether only display media content, default to false, any value to true", "options": [{"label": "true", "value": "true"}, {"label": "false", "value": "false"}]}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/mastodon/tag/mastodon.social/gochisou/true",
  "location": "tag.ts",
  "maintainers": [
    "yuikisaito"
  ],
  "module": "() => import('@/routes/mastodon/tag.ts')",
  "name": "Hashtag timeline",
  "parameters": {
    "hashtag": "Hashtag you want to subscribe to (without the # symbol)",
    "only_media": {
      "default": "false",
      "description": "whether only display media content, default to false, any value to true",
      "options": [
        {
          "label": "true",
          "value": "true"
        },
        {
          "label": "false",
          "value": "false"
        }
      ]
    },
    "site": "instance address, only domain, no `http://` or `https://` protocol header"
  },
  "path": "/tag/:site/:hashtag/:only_media?",
  "view": 1
}
```
