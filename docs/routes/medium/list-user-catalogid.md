# Medium - List

## Coverage
`index-only`

## Route
- Namespace: `medium`
- Namespace Name: `Medium`
- Route Path: `/list/:user/:catalogId`
- Route Name: `List`
- Example: `/medium/list/imsingee/f2d8d48096a9`
- URL: `medium.com`
- Language: `en`
- Categories: `blog`
- Maintainers: `ImSingee`
- Source Location: `list.ts`
- Source Module: `() => import('@/routes/medium/list.ts')`

## Description
The List ID is the last part of the URL after `-`, for example, the username in [https://medium.com/@imsingee/list/collection-7e67004f23f9](https://medium.com/@imsingee/list/collection-7e67004f23f9) is `imsingee`, and the ID is `7e67004f23f9`.

::: warning
  To access private lists, only self-hosting is supported.
:::

## Parameters
- `user`: Username
- `catalogId`: List ID


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
    "blog"
  ],
  "description": "The List ID is the last part of the URL after `-`, for example, the username in [https://medium.com/@imsingee/list/collection-7e67004f23f9](https://medium.com/@imsingee/list/collection-7e67004f23f9) is `imsingee`, and the ID is `7e67004f23f9`.\n\n::: warning\n  To access private lists, only self-hosting is supported.\n:::",
  "example": "/medium/list/imsingee/f2d8d48096a9",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "list.ts",
  "maintainers": [
    "ImSingee"
  ],
  "module": "() => import('@/routes/medium/list.ts')",
  "name": "List",
  "parameters": {
    "catalogId": "List ID",
    "user": "Username"
  },
  "path": "/list/:user/:catalogId"
}
```
