# 10000万联网 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `10000link`
- Namespace Name: `10000万联网`
- Route Path: `/10000link/info/:category?/:id?`
- Route Name: `新闻`
- Example: `/10000link/info/newslists/My01`
- URL: `info.10000link.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `info.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [天下大势](https://info.10000link.com/newslists.aspx?chid=My01)，网址为 `https://info.10000link.com/newslists.aspx?chid=My01`，请截取 `https://info.10000link.com/` 到末尾 `.aspx` 的部分 `newslists` 作为 `category` 参数填入，而 `My01` 作为 `id` 参数填入，此时目标路由为 [`/10000link/info/newslists/My01`](https://rsshub.app/10000link/info/newslists/My01)。
:::

| 金融科技      | 物流          | 供应链金融风控 | 区块链         | B2B       |
| ------------- | ------------- | -------------- | -------------- | --------- |
| newsFinancial | newslogistics | newsRisk       | newsBlockChain | newsBTwoB |

| 跨境电商        | 投融资         | 供应链管理     | 供应链创新     | 数据          |
| --------------- | -------------- | -------------- | -------------- | ------------- |
| newsCrossborder | newsInvestment | newsManagement | newsInnovation | newslists/A02 |

| 政策          | 规划          | 案例           | 职场         | 供应链票据 |
| ------------- | ------------- | -------------- | ------------ | ---------- |
| newslists/A03 | newslists/A04 | newslists/GL03 | newslists/ZC | newsBill   |

## Parameters
- `category`: {"description": "分类，默认为 `newslists`，可在对应分类页 URL 中找到", "options": [{"label": "新闻", "value": "newslists"}, {"label": "物流", "value": "newslogistics"}, {"label": "供应链金融风控", "value": "newsRisk"}, {"label": "区块链", "value": "newsBlockChain"}, {"label": "B2B", "value": "newsBTwoB"}, {"label": "跨境电商", "value": "newsCrossborder"}, {"label": "投融资", "value": "newsInvestment"}, {"label": "供应链管理", "value": "newsManagement"}, {"label": "供应链创新", "value": "newsInnovation"}, {"label": "数据", "value": "newslists/A02"}, {"label": "政策", "value": "newslists/A03"}, {"label": "规划", "value": "newslists/A04"}, {"label": "案例", "value": "newslists/GL03"}, {"label": "职场", "value": "newslists/ZC"}, {"label": "供应链票据", "value": "newsBill"}]}
- `id`: {"description": "ID，默认为空，可在对应分类页 URL 中找到"}


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
  - `info.10000link.com/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [天下大势](https://info.10000link.com/newslists.aspx?chid=My01)，网址为 `https://info.10000link.com/newslists.aspx?chid=My01`，请截取 `https://info.10000link.com/` 到末尾 `.aspx` 的部分 `newslists` 作为 `category` 参数填入，而 `My01` 作为 `id` 参数填入，此时目标路由为 [`/10000link/info/newslists/My01`](https://rsshub.app/10000link/info/newslists/My01)。\n:::\n\n| 金融科技      | 物流          | 供应链金融风控 | 区块链         | B2B       |\n| ------------- | ------------- | -------------- | -------------- | --------- |\n| newsFinancial | newslogistics | newsRisk       | newsBlockChain | newsBTwoB |\n\n| 跨境电商        | 投融资         | 供应链管理     | 供应链创新     | 数据          |\n| --------------- | -------------- | -------------- | -------------- | ------------- |\n| newsCrossborder | newsInvestment | newsManagement | newsInnovation | newslists/A02 |\n\n| 政策          | 规划          | 案例           | 职场         | 供应链票据 |\n| ------------- | ------------- | -------------- | ------------ | ---------- |\n| newslists/A03 | newslists/A04 | newslists/GL03 | newslists/ZC | newsBill   |",
  "example": "/10000link/info/newslists/My01",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 11,
  "location": "info.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新闻",
  "parameters": {
    "category": {
      "description": "分类，默认为 `newslists`，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "新闻",
          "value": "newslists"
        },
        {
          "label": "物流",
          "value": "newslogistics"
        },
        {
          "label": "供应链金融风控",
          "value": "newsRisk"
        },
        {
          "label": "区块链",
          "value": "newsBlockChain"
        },
        {
          "label": "B2B",
          "value": "newsBTwoB"
        },
        {
          "label": "跨境电商",
          "value": "newsCrossborder"
        },
        {
          "label": "投融资",
          "value": "newsInvestment"
        },
        {
          "label": "供应链管理",
          "value": "newsManagement"
        },
        {
          "label": "供应链创新",
          "value": "newsInnovation"
        },
        {
          "label": "数据",
          "value": "newslists/A02"
        },
        {
          "label": "政策",
          "value": "newslists/A03"
        },
        {
          "label": "规划",
          "value": "newslists/A04"
        },
        {
          "label": "案例",
          "value": "newslists/GL03"
        },
        {
          "label": "职场",
          "value": "newslists/ZC"
        },
        {
          "label": "供应链票据",
          "value": "newsBill"
        }
      ]
    },
    "id": {
      "description": "ID，默认为空，可在对应分类页 URL 中找到"
    }
  },
  "path": "/info/:category?/:id?",
  "radar": [
    {
      "source": [
        "info.10000link.com/:category"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "风控不是业务的敌人！46号令终身问责背景下，国企供应链风控如何从“背锅侠”逆袭成“护航员”？ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "138893356640117760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://info.10000link.com/newslists.aspx?chid=My01",
      "title": "10000万联网 - 风控不是业务的敌人！46号令终身问责背景下，国企供应链风控如何从“背锅侠”逆袭成“护航员”？",
      "type": "feed",
      "url": "rsshub://10000link/info/newslists/My01"
    },
    {
      "description": "开票受限、业务被叫停！2026央国企贸易圈大清洗：融资性贸易、开票经济一个不留，再不懂全流程合规与风控，下个被追责的就是你！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "166018536566226944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://info.10000link.com/newslists.aspx",
      "title": "10000万联网 - 开票受限、业务被叫停！2026央国企贸易圈大清洗：融资性贸易、开票经济一个不留，再不懂全流程合规与风控，下个被追责的就是你！",
      "type": "feed",
      "url": "rsshub://10000link/info"
    }
  ],
  "url": "info.10000link.com",
  "view": 0
}
```
