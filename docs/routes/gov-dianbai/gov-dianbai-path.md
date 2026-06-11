# 茂名市电白区人民政府 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov/dianbai`
- Namespace Name: `茂名市电白区人民政府`
- Route Path: `/gov/dianbai/:path{.+}`
- Route Name: `通用`
- Example: `/gov/dianbai/www/zwgk/zcjd`
- URL: `www.dianbai.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `ShuiHuo`
- Source Location: `dianbai.ts`
- Source Module: `_None_`

## Description
::: tip

路径处填写对应页面 URL 中最前面的部分和域名后的字段。下面是一个例子。

若订阅 [政务公开 > 政策解读](http://www.dianbai.gov.cn/zwgk/zcjd/) 则将对应页面 URL <http://www.dianbai.gov.cn/zwgk/zcjd/> 中 `http://www.dianbai.gov.cn/` 的字段 `www` 和 `zwgk/zcjd/` 作为路径填入。此时路由为 [`/gov/dianbai/www/zwgk/zcjd/`](https://rsshub.app/gov/dianbai/www/zwgk/zcjd/)

:::

## Parameters
- `path`: 路径，只填写 `www` 默认为 政务公开 > 政策解读


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n\n路径处填写对应页面 URL 中最前面的部分和域名后的字段。下面是一个例子。\n\n若订阅 [政务公开 > 政策解读](http://www.dianbai.gov.cn/zwgk/zcjd/) 则将对应页面 URL <http://www.dianbai.gov.cn/zwgk/zcjd/> 中 `http://www.dianbai.gov.cn/` 的字段 `www` 和 `zwgk/zcjd/` 作为路径填入。此时路由为 [`/gov/dianbai/www/zwgk/zcjd/`](https://rsshub.app/gov/dianbai/www/zwgk/zcjd/)\n\n:::",
  "example": "/gov/dianbai/www/zwgk/zcjd",
  "heat": 0,
  "location": "dianbai.ts",
  "maintainers": [
    "ShuiHuo"
  ],
  "name": "通用",
  "parameters": {
    "path": "路径，只填写 `www` 默认为 政务公开 > 政策解读"
  },
  "path": "/:path{.+}",
  "topFeeds": []
}
```
