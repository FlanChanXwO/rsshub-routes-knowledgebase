# 机核网 - 用户播客

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/users/:id/radios`
- Route Name: `用户播客`
- Example: `/gcores/users/31418/radios`
- URL: `www.gcores.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `DzmingLi`
- Source Location: `user-radios.ts`
- Source Module: `() => import('@/routes/gcores/user-radios.ts')`

## Description
::: tip
若订阅用户 [这样重这样轻](https://www.gcores.com/users/31418) 发布的播客，网址为 `https://www.gcores.com/users/31418`，请截取 `https://www.gcores.com/users/` 之后的部分 `31418` 作为 `id` 参数填入，此时目标路由为 [`/gcores/users/31418/radios`](https://rsshub.app/gcores/users/31418/radios)。
:::

## Parameters
- `id`: {"description": "用户 ID，可在用户主页 URL 中找到"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.gcores.com/users/:id/content`
  - `www.gcores.com/users/:id`
- `target`: `/users/:id/radios`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若订阅用户 [这样重这样轻](https://www.gcores.com/users/31418) 发布的播客，网址为 `https://www.gcores.com/users/31418`，请截取 `https://www.gcores.com/users/` 之后的部分 `31418` 作为 `id` 参数填入，此时目标路由为 [`/gcores/users/31418/radios`](https://rsshub.app/gcores/users/31418/radios)。\n:::\n",
  "example": "/gcores/users/31418/radios",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "user-radios.ts",
  "maintainers": [
    "DzmingLi"
  ],
  "module": "() => import('@/routes/gcores/user-radios.ts')",
  "name": "用户播客",
  "parameters": {
    "id": {
      "description": "用户 ID，可在用户主页 URL 中找到"
    }
  },
  "path": "/users/:id/radios",
  "radar": [
    {
      "source": [
        "www.gcores.com/users/:id/content",
        "www.gcores.com/users/:id"
      ],
      "target": "/users/:id/radios"
    }
  ],
  "url": "www.gcores.com",
  "view": 4
}
```
