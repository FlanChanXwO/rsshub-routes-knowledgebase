# 游侠网 - 大侠号

## Coverage
`index-only`

## Route
- Namespace: `ali213`
- Namespace Name: `游侠网`
- Route Path: `/zl/:category?`
- Route Name: `大侠号`
- Example: `/ali213/zl`
- URL: `www.ali213.net`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `zl.ts`
- Source Module: `() => import('@/routes/ali213/zl.ts')`

## Description
::: tip
若订阅 [游戏](https://www.ali213.net/news/zl/game/)，网址为 `https://www.ali213.net/news/zl/game/`，请截取 `https://www.ali213.net/news/zl/` 到末尾 `/` 的部分 `game` 作为 `category` 参数填入，此时目标路由为 [`/ali213/zl/game`](https://rsshub.app/ali213/zl/game)。
:::

| 首页                                     | 游戏                                         | 动漫                                           | 影视                                           | 娱乐                                           |
| ---------------------------------------- | -------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- |
| [index](https://www.ali213.net/news/zl/) | [game](https://www.ali213.net/news/zl/game/) | [comic](https://www.ali213.net/news/zl/comic/) | [movie](https://www.ali213.net/news/zl/movie/) | [amuse](https://www.ali213.net/news/zl/amuse/) |

## Parameters
- `category`: 分类，默认为首页，可在对应分类页 URL 中找到


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
  - `www.ali213.net/news/zl/:category`
### Rule 2
- `title`: `首页`
- `source`:
  - `www.ali213.net/news/zl/`
- `target`: `/zl`
### Rule 3
- `title`: `游戏`
- `source`:
  - `www.ali213.net/news/zl/game/`
- `target`: `/zl/game`
### Rule 4
- `title`: `动漫`
- `source`:
  - `www.ali213.net/news/zl/comic/`
- `target`: `/zl/comic`
### Rule 5
- `title`: `影视`
- `source`:
  - `www.ali213.net/news/zl/movie/`
- `target`: `/zl/movie`
### Rule 6
- `title`: `娱乐`
- `source`:
  - `www.ali213.net/news/zl/amuse/`
- `target`: `/zl/amuse`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若订阅 [游戏](https://www.ali213.net/news/zl/game/)，网址为 `https://www.ali213.net/news/zl/game/`，请截取 `https://www.ali213.net/news/zl/` 到末尾 `/` 的部分 `game` 作为 `category` 参数填入，此时目标路由为 [`/ali213/zl/game`](https://rsshub.app/ali213/zl/game)。\n:::\n\n| 首页                                     | 游戏                                         | 动漫                                           | 影视                                           | 娱乐                                           |\n| ---------------------------------------- | -------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- |\n| [index](https://www.ali213.net/news/zl/) | [game](https://www.ali213.net/news/zl/game/) | [comic](https://www.ali213.net/news/zl/comic/) | [movie](https://www.ali213.net/news/zl/movie/) | [amuse](https://www.ali213.net/news/zl/amuse/) |\n",
  "example": "/ali213/zl",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "zl.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/ali213/zl.ts')",
  "name": "大侠号",
  "parameters": {
    "category": "分类，默认为首页，可在对应分类页 URL 中找到"
  },
  "path": "/zl/:category?",
  "radar": [
    {
      "source": [
        "www.ali213.net/news/zl/:category"
      ]
    },
    {
      "source": [
        "www.ali213.net/news/zl/"
      ],
      "target": "/zl",
      "title": "首页"
    },
    {
      "source": [
        "www.ali213.net/news/zl/game/"
      ],
      "target": "/zl/game",
      "title": "游戏"
    },
    {
      "source": [
        "www.ali213.net/news/zl/comic/"
      ],
      "target": "/zl/comic",
      "title": "动漫"
    },
    {
      "source": [
        "www.ali213.net/news/zl/movie/"
      ],
      "target": "/zl/movie",
      "title": "影视"
    },
    {
      "source": [
        "www.ali213.net/news/zl/amuse/"
      ],
      "target": "/zl/amuse",
      "title": "娱乐"
    }
  ],
  "url": "www.ali213.net",
  "view": 0
}
```
