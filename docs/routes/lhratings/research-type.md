# 联合资信评估股份有限公司 - 研究报告

## Coverage
`index-only`

## Route
- Namespace: `lhratings`
- Namespace Name: `联合资信评估股份有限公司`
- Route Path: `/research/:type?`
- Route Name: `研究报告`
- Example: `/lhratings/research/1`
- URL: `www.lhratings.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `research.ts`
- Source Module: `() => import('@/routes/lhratings/research.ts')`

## Description
::: tip
若订阅 [宏观经济](https://www.lhratings.com/research.html?type=1)，网址为 `https://www.lhratings.com/research.html?type=1`，请截取 `https://www.lhratings.com/research.html?type=` 到末尾的部分 `1` 作为 `type` 参数填入，此时目标路由为 [`/lhratings/research/1`](https://rsshub.app/lhratings/research/1)。
:::

| 宏观经济 | 债券市场 | 行业研究 | 评级理论与方法 | 国际债券市场与评级 | 评级表现 |
| -------- | -------- | -------- | -------------- | ------------------ | -------- |
| 1        | 2        | 3        | 4              | 5                  | 6        |

## Parameters
- `type`: 分类，默认为 `1`，即宏观经济，可在对应分类页 URL 中找到


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
  - `www.lhratings.com/research.html`
### Rule 2
- `title`: `宏观经济`
- `source`:
  - `www.lhratings.com/research.html?type=1`
- `target`: `/research/1`
### Rule 3
- `title`: `债券市场`
- `source`:
  - `www.lhratings.com/research.html?type=2`
- `target`: `/research/2`
### Rule 4
- `title`: `行业研究`
- `source`:
  - `www.lhratings.com/research.html?type=3`
- `target`: `/research/3`
### Rule 5
- `title`: `评级理论与方法`
- `source`:
  - `www.lhratings.com/research.html?type=4`
- `target`: `/research/4`
### Rule 6
- `title`: `国际债券市场与评级`
- `source`:
  - `www.lhratings.com/research.html?type=5`
- `target`: `/research/5`
### Rule 7
- `title`: `评级表现`
- `source`:
  - `www.lhratings.com/research.html?type=6`
- `target`: `/research/6`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n若订阅 [宏观经济](https://www.lhratings.com/research.html?type=1)，网址为 `https://www.lhratings.com/research.html?type=1`，请截取 `https://www.lhratings.com/research.html?type=` 到末尾的部分 `1` 作为 `type` 参数填入，此时目标路由为 [`/lhratings/research/1`](https://rsshub.app/lhratings/research/1)。\n:::\n\n| 宏观经济 | 债券市场 | 行业研究 | 评级理论与方法 | 国际债券市场与评级 | 评级表现 |\n| -------- | -------- | -------- | -------------- | ------------------ | -------- |\n| 1        | 2        | 3        | 4              | 5                  | 6        |\n",
  "example": "/lhratings/research/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "research.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/lhratings/research.ts')",
  "name": "研究报告",
  "parameters": {
    "type": "分类，默认为 `1`，即宏观经济，可在对应分类页 URL 中找到"
  },
  "path": "/research/:type?",
  "radar": [
    {
      "source": [
        "www.lhratings.com/research.html"
      ]
    },
    {
      "source": [
        "www.lhratings.com/research.html?type=1"
      ],
      "target": "/research/1",
      "title": "宏观经济"
    },
    {
      "source": [
        "www.lhratings.com/research.html?type=2"
      ],
      "target": "/research/2",
      "title": "债券市场"
    },
    {
      "source": [
        "www.lhratings.com/research.html?type=3"
      ],
      "target": "/research/3",
      "title": "行业研究"
    },
    {
      "source": [
        "www.lhratings.com/research.html?type=4"
      ],
      "target": "/research/4",
      "title": "评级理论与方法"
    },
    {
      "source": [
        "www.lhratings.com/research.html?type=5"
      ],
      "target": "/research/5",
      "title": "国际债券市场与评级"
    },
    {
      "source": [
        "www.lhratings.com/research.html?type=6"
      ],
      "target": "/research/6",
      "title": "评级表现"
    }
  ],
  "url": "www.lhratings.com",
  "view": 0
}
```
