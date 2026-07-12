# 中央纪委国家监委 - 要闻

## Coverage
`index-only`

## Route
- Namespace: `gov/ccdi`
- Namespace Name: `中央纪委国家监委`
- Route Path: `/gov/ccdi/:path{.+}?`
- Route Name: `要闻`
- Example: `/gov/ccdi/yaowenn`
- URL: `www.ccdi.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `bigfei`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip

路径处填写对应页面 URL 中 `http://www.ccdi.gov.cn/` 后的字段。下面是一个例子。

若订阅 [审查调查 > 中管干部 > 执纪审查](https://www.ccdi.gov.cn/scdcn/zggb/zjsc/) 则将对应页面 URL <https://www.ccdi.gov.cn/scdcn/zggb/zjsc/> 中 `http://www.ccdi.gov.cn/` 后的字段 `scdcn/zggb/zjsc` 作为路径填入。此时路由为 [`/gov/ccdi/scdcn/zggb/zjsc`](https://rsshub.app/gov/ccdi/scdcn/zggb/zjsc)

:::

## Parameters
- `path`: 路径，默认为 要闻


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `www.ccdi.gov.cn/*path`
- `target`: `/:path`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n\n路径处填写对应页面 URL 中 `http://www.ccdi.gov.cn/` 后的字段。下面是一个例子。\n\n若订阅 [审查调查 > 中管干部 > 执纪审查](https://www.ccdi.gov.cn/scdcn/zggb/zjsc/) 则将对应页面 URL <https://www.ccdi.gov.cn/scdcn/zggb/zjsc/> 中 `http://www.ccdi.gov.cn/` 后的字段 `scdcn/zggb/zjsc` 作为路径填入。此时路由为 [`/gov/ccdi/scdcn/zggb/zjsc`](https://rsshub.app/gov/ccdi/scdcn/zggb/zjsc)\n\n:::",
  "example": "/gov/ccdi/yaowenn",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "bigfei"
  ],
  "name": "要闻",
  "parameters": {
    "path": "路径，默认为 要闻"
  },
  "path": "/:path{.+}?",
  "radar": [
    {
      "source": [
        "www.ccdi.gov.cn/*path"
      ],
      "target": "/:path"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
