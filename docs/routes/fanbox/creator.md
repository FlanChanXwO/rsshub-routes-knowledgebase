# fanbox - Creator

## Coverage
`index-only`

## Route
- Namespace: `fanbox`
- Namespace Name: `fanbox`
- Route Path: `/:creator`
- Route Name: `Creator`
- Example: `/fanbox/official`
- URL: `www.fanbox.cc`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `KarasuShin, pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/fanbox/index.ts')`

## Description
_None_

## Parameters
- `creator`: fanbox user name


## Features
- `requireConfig`: [{"description": "Required for private posts. Can be found in browser DevTools -> Application -> Cookies -> https://www.fanbox.cc -> FANBOXSESSID", "name": "FANBOX_SESSION_ID", "optional": true}]
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/fanbox/official",
  "features": {
    "nsfw": true,
    "requireConfig": [
      {
        "description": "Required for private posts. Can be found in browser DevTools -> Application -> Cookies -> https://www.fanbox.cc -> FANBOXSESSID",
        "name": "FANBOX_SESSION_ID",
        "optional": true
      }
    ]
  },
  "location": "index.ts",
  "maintainers": [
    "KarasuShin",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/fanbox/index.ts')",
  "name": "Creator",
  "parameters": {
    "creator": "fanbox user name"
  },
  "path": "/:creator"
}
```
