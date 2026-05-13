# 国家能源局 - 中华人民共和国交通运输部

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/mot/:category{.+}?`
- Route Name: `中华人民共和国交通运输部`
- Example: `/gov/mot/jiaotongyaowen`
- URL: `www.mot.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `ladeng07, nczitzk`
- Source Location: `mot/index.ts`
- Source Module: `() => import('@/routes/gov/mot/index.ts')`

## Description
::: tip
若订阅 [重要会议](https://www.mot.gov.cn/zhongyaohuiyi/)，网址为 `https://www.mot.gov.cn/zhongyaohuiyi/`，请截取 `https://www.mot.gov.cn/` 到末尾 `/` 的部分 `zhongyaohuiyi` 作为 `category` 参数填入，此时目标路由为 [`/gov/mot/zhongyaohuiyi`](https://rsshub.app/gov/mot/zhongyaohuiyi)。
:::

## Parameters
- `category`: {"description": "分类，默认为 `jiaotongyaowen`，即交通要闻，可在对应分类页 URL 中找到", "options": [{"label": "交通要闻", "value": "jiaotongyaowen"}, {"label": "时政要闻", "value": "shizhengyaowen"}, {"label": "重要会议", "value": "zhongyaohuiyi"}]}


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
  - `www.mot.gov.cn/:category`
### Rule 2
- `title`: `交通要闻`
- `source`:
  - `www.mot.gov.cn/jiaotongyaowen/`
- `target`: `/mot/jiaotongyaowen`
### Rule 3
- `title`: `时政要闻`
- `source`:
  - `www.mot.gov.cn/shizhengyaowen/`
- `target`: `/mot/shizhengyaowen`
### Rule 4
- `title`: `重要会议`
- `source`:
  - `www.mot.gov.cn/zhongyaohuiyi/`
- `target`: `/mot/zhongyaohuiyi`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n若订阅 [重要会议](https://www.mot.gov.cn/zhongyaohuiyi/)，网址为 `https://www.mot.gov.cn/zhongyaohuiyi/`，请截取 `https://www.mot.gov.cn/` 到末尾 `/` 的部分 `zhongyaohuiyi` 作为 `category` 参数填入，此时目标路由为 [`/gov/mot/zhongyaohuiyi`](https://rsshub.app/gov/mot/zhongyaohuiyi)。\n:::",
  "example": "/gov/mot/jiaotongyaowen",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "mot/index.ts",
  "maintainers": [
    "ladeng07",
    "nczitzk"
  ],
  "module": "() => import('@/routes/gov/mot/index.ts')",
  "name": "中华人民共和国交通运输部",
  "parameters": {
    "category": {
      "description": "分类，默认为 `jiaotongyaowen`，即交通要闻，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "交通要闻",
          "value": "jiaotongyaowen"
        },
        {
          "label": "时政要闻",
          "value": "shizhengyaowen"
        },
        {
          "label": "重要会议",
          "value": "zhongyaohuiyi"
        }
      ]
    }
  },
  "path": "/mot/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.mot.gov.cn/:category"
      ]
    },
    {
      "source": [
        "www.mot.gov.cn/jiaotongyaowen/"
      ],
      "target": "/mot/jiaotongyaowen",
      "title": "交通要闻"
    },
    {
      "source": [
        "www.mot.gov.cn/shizhengyaowen/"
      ],
      "target": "/mot/shizhengyaowen",
      "title": "时政要闻"
    },
    {
      "source": [
        "www.mot.gov.cn/zhongyaohuiyi/"
      ],
      "target": "/mot/zhongyaohuiyi",
      "title": "重要会议"
    }
  ],
  "url": "www.mot.gov.cn",
  "view": 0
}
```
