# 北京证券交易所 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `bse`
- Namespace Name: `北京证券交易所`
- Route Path: `/:category?/:keyword?`
- Route Name: `栏目`
- Example: `/bse`
- URL: `bse.cn/`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/bse/index.ts')`

## Description
| 本所要闻        | 人才招聘 | 采购信息 | 业务通知   |
| --------------- | -------- | -------- | ---------- |
| important_news | recruit  | purchase | news_list |

| 法律法规  | 公开征求意见    | 部门规章         | 发行融资   |
| --------- | --------------- | ---------------- | ---------- |
| law_list | public_opinion | regulation_list | fxrz_list |

| 持续监管   | 交易管理   | 市场管理   | 上市委会议公告  |
| ---------- | ---------- | ---------- | --------------- |
| cxjg_list | jygl_list | scgl_list | meeting_notice |

| 上市委会议结果公告 | 上市委会议变更公告 | 并购重组委会议公告 |
| ------------------ | ------------------ | ------------------ |
| meeting_result    | meeting_change    | bgcz_notice       |

| 并购重组委会议结果公告 | 并购重组委会议变更公告 | 终止审核           | 注册结果      |
| ---------------------- | ---------------------- | ------------------ | ------------- |
| bgcz_result           | bgcz_change           | termination_audit | audit_result |

## Parameters
- `category`: 分类，见下表，默认为本所要闻
- `keyword`: 关键字，默认为空


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
  - `bse.cn/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 本所要闻        | 人才招聘 | 采购信息 | 业务通知   |\n| --------------- | -------- | -------- | ---------- |\n| important_news | recruit  | purchase | news_list |\n\n| 法律法规  | 公开征求意见    | 部门规章         | 发行融资   |\n| --------- | --------------- | ---------------- | ---------- |\n| law_list | public_opinion | regulation_list | fxrz_list |\n\n| 持续监管   | 交易管理   | 市场管理   | 上市委会议公告  |\n| ---------- | ---------- | ---------- | --------------- |\n| cxjg_list | jygl_list | scgl_list | meeting_notice |\n\n| 上市委会议结果公告 | 上市委会议变更公告 | 并购重组委会议公告 |\n| ------------------ | ------------------ | ------------------ |\n| meeting_result    | meeting_change    | bgcz_notice       |\n\n| 并购重组委会议结果公告 | 并购重组委会议变更公告 | 终止审核           | 注册结果      |\n| ---------------------- | ---------------------- | ------------------ | ------------- |\n| bgcz_result           | bgcz_change           | termination_audit | audit_result |",
  "example": "/bse",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/bse/index.ts')",
  "name": "栏目",
  "parameters": {
    "category": "分类，见下表，默认为本所要闻",
    "keyword": "关键字，默认为空"
  },
  "path": "/:category?/:keyword?",
  "radar": [
    {
      "source": [
        "bse.cn/"
      ]
    }
  ],
  "url": "bse.cn/"
}
```
