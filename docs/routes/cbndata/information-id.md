# CBNData - 看点

## Coverage
`index-only`

## Route
- Namespace: `cbndata`
- Namespace Name: `CBNData`
- Route Path: `/information/:id?`
- Route Name: `看点`
- Example: `/cbndata/information/all`
- URL: `www.cbndata.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `information.ts`
- Source Module: `() => import('@/routes/cbndata/information.ts')`

## Description
::: tip
订阅 [美妆个护](https://www.cbndata.com/information?tag_id=1)，其源网址为 `https://www.cbndata.com/information?tag_id=1`，请参考该 URL 指定部分构成参数，此时路由为 [`/cbndata/information/1`](https://rsshub.app/cbndata/information/1)。
:::

| 分类                                                        | ID                                                  |
| ----------------------------------------------------------- | --------------------------------------------------- |
| [全部](https://www.cbndata.com/information?tag_id=all)      | [all](https://rsshub.app/cbndata/information/all)   |
| [美妆个护](https://www.cbndata.com/information?tag_id=1)    | [1](https://rsshub.app/cbndata/information/1)       |
| [服饰鞋包](https://www.cbndata.com/information?tag_id=2559) | [2559](https://rsshub.app/cbndata/information/2559) |
| [宠物](https://www.cbndata.com/information?tag_id=2419)     | [2419](https://rsshub.app/cbndata/information/2419) |
| [营销](https://www.cbndata.com/information?tag_id=2484)     | [2484](https://rsshub.app/cbndata/information/2484) |

## Parameters
- `id`: {"description": "分类，默认为 `all`，即全部，可在对应分类页 URL 中找到", "options": [{"label": "全部", "value": "all"}, {"label": "美妆个护", "value": "1"}, {"label": "服饰鞋包", "value": "2559"}, {"label": "宠物", "value": "2419"}, {"label": "营销", "value": "2484"}]}


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
  - `www.cbndata.com/information`
### Rule 2
- `title`: `全部`
- `source`:
  - `www.cbndata.com/information`
- `target`: `/information/all`
### Rule 3
- `title`: `美妆个护`
- `source`:
  - `www.cbndata.com/information`
- `target`: `/information/1`
### Rule 4
- `title`: `服饰鞋包`
- `source`:
  - `www.cbndata.com/information`
- `target`: `/information/2559`
### Rule 5
- `title`: `宠物`
- `source`:
  - `www.cbndata.com/information`
- `target`: `/information/2419`
### Rule 6
- `title`: `营销`
- `source`:
  - `www.cbndata.com/information`
- `target`: `/information/2484`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n订阅 [美妆个护](https://www.cbndata.com/information?tag_id=1)，其源网址为 `https://www.cbndata.com/information?tag_id=1`，请参考该 URL 指定部分构成参数，此时路由为 [`/cbndata/information/1`](https://rsshub.app/cbndata/information/1)。\n:::\n\n| 分类                                                        | ID                                                  |\n| ----------------------------------------------------------- | --------------------------------------------------- |\n| [全部](https://www.cbndata.com/information?tag_id=all)      | [all](https://rsshub.app/cbndata/information/all)   |\n| [美妆个护](https://www.cbndata.com/information?tag_id=1)    | [1](https://rsshub.app/cbndata/information/1)       |\n| [服饰鞋包](https://www.cbndata.com/information?tag_id=2559) | [2559](https://rsshub.app/cbndata/information/2559) |\n| [宠物](https://www.cbndata.com/information?tag_id=2419)     | [2419](https://rsshub.app/cbndata/information/2419) |\n| [营销](https://www.cbndata.com/information?tag_id=2484)     | [2484](https://rsshub.app/cbndata/information/2484) |\n",
  "example": "/cbndata/information/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "information.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/cbndata/information.ts')",
  "name": "看点",
  "parameters": {
    "id": {
      "description": "分类，默认为 `all`，即全部，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "全部",
          "value": "all"
        },
        {
          "label": "美妆个护",
          "value": "1"
        },
        {
          "label": "服饰鞋包",
          "value": "2559"
        },
        {
          "label": "宠物",
          "value": "2419"
        },
        {
          "label": "营销",
          "value": "2484"
        }
      ]
    }
  },
  "path": "/information/:id?",
  "radar": [
    {
      "source": [
        "www.cbndata.com/information"
      ]
    },
    {
      "source": [
        "www.cbndata.com/information"
      ],
      "target": "/information/all",
      "title": "全部"
    },
    {
      "source": [
        "www.cbndata.com/information"
      ],
      "target": "/information/1",
      "title": "美妆个护"
    },
    {
      "source": [
        "www.cbndata.com/information"
      ],
      "target": "/information/2559",
      "title": "服饰鞋包"
    },
    {
      "source": [
        "www.cbndata.com/information"
      ],
      "target": "/information/2419",
      "title": "宠物"
    },
    {
      "source": [
        "www.cbndata.com/information"
      ],
      "target": "/information/2484",
      "title": "营销"
    }
  ],
  "url": "www.cbndata.com",
  "view": 0
}
```
