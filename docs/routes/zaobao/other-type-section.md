# 联合早报 - 其他栏目

## Coverage
`index-only`

## Route
- Namespace: `zaobao`
- Namespace Name: `联合早报`
- Route Path: `/other/:type?/:section?`
- Route Name: `其他栏目`
- Example: `/zaobao/other/lifestyle/health`
- URL: `www.zaobao.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `shunf4`
- Source Location: `other.ts`
- Source Module: `() => import('@/routes/zaobao/other.ts')`

## Description
除了上面两个兼容规则之外，联合早报网站里所有页面形如 [https://www.zaobao.com/lifestyle/health](https://www.zaobao.com/lifestyle/health) 这样的栏目都能被这个规则解析到，早报的大部分栏目都是这个样式的。你可以测试之后再订阅。

## Parameters
- `type`: https://www.zaobao.com/**lifestyle**/health 中的 **lifestyle**
- `section`: https://www.zaobao.com/lifestyle/**health** 中的 **health**


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "除了上面两个兼容规则之外，联合早报网站里所有页面形如 [https://www.zaobao.com/lifestyle/health](https://www.zaobao.com/lifestyle/health) 这样的栏目都能被这个规则解析到，早报的大部分栏目都是这个样式的。你可以测试之后再订阅。",
  "example": "/zaobao/other/lifestyle/health",
  "location": "other.ts",
  "maintainers": [
    "shunf4"
  ],
  "module": "() => import('@/routes/zaobao/other.ts')",
  "name": "其他栏目",
  "parameters": {
    "section": "https://www.zaobao.com/lifestyle/**health** 中的 **health**",
    "type": "https://www.zaobao.com/**lifestyle**/health 中的 **lifestyle**"
  },
  "path": "/other/:type?/:section?"
}
```
