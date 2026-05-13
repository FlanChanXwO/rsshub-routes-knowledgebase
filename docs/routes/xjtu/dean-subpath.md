# 西安交通大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `xjtu`
- Namespace Name: `西安交通大学`
- Route Path: `/dean/:subpath{.+}`
- Route Name: `教务处`
- Example: `/xjtu/dean/jxxx/jxtz2`
- URL: `2yuan.xjtu.edu.cn`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `hoilc`
- Source Location: `dean.ts`
- Source Module: `() => import('@/routes/xjtu/dean.ts')`

## Description
打开一个类似 <https://dean.xjtu.edu.cn/jxxx/jxtz2.htm> 的网址，在 `.cn` 后的内容就是 subpath，此例中是 `jxxx/jxtz2`

## Parameters
_None_


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "description": "打开一个类似 <https://dean.xjtu.edu.cn/jxxx/jxtz2.htm> 的网址，在 `.cn` 后的内容就是 subpath，此例中是 `jxxx/jxtz2`",
  "example": "/xjtu/dean/jxxx/jxtz2",
  "location": "dean.ts",
  "maintainers": [
    "hoilc"
  ],
  "module": "() => import('@/routes/xjtu/dean.ts')",
  "name": "教务处",
  "path": "/dean/:subpath{.+}"
}
```
