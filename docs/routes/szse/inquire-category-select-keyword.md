# 深圳证券交易所 - 问询函件

## Coverage
`index-only`

## Route
- Namespace: `szse`
- Namespace Name: `深圳证券交易所`
- Route Path: `/inquire/:category?/:select?/:keyword?`
- Route Name: `问询函件`
- Example: `/szse/inquire`
- URL: `szse.cn/disclosure/supervision/inquire/index.html`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `Jeason0228, nczitzk`
- Source Location: `inquire.tsx`
- Source Module: `() => import('@/routes/szse/inquire.tsx')`

## Description
类型

| 主板 | 创业板 |
| ---- | ------ |
| 0    | 1      |

  函件类别

| 全部函件类别 | 非许可类重组问询函 | 问询函 | 违法违规线索分析报告 | 许可类重组问询函 | 监管函（会计师事务所模板） | 提请关注函（会计师事务所模板） | 年报问询函 | 向中介机构发函 | 半年报问询函 | 关注函 | 公司部函 | 三季报问询函 |
| ------------ | ------------------ | ------ | -------------------- | ---------------- | -------------------------- | ------------------------------ | ---------- | -------------- | ------------ | ------ | -------- | ------------ |

## Parameters
- `category`: 类型，见下表，默认为 `0` 即 主板
- `select`: 函件类别, 见下表，默认为全部函件类别
- `keyword`: 公司代码或简称，默认为空


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
  - `szse.cn/disclosure/supervision/inquire/index.html`
  - `szse.cn/`
- `target`: `/inquire`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "类型\n\n| 主板 | 创业板 |\n| ---- | ------ |\n| 0    | 1      |\n\n  函件类别\n\n| 全部函件类别 | 非许可类重组问询函 | 问询函 | 违法违规线索分析报告 | 许可类重组问询函 | 监管函（会计师事务所模板） | 提请关注函（会计师事务所模板） | 年报问询函 | 向中介机构发函 | 半年报问询函 | 关注函 | 公司部函 | 三季报问询函 |\n| ------------ | ------------------ | ------ | -------------------- | ---------------- | -------------------------- | ------------------------------ | ---------- | -------------- | ------------ | ------ | -------- | ------------ |",
  "example": "/szse/inquire",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "inquire.tsx",
  "maintainers": [
    "Jeason0228",
    "nczitzk"
  ],
  "module": "() => import('@/routes/szse/inquire.tsx')",
  "name": "问询函件",
  "parameters": {
    "category": "类型，见下表，默认为 `0` 即 主板",
    "keyword": "公司代码或简称，默认为空",
    "select": "函件类别, 见下表，默认为全部函件类别"
  },
  "path": "/inquire/:category?/:select?/:keyword?",
  "radar": [
    {
      "source": [
        "szse.cn/disclosure/supervision/inquire/index.html",
        "szse.cn/"
      ],
      "target": "/inquire"
    }
  ],
  "url": "szse.cn/disclosure/supervision/inquire/index.html"
}
```
