# 国家互联网信息办公室 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov/cac`
- Namespace Name: `国家互联网信息办公室`
- Route Path: `/gov/cac/:path{.+}`
- Route Name: `通用`
- Example: `/gov/cac/wxzw/xxh`
- URL: `www.cac.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `drgnchan`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip

路径填写对应页面 URL 中间部分。例如：

首页 > 网信政务 > 网信发布： <https://www.cac.gov.cn/wxzw/wxfb/A093702index_1.htm>
此时，path 参数为：/wxzw/wxfb

:::

## Parameters
- `path`: 路径，比如xxh表示信息化


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
  "description": "::: tip\n\n路径填写对应页面 URL 中间部分。例如：\n\n首页 > 网信政务 > 网信发布： <https://www.cac.gov.cn/wxzw/wxfb/A093702index_1.htm>\n此时，path 参数为：/wxzw/wxfb\n\n:::",
  "example": "/gov/cac/wxzw/xxh",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "drgnchan"
  ],
  "name": "通用",
  "parameters": {
    "path": "路径，比如xxh表示信息化"
  },
  "path": "/:path{.+}",
  "topFeeds": []
}
```
