# 北京大学 - 人事处

## Coverage
`index-only`

## Route
- Namespace: `pku`
- Namespace Name: `北京大学`
- Route Path: `/pku/hr/:category?`
- Route Name: `人事处`
- Example: `/pku/hr`
- URL: `hr.pku.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `hr.ts`
- Source Module: `_None_`

## Description
::: tip
分类字段处填写的是对应北京大学人事处分类页网址中介于 **`http://hr.pku.edu.cn/`** 和 **/index.htm** 中间的一段，并将其中的 `/` 修改为 `-`。

如 [北京大学人事处 - 人才招聘 - 教师 - 教学科研人员](https://hr.pku.edu.cn/rczp/js/jxkyry/index.htm) 的网址为 `https://hr.pku.edu.cn/rczp/js/jxkyry/index.htm` 其中介于 **`http://hr.pku.edu.cn/`** 和 **`/index.ht`** 中间的一段为 `rczp/js/jxkyry`。随后，并将其中的 `/` 修改为 `-`，可以得到 `rczp-js-jxkyry`。所以最终我们的路由为 [`/pku/hr/rczp-js-jxkyry`](https://rsshub.app/pku/hr/rczp-js-jxkyry)
:::

## Parameters
- `category`: 分类，见下方说明，默认为首页最新公告


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `hr.pku.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n分类字段处填写的是对应北京大学人事处分类页网址中介于 **`http://hr.pku.edu.cn/`** 和 **/index.htm** 中间的一段，并将其中的 `/` 修改为 `-`。\n\n如 [北京大学人事处 - 人才招聘 - 教师 - 教学科研人员](https://hr.pku.edu.cn/rczp/js/jxkyry/index.htm) 的网址为 `https://hr.pku.edu.cn/rczp/js/jxkyry/index.htm` 其中介于 **`http://hr.pku.edu.cn/`** 和 **`/index.ht`** 中间的一段为 `rczp/js/jxkyry`。随后，并将其中的 `/` 修改为 `-`，可以得到 `rczp-js-jxkyry`。所以最终我们的路由为 [`/pku/hr/rczp-js-jxkyry`](https://rsshub.app/pku/hr/rczp-js-jxkyry)\n:::",
  "example": "/pku/hr",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "hr.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "人事处",
  "parameters": {
    "category": "分类，见下方说明，默认为首页最新公告"
  },
  "path": "/hr/:category?",
  "radar": [
    {
      "source": [
        "hr.pku.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "hr.pku.edu.cn/"
}
```
