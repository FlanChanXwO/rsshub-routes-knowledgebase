# 茂名高新技术产业开发区 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov/mmht`
- Namespace Name: `茂名高新技术产业开发区`
- Route Path: `/gov/mmht/:path{.+}`
- Route Name: `通用`
- Example: `/gov/mmht/www/xwzx/zcjd`
- URL: `www.mmht.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `ShuiHuo`
- Source Location: `mmht.ts`
- Source Module: `_None_`

## Description
::: tip

路径处填写对应页面 URL 中最前面的部分和域名后的字段。下面是一个例子。

若订阅 [政务公开 > 政策解读](http://www.mmht.gov.cn/xwzx/zcjd/) 则将对应页面 URL <http://www.mmht.gov.cn/xwzx/zcjd/> 中 `http://www.mmht.gov.cn/` 的字段 `www` 和 `xwzx/zcjd/` 作为路径填入。此时路由为 [`/gov/mmht/www/xwzx/zcjd/`](https://rsshub.app/gov/mmht/www/xwzx/zcjd/)

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
  "description": "::: tip\n\n路径处填写对应页面 URL 中最前面的部分和域名后的字段。下面是一个例子。\n\n若订阅 [政务公开 > 政策解读](http://www.mmht.gov.cn/xwzx/zcjd/) 则将对应页面 URL <http://www.mmht.gov.cn/xwzx/zcjd/> 中 `http://www.mmht.gov.cn/` 的字段 `www` 和 `xwzx/zcjd/` 作为路径填入。此时路由为 [`/gov/mmht/www/xwzx/zcjd/`](https://rsshub.app/gov/mmht/www/xwzx/zcjd/)\n\n:::",
  "example": "/gov/mmht/www/xwzx/zcjd",
  "heat": 0,
  "location": "mmht.ts",
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
