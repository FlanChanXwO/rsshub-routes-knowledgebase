# Medium - Personalized Recommendations - Following

## Coverage
`index-only`

## Route
- Namespace: `medium`
- Namespace Name: `Medium`
- Route Path: `/following/:user`
- Route Name: `Personalized Recommendations - Following`
- Example: `/medium/following/imsingee`
- URL: `medium.com`
- Language: `en`
- Categories: `blog`
- Maintainers: `ImSingee`
- Source Location: `following.ts`
- Source Module: `() => import('@/routes/medium/following.ts')`

## Description
::: warning
  Personalized recommendations require the cookie value after logging in, so only self-hosting is supported. See the configuration module on the deployment page for details.
:::

## Parameters
- `user`: Username


## Features
- `requireConfig`: [{"description": "", "name": "MEDIUM_COOKIE_*"}]
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
  "description": "::: warning\n  Personalized recommendations require the cookie value after logging in, so only self-hosting is supported. See the configuration module on the deployment page for details.\n:::",
  "example": "/medium/following/imsingee",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "MEDIUM_COOKIE_*"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "following.ts",
  "maintainers": [
    "ImSingee"
  ],
  "module": "() => import('@/routes/medium/following.ts')",
  "name": "Personalized Recommendations - Following",
  "parameters": {
    "user": "Username"
  },
  "path": "/following/:user"
}
```
