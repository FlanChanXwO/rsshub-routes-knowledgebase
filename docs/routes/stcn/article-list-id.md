# 证券时报网 - 列表

## Coverage
`index-only`

## Route
- Namespace: `stcn`
- Namespace Name: `证券时报网`
- Route Path: `/article/list/:id?`
- Route Name: `列表`
- Example: `/stcn/article/list/yw`
- URL: `www.stcn.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/stcn/index.ts')`

## Description
::: tip
若订阅 [要闻](https://www.stcn.com/article/list/yw.html)，网址为 `https://www.stcn.com/article/list/yw.html`，请截取 `https://www.stcn.com/article/list/` 到末尾 `.html` 的部分 `yw` 作为 `id` 参数填入，此时目标路由为 [`/stcn/article/list/yw`](https://rsshub.app/stcn/article/list/yw)。
:::

| 要闻 | 股市 | 公司    | 基金 | 金融    | 评论    |
| ---- | ---- | ------- | ---- | ------- | ------- |
| yw   | gs   | company | fund | finance | comment |

| 产经 | 科创板 | 新三板 | ESG | 滚动 |
| ---- | ------ | ------ | --- | ---- |
| cj   | kcb    | xsb    | zk  | gd   |

## Parameters
- `category`: {"description": "分类，默认为 `yw`，即要闻，可在对应分类页 URL 中找到", "options": [{"label": "要闻", "value": "yw"}, {"label": "股市", "value": "gs"}, {"label": "公司", "value": "company"}, {"label": "基金", "value": "fund"}, {"label": "金融", "value": "finance"}, {"label": "评论", "value": "comment"}, {"label": "产经", "value": "cj"}, {"label": "科创板", "value": "kcb"}, {"label": "新三板", "value": "xsb"}, {"label": "ESG", "value": "zk"}, {"label": "滚动", "value": "gd"}]}


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
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/:id`
### Rule 2
- `title`: `要闻`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/yw.html`
- `target`: `/article/list/yw`
### Rule 3
- `title`: `股市`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/gs.html`
- `target`: `/article/list/gs`
### Rule 4
- `title`: `公司`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/company.html`
- `target`: `/article/list/company`
### Rule 5
- `title`: `基金`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/fund.html`
- `target`: `/article/list/fund`
### Rule 6
- `title`: `金融`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/finance.html`
- `target`: `/article/list/finance`
### Rule 7
- `title`: `评论`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/comment.html`
- `target`: `/article/list/comment`
### Rule 8
- `title`: `产经`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/cj.html`
- `target`: `/article/list/cj`
### Rule 9
- `title`: `科创板`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/kcb.html`
- `target`: `/article/list/kcb`
### Rule 10
- `title`: `新三板`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/xsb.html`
- `target`: `/article/list/xsb`
### Rule 11
- `title`: `ESG`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/zk.html`
- `target`: `/article/list/zk`
### Rule 12
- `title`: `滚动`
- `source`:
  - `www.stcn.com/article/list.html`
  - `www.stcn.com/article/list/gd.html`
- `target`: `/article/list/gd`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n若订阅 [要闻](https://www.stcn.com/article/list/yw.html)，网址为 `https://www.stcn.com/article/list/yw.html`，请截取 `https://www.stcn.com/article/list/` 到末尾 `.html` 的部分 `yw` 作为 `id` 参数填入，此时目标路由为 [`/stcn/article/list/yw`](https://rsshub.app/stcn/article/list/yw)。\n:::\n\n| 要闻 | 股市 | 公司    | 基金 | 金融    | 评论    |\n| ---- | ---- | ------- | ---- | ------- | ------- |\n| yw   | gs   | company | fund | finance | comment |\n\n| 产经 | 科创板 | 新三板 | ESG | 滚动 |\n| ---- | ------ | ------ | --- | ---- |\n| cj   | kcb    | xsb    | zk  | gd   |\n",
  "example": "/stcn/article/list/yw",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/stcn/index.ts')",
  "name": "列表",
  "parameters": {
    "category": {
      "description": "分类，默认为 `yw`，即要闻，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "要闻",
          "value": "yw"
        },
        {
          "label": "股市",
          "value": "gs"
        },
        {
          "label": "公司",
          "value": "company"
        },
        {
          "label": "基金",
          "value": "fund"
        },
        {
          "label": "金融",
          "value": "finance"
        },
        {
          "label": "评论",
          "value": "comment"
        },
        {
          "label": "产经",
          "value": "cj"
        },
        {
          "label": "科创板",
          "value": "kcb"
        },
        {
          "label": "新三板",
          "value": "xsb"
        },
        {
          "label": "ESG",
          "value": "zk"
        },
        {
          "label": "滚动",
          "value": "gd"
        }
      ]
    }
  },
  "path": "/article/list/:id?",
  "radar": [
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/:id"
      ]
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/yw.html"
      ],
      "target": "/article/list/yw",
      "title": "要闻"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/gs.html"
      ],
      "target": "/article/list/gs",
      "title": "股市"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/company.html"
      ],
      "target": "/article/list/company",
      "title": "公司"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/fund.html"
      ],
      "target": "/article/list/fund",
      "title": "基金"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/finance.html"
      ],
      "target": "/article/list/finance",
      "title": "金融"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/comment.html"
      ],
      "target": "/article/list/comment",
      "title": "评论"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/cj.html"
      ],
      "target": "/article/list/cj",
      "title": "产经"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/kcb.html"
      ],
      "target": "/article/list/kcb",
      "title": "科创板"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/xsb.html"
      ],
      "target": "/article/list/xsb",
      "title": "新三板"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/zk.html"
      ],
      "target": "/article/list/zk",
      "title": "ESG"
    },
    {
      "source": [
        "www.stcn.com/article/list.html",
        "www.stcn.com/article/list/gd.html"
      ],
      "target": "/article/list/gd",
      "title": "滚动"
    }
  ],
  "url": "www.stcn.com",
  "view": 0
}
```
