# River.to (江河日下) - 分类

## Coverage
`index-only`

## Route
- Namespace: `the`
- Namespace Name: `River.to (江河日下)`
- Route Path: `/:filter{.+}?`
- Route Name: `分类`
- Example: `/the`
- URL: `river.to`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/the/index.ts')`

## Description
::: tip
  如果你想订阅特定类别或出版物，可以在路由中填写 filter 参数。

  `/category/rawj7o4ypewv94` 可以实现订阅 [时局](https://river.to/occasus/rawj7o4ypewv94) 类别。此时，路由是 [`/the/category/rawj7o4ypewv94/`](https://rsshub.app/the/category/rawj7o4ypewv94).

  也可以直接使用 slug：[`/the/rawj7o4ypewv94`](https://rsshub.app/the/rawj7o4ypewv94)
:::

| 分类                                                      | ID                                                               |
| --------------------------------------------------------- | ---------------------------------------------------------------- |
| [时局](https://river.to/occasus/rawj7o4ypewv94)           | [rawj7o4ypewv94](https://rsshub.app/the/category/rawj7o4ypewv94) |
| [剩余价值](https://river.to/occasus/rawmw7dsta2jew)       | [rawmw7dsta2jew](https://rsshub.app/the/category/rawmw7dsta2jew) |
| [Beijing](https://river.to/occasus/rawbcvxkktdkq8)        | [rawbcvxkktdkq8](https://rsshub.app/the/category/rawbcvxkktdkq8) |
| [稳中向好](https://river.to/occasus/raw4krvx85dh27)       | [raw4krvx85dh27](https://rsshub.app/the/category/raw4krvx85dh27) |
| [水深火热](https://river.to/occasus/rawtn8jpsc6uvv)       | [rawtn8jpsc6uvv](https://rsshub.app/the/category/rawtn8jpsc6uvv) |
| [东升西降](https://river.to/occasus/rawai5kd4z15il)       | [rawai5kd4z15il](https://rsshub.app/the/category/rawai5kd4z15il) |
| [大局](https://river.to/occasus/raw2efkzejrsx8)           | [raw2efkzejrsx8](https://rsshub.app/the/category/raw2efkzejrsx8) |
| [境外势力](https://river.to/occasus/rawmpalhnlphuc)       | [rawmpalhnlphuc](https://rsshub.app/the/category/rawmpalhnlphuc) |
| [副刊](https://river.to/occasus/rawxght2jr2u5z)           | [rawxght2jr2u5z](https://rsshub.app/the/category/rawxght2jr2u5z) |
| [天高地厚](https://river.to/occasus/rawrsnh9zakqdx)       | [rawrsnh9zakqdx](https://rsshub.app/the/category/rawrsnh9zakqdx) |
| [Oyster](https://river.to/occasus/rawdhl9hugdfn9)         | [rawdhl9hugdfn9](https://rsshub.app/the/category/rawdhl9hugdfn9) |

## Parameters
- `filter`: 过滤器，见下方描述


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
  - `river.to/occasus/:category?`
### Rule 2
- `title`: `时局`
- `source`:
  - `river.to/occasus/rawj7o4ypewv94`
- `target`: `/the/category/rawj7o4ypewv94`
### Rule 3
- `title`: `剩余价值`
- `source`:
  - `river.to/occasus/rawmw7dsta2jew`
- `target`: `/the/category/rawmw7dsta2jew`
### Rule 4
- `title`: `Beijing`
- `source`:
  - `river.to/occasus/rawbcvxkktdkq8`
- `target`: `/the/category/rawbcvxkktdkq8`
### Rule 5
- `title`: `稳中向好`
- `source`:
  - `river.to/occasus/raw4krvx85dh27`
- `target`: `/the/category/raw4krvx85dh27`
### Rule 6
- `title`: `水深火热`
- `source`:
  - `river.to/occasus/rawtn8jpsc6uvv`
- `target`: `/the/category/rawtn8jpsc6uvv`
### Rule 7
- `title`: `东升西降`
- `source`:
  - `river.to/occasus/rawai5kd4z15il`
- `target`: `/the/category/rawai5kd4z15il`
### Rule 8
- `title`: `大局`
- `source`:
  - `river.to/occasus/raw2efkzejrsx8`
- `target`: `/the/category/raw2efkzejrsx8`
### Rule 9
- `title`: `境外势力`
- `source`:
  - `river.to/occasus/rawmpalhnlphuc`
- `target`: `/the/category/rawmpalhnlphuc`
### Rule 10
- `title`: `副刊`
- `source`:
  - `river.to/occasus/rawxght2jr2u5z`
- `target`: `/the/category/rawxght2jr2u5z`
### Rule 11
- `title`: `天高地厚`
- `source`:
  - `river.to/occasus/rawrsnh9zakqdx`
- `target`: `/the/category/rawrsnh9zakqdx`
### Rule 12
- `title`: `Oyster`
- `source`:
  - `river.to/occasus/rawdhl9hugdfn9`
- `target`: `/the/category/rawdhl9hugdfn9`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n  如果你想订阅特定类别或出版物，可以在路由中填写 filter 参数。\n\n  `/category/rawj7o4ypewv94` 可以实现订阅 [时局](https://river.to/occasus/rawj7o4ypewv94) 类别。此时，路由是 [`/the/category/rawj7o4ypewv94/`](https://rsshub.app/the/category/rawj7o4ypewv94).\n\n  也可以直接使用 slug：[`/the/rawj7o4ypewv94`](https://rsshub.app/the/rawj7o4ypewv94)\n:::\n\n| 分类                                                      | ID                                                               |\n| --------------------------------------------------------- | ---------------------------------------------------------------- |\n| [时局](https://river.to/occasus/rawj7o4ypewv94)           | [rawj7o4ypewv94](https://rsshub.app/the/category/rawj7o4ypewv94) |\n| [剩余价值](https://river.to/occasus/rawmw7dsta2jew)       | [rawmw7dsta2jew](https://rsshub.app/the/category/rawmw7dsta2jew) |\n| [Beijing](https://river.to/occasus/rawbcvxkktdkq8)        | [rawbcvxkktdkq8](https://rsshub.app/the/category/rawbcvxkktdkq8) |\n| [稳中向好](https://river.to/occasus/raw4krvx85dh27)       | [raw4krvx85dh27](https://rsshub.app/the/category/raw4krvx85dh27) |\n| [水深火热](https://river.to/occasus/rawtn8jpsc6uvv)       | [rawtn8jpsc6uvv](https://rsshub.app/the/category/rawtn8jpsc6uvv) |\n| [东升西降](https://river.to/occasus/rawai5kd4z15il)       | [rawai5kd4z15il](https://rsshub.app/the/category/rawai5kd4z15il) |\n| [大局](https://river.to/occasus/raw2efkzejrsx8)           | [raw2efkzejrsx8](https://rsshub.app/the/category/raw2efkzejrsx8) |\n| [境外势力](https://river.to/occasus/rawmpalhnlphuc)       | [rawmpalhnlphuc](https://rsshub.app/the/category/rawmpalhnlphuc) |\n| [副刊](https://river.to/occasus/rawxght2jr2u5z)           | [rawxght2jr2u5z](https://rsshub.app/the/category/rawxght2jr2u5z) |\n| [天高地厚](https://river.to/occasus/rawrsnh9zakqdx)       | [rawrsnh9zakqdx](https://rsshub.app/the/category/rawrsnh9zakqdx) |\n| [Oyster](https://river.to/occasus/rawdhl9hugdfn9)         | [rawdhl9hugdfn9](https://rsshub.app/the/category/rawdhl9hugdfn9) |\n  ",
  "example": "/the",
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
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/the/index.ts')",
  "name": "分类",
  "parameters": {
    "filter": "过滤器，见下方描述"
  },
  "path": "/:filter{.+}?",
  "radar": [
    {
      "source": [
        "river.to/occasus/:category?"
      ]
    },
    {
      "source": [
        "river.to/occasus/rawj7o4ypewv94"
      ],
      "target": "/the/category/rawj7o4ypewv94",
      "title": "时局"
    },
    {
      "source": [
        "river.to/occasus/rawmw7dsta2jew"
      ],
      "target": "/the/category/rawmw7dsta2jew",
      "title": "剩余价值"
    },
    {
      "source": [
        "river.to/occasus/rawbcvxkktdkq8"
      ],
      "target": "/the/category/rawbcvxkktdkq8",
      "title": "Beijing"
    },
    {
      "source": [
        "river.to/occasus/raw4krvx85dh27"
      ],
      "target": "/the/category/raw4krvx85dh27",
      "title": "稳中向好"
    },
    {
      "source": [
        "river.to/occasus/rawtn8jpsc6uvv"
      ],
      "target": "/the/category/rawtn8jpsc6uvv",
      "title": "水深火热"
    },
    {
      "source": [
        "river.to/occasus/rawai5kd4z15il"
      ],
      "target": "/the/category/rawai5kd4z15il",
      "title": "东升西降"
    },
    {
      "source": [
        "river.to/occasus/raw2efkzejrsx8"
      ],
      "target": "/the/category/raw2efkzejrsx8",
      "title": "大局"
    },
    {
      "source": [
        "river.to/occasus/rawmpalhnlphuc"
      ],
      "target": "/the/category/rawmpalhnlphuc",
      "title": "境外势力"
    },
    {
      "source": [
        "river.to/occasus/rawxght2jr2u5z"
      ],
      "target": "/the/category/rawxght2jr2u5z",
      "title": "副刊"
    },
    {
      "source": [
        "river.to/occasus/rawrsnh9zakqdx"
      ],
      "target": "/the/category/rawrsnh9zakqdx",
      "title": "天高地厚"
    },
    {
      "source": [
        "river.to/occasus/rawdhl9hugdfn9"
      ],
      "target": "/the/category/rawdhl9hugdfn9",
      "title": "Oyster"
    }
  ],
  "url": "river.to"
}
```
