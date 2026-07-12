# 高州市人民政府 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov/gaozhou`
- Namespace Name: `高州市人民政府`
- Route Path: `/gov/gaozhou/:path{.+}`
- Route Name: `通用`
- Example: `/gov/gaozhou/www/zcjd`
- URL: `www.gaozhou.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `ShuiHuo`
- Source Location: `gaozhou.ts`
- Source Module: `_None_`

## Description
::: tip

路径处填写对应页面 URL 中最前面的部分和域名后的字段。下面是一个例子。

若订阅 [政策解读](http://www.gaozhou.gov.cn/zcjd/) 则将对应页面 URL <http://www.gaozhou.gov.cn/zcjd/> 中 `http://www.gaozhou.gov.cn/` 的字段 `www` 和 `zcjd/` 作为路径填入。此时路由为 [`/gov/gaozhou/www/zcjd/`](https://rsshub.app/gov/gaozhou/www/zcjd/)

:::

## Parameters
- `path`: 路径，只填写 `www` 默认为 政策解读


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
  "description": "::: tip\n\n路径处填写对应页面 URL 中最前面的部分和域名后的字段。下面是一个例子。\n\n若订阅 [政策解读](http://www.gaozhou.gov.cn/zcjd/) 则将对应页面 URL <http://www.gaozhou.gov.cn/zcjd/> 中 `http://www.gaozhou.gov.cn/` 的字段 `www` 和 `zcjd/` 作为路径填入。此时路由为 [`/gov/gaozhou/www/zcjd/`](https://rsshub.app/gov/gaozhou/www/zcjd/)\n\n:::",
  "example": "/gov/gaozhou/www/zcjd",
  "heat": 0,
  "location": "gaozhou.ts",
  "maintainers": [
    "ShuiHuo"
  ],
  "name": "通用",
  "parameters": {
    "path": "路径，只填写 `www` 默认为 政策解读"
  },
  "path": "/:path{.+}",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
