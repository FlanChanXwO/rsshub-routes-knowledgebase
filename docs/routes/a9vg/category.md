# A9VG 电玩部落 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `a9vg`
- Namespace Name: `A9VG 电玩部落`
- Route Path: `/:category{.+}?`
- Route Name: `新闻`
- Example: `/a9vg/news`
- URL: `a9vg.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `monnerHenster, nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/a9vg/index.ts')`

## Description
::: tip
  若订阅 [PS4](http://www.a9vg.com/list/news/PS4)，网址为 `http://www.a9vg.com/list/news/PS4`。截取 `http://www.a9vg.com/list` 到末尾的部分 `news/PS4` 作为参数填入，此时路由为 [`/a9vg/news/PS4`](https://rsshub.app/a9vg/news/PS4)。
:::

| 分类                                               | ID                                                     |
| -------------------------------------------------- | ------------------------------------------------------ |
| [All](https://www.a9vg.com/list/news/All)          | [news/All](https://rsshub.app/a9vg/news/All)           |
| [PS4](https://www.a9vg.com/list/news/PS4)          | [news/PS4](https://rsshub.app/a9vg/news/PS4)           |
| [PS5](https://www.a9vg.com/list/news/PS5)          | [news/PS5](https://rsshub.app/a9vg/news/PS5)           |
| [Switch](https://www.a9vg.com/list/news/Switch)    | [news/Switch](https://rsshub.app/a9vg/news/Switch)     |
| [Xbox One](https://www.a9vg.com/list/news/XboxOne) | [news/XboxOne](https://rsshub.app/a9vg/news/XboxOne)   |
| [XSX](https://www.a9vg.com/list/news/XSX)          | [news/XSX](https://rsshub.app/a9vg/news/XSX)           |
| [PC](https://www.a9vg.com/list/news/PC)            | [news/PC](https://rsshub.app/a9vg/news/PC)             |
| [业界](https://www.a9vg.com/list/news/Industry)    | [news/Industry](https://rsshub.app/a9vg/news/Industry) |
| [厂商](https://www.a9vg.com/list/news/Factory)     | [news/Factory](https://rsshub.app/a9vg/news/Factory)   |

## Parameters
- `category`: 分类，默认为 ，可在对应分类页 URL 中找到, Category, by default


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
  - `www.a9vg.com/list/:category`
### Rule 2
- `title`: `All`
- `source`:
  - `www.a9vg.com/list/news/All`
- `target`: `/news/All`
### Rule 3
- `title`: `PS4`
- `source`:
  - `www.a9vg.com/list/news/PS4`
- `target`: `/news/PS4`
### Rule 4
- `title`: `PS5`
- `source`:
  - `www.a9vg.com/list/news/PS5`
- `target`: `/news/PS5`
### Rule 5
- `title`: `Switch`
- `source`:
  - `www.a9vg.com/list/news/Switch`
- `target`: `/news/Switch`
### Rule 6
- `title`: `Xbox One`
- `source`:
  - `www.a9vg.com/list/news/XboxOne`
- `target`: `/news/XboxOne`
### Rule 7
- `title`: `XSX`
- `source`:
  - `www.a9vg.com/list/news/XSX`
- `target`: `/news/XSX`
### Rule 8
- `title`: `PC`
- `source`:
  - `www.a9vg.com/list/news/PC`
- `target`: `/news/PC`
### Rule 9
- `title`: `业界`
- `source`:
  - `www.a9vg.com/list/news/Industry`
- `target`: `/news/Industry`
### Rule 10
- `title`: `厂商`
- `source`:
  - `www.a9vg.com/list/news/Factory`
- `target`: `/news/Factory`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n  若订阅 [PS4](http://www.a9vg.com/list/news/PS4)，网址为 `http://www.a9vg.com/list/news/PS4`。截取 `http://www.a9vg.com/list` 到末尾的部分 `news/PS4` 作为参数填入，此时路由为 [`/a9vg/news/PS4`](https://rsshub.app/a9vg/news/PS4)。\n:::\n\n| 分类                                               | ID                                                     |\n| -------------------------------------------------- | ------------------------------------------------------ |\n| [All](https://www.a9vg.com/list/news/All)          | [news/All](https://rsshub.app/a9vg/news/All)           |\n| [PS4](https://www.a9vg.com/list/news/PS4)          | [news/PS4](https://rsshub.app/a9vg/news/PS4)           |\n| [PS5](https://www.a9vg.com/list/news/PS5)          | [news/PS5](https://rsshub.app/a9vg/news/PS5)           |\n| [Switch](https://www.a9vg.com/list/news/Switch)    | [news/Switch](https://rsshub.app/a9vg/news/Switch)     |\n| [Xbox One](https://www.a9vg.com/list/news/XboxOne) | [news/XboxOne](https://rsshub.app/a9vg/news/XboxOne)   |\n| [XSX](https://www.a9vg.com/list/news/XSX)          | [news/XSX](https://rsshub.app/a9vg/news/XSX)           |\n| [PC](https://www.a9vg.com/list/news/PC)            | [news/PC](https://rsshub.app/a9vg/news/PC)             |\n| [业界](https://www.a9vg.com/list/news/Industry)    | [news/Industry](https://rsshub.app/a9vg/news/Industry) |\n| [厂商](https://www.a9vg.com/list/news/Factory)     | [news/Factory](https://rsshub.app/a9vg/news/Factory)   |\n  ",
  "example": "/a9vg/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "monnerHenster",
    "nczitzk"
  ],
  "module": "() => import('@/routes/a9vg/index.ts')",
  "name": "新闻",
  "parameters": {
    "category": "分类，默认为 ，可在对应分类页 URL 中找到, Category, by default"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.a9vg.com/list/:category"
      ]
    },
    {
      "source": [
        "www.a9vg.com/list/news/All"
      ],
      "target": "/news/All",
      "title": "All"
    },
    {
      "source": [
        "www.a9vg.com/list/news/PS4"
      ],
      "target": "/news/PS4",
      "title": "PS4"
    },
    {
      "source": [
        "www.a9vg.com/list/news/PS5"
      ],
      "target": "/news/PS5",
      "title": "PS5"
    },
    {
      "source": [
        "www.a9vg.com/list/news/Switch"
      ],
      "target": "/news/Switch",
      "title": "Switch"
    },
    {
      "source": [
        "www.a9vg.com/list/news/XboxOne"
      ],
      "target": "/news/XboxOne",
      "title": "Xbox One"
    },
    {
      "source": [
        "www.a9vg.com/list/news/XSX"
      ],
      "target": "/news/XSX",
      "title": "XSX"
    },
    {
      "source": [
        "www.a9vg.com/list/news/PC"
      ],
      "target": "/news/PC",
      "title": "PC"
    },
    {
      "source": [
        "www.a9vg.com/list/news/Industry"
      ],
      "target": "/news/Industry",
      "title": "业界"
    },
    {
      "source": [
        "www.a9vg.com/list/news/Factory"
      ],
      "target": "/news/Factory",
      "title": "厂商"
    }
  ],
  "url": "a9vg.com"
}
```
