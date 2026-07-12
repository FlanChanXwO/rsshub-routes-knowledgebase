# 化州市人民政府 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov/huazhou`
- Namespace Name: `化州市人民政府`
- Route Path: `/gov/huazhou/:path{.+}`
- Route Name: `通用`
- Example: `/gov/huazhou/www/syzl/zcjd`
- URL: `www.huazhou.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `ShuiHuo`
- Source Location: `huazhou.ts`
- Source Module: `_None_`

## Description
::: tip

路径处填写对应页面 URL 中最前面的部分和域名后的字段。下面是一个例子。

若订阅 [政策解读](http://www.huazhou.gov.cn/syzl/zcjd/) 则将对应页面 URL <http://www.huazhou.gov.cn/syzl/zcjd/> 中 `http://www.huazhou.gov.cn/` 的字段 `www` `syzl/zcjd/` 作为路径填入。此时路由为 [`/gov/huazhou/www/syzl/zcjd/`](https://rsshub.app/gov/huazhou/www/syzl/zcjd/)

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
  "description": "::: tip\n\n路径处填写对应页面 URL 中最前面的部分和域名后的字段。下面是一个例子。\n\n若订阅 [政策解读](http://www.huazhou.gov.cn/syzl/zcjd/) 则将对应页面 URL <http://www.huazhou.gov.cn/syzl/zcjd/> 中 `http://www.huazhou.gov.cn/` 的字段 `www` `syzl/zcjd/` 作为路径填入。此时路由为 [`/gov/huazhou/www/syzl/zcjd/`](https://rsshub.app/gov/huazhou/www/syzl/zcjd/)\n\n:::",
  "example": "/gov/huazhou/www/syzl/zcjd",
  "heat": 0,
  "location": "huazhou.ts",
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
