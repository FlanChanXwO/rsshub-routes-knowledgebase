# 机核网 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/gcores/users/:id/talks`
- Route Name: `用户动态`
- Example: `/gcores/users/31418/talks`
- URL: `www.gcores.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `DzmingLi`
- Source Location: `user-talks.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅用户 [这样重这样轻](https://www.gcores.com/users/31418/talks) 的动态，网址为 `https://www.gcores.com/users/31418/talks`，请截取 `https://www.gcores.com/users/` 到 `/talks` 之间的部分 `31418` 作为 `id` 参数填入，此时目标路由为 [`/gcores/users/31418/talks`](https://rsshub.app/gcores/users/31418/talks)。
:::

## Parameters
- `id`: {"description": "用户 ID，可在用户主页 URL 中找到"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.gcores.com/users/:id/talks`
- `target`: `/users/:id/talks`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若订阅用户 [这样重这样轻](https://www.gcores.com/users/31418/talks) 的动态，网址为 `https://www.gcores.com/users/31418/talks`，请截取 `https://www.gcores.com/users/` 到 `/talks` 之间的部分 `31418` 作为 `id` 参数填入，此时目标路由为 [`/gcores/users/31418/talks`](https://rsshub.app/gcores/users/31418/talks)。\n:::",
  "example": "/gcores/users/31418/talks",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user-talks.ts",
  "maintainers": [
    "DzmingLi"
  ],
  "name": "用户动态",
  "parameters": {
    "id": {
      "description": "用户 ID，可在用户主页 URL 中找到"
    }
  },
  "path": "/users/:id/talks",
  "radar": [
    {
      "source": [
        "www.gcores.com/users/:id/talks"
      ],
      "target": "/users/:id/talks"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.gcores.com",
  "view": 1
}
```
