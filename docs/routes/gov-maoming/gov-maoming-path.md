# 茂名市人民政府 - 门户网站

## Coverage
`index-only`

## Route
- Namespace: `gov/maoming`
- Namespace Name: `茂名市人民政府`
- Route Path: `/gov/maoming/:path{.+}`
- Route Name: `门户网站`
- Example: `/gov/maoming/www/zwgk/zcjd/jd`
- URL: `www.maoming.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `ShuiHuo`
- Source Location: `maoming.ts`
- Source Module: `_None_`

## Description
::: tip

路径处填写对应页面 URL 中茂名有关政府网站的域名最前面的部分和域名后的字段。下面是一个例子。

若订阅 [茂名市人民政府门户网站 > 政务公开 > 政策解读](http://www.maoming.gov.cn/zwgk/zcjd/jd/) 则将对应页面 URL <http://www.maoming.gov.cn/zwgk/zcjd/jd/> 中 `http://www.maoming.gov.cn/` 的字段 `www` 和 `/zwgk/zcjd/jd/` 作为路径填入。此时路由为 [`/gov/maoming/www/zwgk/zcjd/jd/`](https://rsshub.app/gov/maoming/www/zwgk/zcjd/jd/)

若订阅 [茂名市农业农村局网站 > 政务区 > 政务公开 > 通知公告](http://mmny.maoming.gov.cn/zwq/zwgk/tzgg/) 则将对应页面 URL <http://mmny.maoming.gov.cn/zwq/zwgk/tzgg/> 中 `http://mmny.maoming.gov.cn/` 的字段 `mmny` 和 `/zwq/zwgk/tzgg/` 作为路径填入。此时路由为 [`/gov/maoming/mmny/zwq/zwgk/tzgg/`](https://rsshub.app/gov/maoming/mmny/zwq/zwgk/tzgg/)

:::

## Parameters
- `path`: 路径


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
  "description": "::: tip\n\n路径处填写对应页面 URL 中茂名有关政府网站的域名最前面的部分和域名后的字段。下面是一个例子。\n\n若订阅 [茂名市人民政府门户网站 > 政务公开 > 政策解读](http://www.maoming.gov.cn/zwgk/zcjd/jd/) 则将对应页面 URL <http://www.maoming.gov.cn/zwgk/zcjd/jd/> 中 `http://www.maoming.gov.cn/` 的字段 `www` 和 `/zwgk/zcjd/jd/` 作为路径填入。此时路由为 [`/gov/maoming/www/zwgk/zcjd/jd/`](https://rsshub.app/gov/maoming/www/zwgk/zcjd/jd/)\n\n若订阅 [茂名市农业农村局网站 > 政务区 > 政务公开 > 通知公告](http://mmny.maoming.gov.cn/zwq/zwgk/tzgg/) 则将对应页面 URL <http://mmny.maoming.gov.cn/zwq/zwgk/tzgg/> 中 `http://mmny.maoming.gov.cn/` 的字段 `mmny` 和 `/zwq/zwgk/tzgg/` 作为路径填入。此时路由为 [`/gov/maoming/mmny/zwq/zwgk/tzgg/`](https://rsshub.app/gov/maoming/mmny/zwq/zwgk/tzgg/)\n\n:::",
  "example": "/gov/maoming/www/zwgk/zcjd/jd",
  "heat": 0,
  "location": "maoming.ts",
  "maintainers": [
    "ShuiHuo"
  ],
  "name": "门户网站",
  "parameters": {
    "path": "路径"
  },
  "path": "/:path{.+}",
  "topFeeds": []
}
```
