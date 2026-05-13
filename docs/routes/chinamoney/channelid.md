# 中国货币网 - 公告

## Coverage
`index-only`

## Route
- Namespace: `chinamoney`
- Namespace Name: `中国货币网`
- Route Path: `/:channelId?`
- Route Name: `公告`
- Example: `/chinamoney`
- URL: `chinamoney.com.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `notice.ts`
- Source Module: `() => import('@/routes/chinamoney/notice.ts')`

## Description
<details>
<summary>市场公告</summary>

    外汇市场公告

| 最新 | 市场公告通知 | 中心会员公告 | 会员信息公告 |
| ---- | ------------ | ------------ | ------------ |
| 2834 | 2835         | 2836         | 2837         |

    本币市场公告

| 最新           | 市场公告通知 | 中心会员公告 | 会员信息公告 |
| -------------- | ------------ | ------------ | ------------ |
| 2839,2840,2841 | 2839         | 2840         | 2841         |

    央行业务公告

| 最新      | 公开市场操作 | 中央国库现金管理 |
| --------- | ------------ | ---------------- |
| 2845,2846 | 2845         | 2846             |
</details>

<details>
<summary>本币市场</summary>

    贷款市场报价利率

| LPR 市场公告 |
| ------------ |
| 3686         |
</details>

## Parameters
- `channelId`: 分类，见下表，默认为 `2834`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "<details>\n<summary>市场公告</summary>\n\n    外汇市场公告\n\n| 最新 | 市场公告通知 | 中心会员公告 | 会员信息公告 |\n| ---- | ------------ | ------------ | ------------ |\n| 2834 | 2835         | 2836         | 2837         |\n\n    本币市场公告\n\n| 最新           | 市场公告通知 | 中心会员公告 | 会员信息公告 |\n| -------------- | ------------ | ------------ | ------------ |\n| 2839,2840,2841 | 2839         | 2840         | 2841         |\n\n    央行业务公告\n\n| 最新      | 公开市场操作 | 中央国库现金管理 |\n| --------- | ------------ | ---------------- |\n| 2845,2846 | 2845         | 2846             |\n</details>\n\n<details>\n<summary>本币市场</summary>\n\n    贷款市场报价利率\n\n| LPR 市场公告 |\n| ------------ |\n| 3686         |\n</details>",
  "example": "/chinamoney",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "notice.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/chinamoney/notice.ts')",
  "name": "公告",
  "parameters": {
    "channelId": "分类，见下表，默认为 `2834`"
  },
  "path": "/:channelId?"
}
```
