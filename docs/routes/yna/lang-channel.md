# Yonhap News Agency - News

## Coverage
`index-only`

## Route
- Namespace: `yna`
- Namespace Name: `Yonhap News Agency`
- Route Path: `/:lang?/:channel?`
- Route Name: `News`
- Example: `/yna/en/national`
- URL: `yna.co.kr`
- Language: `ko`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/yna/index.ts')`

## Description
| Language  | 한국어 | English | 简体中文 | 日本語 | عربي   | Español | Français |
| --------- | ------ | ------- | -------- | ------ | ------ | ------- | -------- |
| `:lang` | `ko` | `en`  | `cn`   | `jp` | `ar` | `es`  | `fr`   |

For a full list of RSS Feed Channels, please refer to the RSS feed page of the corresponding language
| RSS Feed Page                                             |
| --------------------------------------------------------- |
| [한국어](https://www.yna.co.kr/rss/index?site=footer_rss) |
| [English](https://en.yna.co.kr/channel/index)             |
| [简体中文](https://cn.yna.co.kr/channel/index)            |
| [日本語](https://jp.yna.co.kr/channel/index)              |
| [عربي](https://ar.yna.co.kr/channel/index)                |
| [Español](https://sp.yna.co.kr/channel/index)             |
| [Français](https://fr.yna.co.kr/channel/index)            |

::: tip
For example, the path for the RSS feed url https://www.yna.co.kr/rss/economy.xml and https://cn.yna.co.kr/RSS/news.xml would be `/ko/economy` and `/cn/news` respectively. 
:::

## Parameters
- `lang`: Language, see below, `ko` by default
- `channel`: RSS Feed Channel, see below, `news` by default


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "\n| Language  | 한국어 | English | 简体中文 | 日本語 | عربي   | Español | Français |\n| --------- | ------ | ------- | -------- | ------ | ------ | ------- | -------- |\n| `:lang` | `ko` | `en`  | `cn`   | `jp` | `ar` | `es`  | `fr`   |\n\nFor a full list of RSS Feed Channels, please refer to the RSS feed page of the corresponding language\n| RSS Feed Page                                             |\n| --------------------------------------------------------- |\n| [한국어](https://www.yna.co.kr/rss/index?site=footer_rss) |\n| [English](https://en.yna.co.kr/channel/index)             |\n| [简体中文](https://cn.yna.co.kr/channel/index)            |\n| [日本語](https://jp.yna.co.kr/channel/index)              |\n| [عربي](https://ar.yna.co.kr/channel/index)                |\n| [Español](https://sp.yna.co.kr/channel/index)             |\n| [Français](https://fr.yna.co.kr/channel/index)            |\n\n::: tip\nFor example, the path for the RSS feed url https://www.yna.co.kr/rss/economy.xml and https://cn.yna.co.kr/RSS/news.xml would be `/ko/economy` and `/cn/news` respectively. \n:::\n",
  "example": "/yna/en/national",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "module": "() => import('@/routes/yna/index.ts')",
  "name": "News",
  "parameters": {
    "channel": "RSS Feed Channel, see below, `news` by default",
    "lang": "Language, see below, `ko` by default"
  },
  "path": "/:lang?/:channel?"
}
```
