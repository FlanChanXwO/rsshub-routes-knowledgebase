# 搜狐号 - 最新

## Coverage
`index-only`

## Route
- Namespace: `sohu`
- Namespace Name: `搜狐号`
- Route Path: `/mp/:xpt`
- Route Name: `最新`
- Example: `/sohu/mp/c29odXptdGhnbjZ3NEBzb2h1LmNvbQ==`
- URL: `sohu.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `HenryQW`
- Source Location: `mp.tsx`
- Source Module: `() => import('@/routes/sohu/mp.tsx')`

## Description
搜狐号 ID 可以通过以下方式获取：
  1.  通过浏览器搜索相关搜狐号 `果壳 site: mp.sohu.com`。
  2.  通过浏览器控制台执行 `window.globalConst.mkeyConst_mkey`，返回的即为搜狐号 ID。

## Parameters
- `xpt`: 搜狐号 xpt ，可在URL中找到或搜狐号 ID


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mp.sohu.com/profile`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "搜狐号 ID 可以通过以下方式获取：\n  1.  通过浏览器搜索相关搜狐号 `果壳 site: mp.sohu.com`。\n  2.  通过浏览器控制台执行 `window.globalConst.mkeyConst_mkey`，返回的即为搜狐号 ID。",
  "example": "/sohu/mp/c29odXptdGhnbjZ3NEBzb2h1LmNvbQ==",
  "location": "mp.tsx",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/sohu/mp.tsx')",
  "name": "最新",
  "parameters": {
    "xpt": "搜狐号 xpt ，可在URL中找到或搜狐号 ID"
  },
  "path": "/mp/:xpt",
  "radar": [
    {
      "source": [
        "mp.sohu.com/profile"
      ]
    }
  ]
}
```
