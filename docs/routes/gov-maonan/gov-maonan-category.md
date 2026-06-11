# 茂名市茂南区人民政府 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov/maonan`
- Namespace Name: `茂名市茂南区人民政府`
- Route Path: `/gov/maonan/:category`
- Route Name: `通用`
- Example: `/gov/maonan/zwgk`
- URL: `www.maonan.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `ShuiHuo`
- Source Location: `maonan.ts`
- Source Module: `_None_`

## Description
| 政务公开 | 政务新闻 | 茂南动态 | 重大会议 | 公告公示 | 招录信息 | 政策解读 |
| :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|   zwgk   |   zwxw   |   mndt   |   zdhy   |   tzgg   |   zlxx   |   zcjd   |

## Parameters
- `category`: 分类名


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `政务公开`
- `source`:
  - `www.maonan.gov.cn/zwgk/*path`
- `target`: `/zwgk`
### Rule 2
- `title`: `政务新闻`
- `source`:
  - `www.maonan.gov.cn/zwxw/*path`
- `target`: `/zwxw`
### Rule 3
- `title`: `茂南动态`
- `source`:
  - `www.maonan.gov.cn/zwxw/mndt/*path`
- `target`: `/mndt`
### Rule 4
- `title`: `重大会议`
- `source`:
  - `www.maonan.gov.cn/zwxw/zdhy/*path`
- `target`: `/zdhy`
### Rule 5
- `title`: `公告公示`
- `source`:
  - `www.maonan.gov.cn/zwgk/tzgg/*path`
- `target`: `/tzgg`
### Rule 6
- `title`: `招录信息`
- `source`:
  - `www.maonan.gov.cn/zwgk/zlxx/*path`
- `target`: `/zlxx`
### Rule 7
- `title`: `政策解读`
- `source`:
  - `www.maonan.gov.cn/zwgk/zcjd/*path`
- `target`: `/zcjd`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 政务公开 | 政务新闻 | 茂南动态 | 重大会议 | 公告公示 | 招录信息 | 政策解读 |\n| :------: | :------: | :------: | :------: | :------: | :------: | :------: |\n|   zwgk   |   zwxw   |   mndt   |   zdhy   |   tzgg   |   zlxx   |   zcjd   |",
  "example": "/gov/maonan/zwgk",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "maonan.ts",
  "maintainers": [
    "ShuiHuo"
  ],
  "name": "通用",
  "parameters": {
    "category": "分类名"
  },
  "path": "/:category",
  "radar": [
    {
      "source": [
        "www.maonan.gov.cn/zwgk/*path"
      ],
      "target": "/zwgk",
      "title": "政务公开"
    },
    {
      "source": [
        "www.maonan.gov.cn/zwxw/*path"
      ],
      "target": "/zwxw",
      "title": "政务新闻"
    },
    {
      "source": [
        "www.maonan.gov.cn/zwxw/mndt/*path"
      ],
      "target": "/mndt",
      "title": "茂南动态"
    },
    {
      "source": [
        "www.maonan.gov.cn/zwxw/zdhy/*path"
      ],
      "target": "/zdhy",
      "title": "重大会议"
    },
    {
      "source": [
        "www.maonan.gov.cn/zwgk/tzgg/*path"
      ],
      "target": "/tzgg",
      "title": "公告公示"
    },
    {
      "source": [
        "www.maonan.gov.cn/zwgk/zlxx/*path"
      ],
      "target": "/zlxx",
      "title": "招录信息"
    },
    {
      "source": [
        "www.maonan.gov.cn/zwgk/zcjd/*path"
      ],
      "target": "/zcjd",
      "title": "政策解读"
    }
  ],
  "topFeeds": []
}
```
