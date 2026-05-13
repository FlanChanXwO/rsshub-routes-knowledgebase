# 中债资信评估有限责任公司 - 中债研究

## Coverage
`index-only`

## Route
- Namespace: `chinaratings`
- Namespace Name: `中债资信评估有限责任公司`
- Route Path: `/CreditResearch/:category{.+}?`
- Route Name: `中债研究`
- Example: `/chinaratings/CreditResearch`
- URL: `www.chinaratings.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `credit-research.ts`
- Source Module: `() => import('@/routes/chinaratings/credit-research.ts')`

## Description
::: tip
若订阅 [行业评论](https://www.chinaratings.com.cn/CreditResearch/Industry/Comment/)，网址为 `https://www.chinaratings.com.cn/CreditResearch/Industry/Comment/`，请截取 `https://www.chinaratings.com.cn/CreditResearch/` 到末尾 `/` 的部分 `Industry/Comment` 作为 `category` 参数填入，此时目标路由为 [`/chinaratings/CreditResearch/Industry/Comment`](https://rsshub.app/chinaratings/CreditResearch/Industry/Comment)。
:::

## Parameters
- `category`: 分类，默认为 `Industry/Comment`，即行业评论，可在对应分类页 URL 中找到


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
  - `www.chinaratings.com.cn/CreditResearch/:category`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n若订阅 [行业评论](https://www.chinaratings.com.cn/CreditResearch/Industry/Comment/)，网址为 `https://www.chinaratings.com.cn/CreditResearch/Industry/Comment/`，请截取 `https://www.chinaratings.com.cn/CreditResearch/` 到末尾 `/` 的部分 `Industry/Comment` 作为 `category` 参数填入，此时目标路由为 [`/chinaratings/CreditResearch/Industry/Comment`](https://rsshub.app/chinaratings/CreditResearch/Industry/Comment)。\n:::\n",
  "example": "/chinaratings/CreditResearch",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "credit-research.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/chinaratings/credit-research.ts')",
  "name": "中债研究",
  "parameters": {
    "category": "分类，默认为 `Industry/Comment`，即行业评论，可在对应分类页 URL 中找到"
  },
  "path": "/CreditResearch/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.chinaratings.com.cn/CreditResearch/:category"
      ]
    }
  ],
  "url": "www.chinaratings.com.cn",
  "view": 0
}
```
