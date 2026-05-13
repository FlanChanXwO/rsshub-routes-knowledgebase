# 上海大学 - 教务部

## Coverage
`index-only`

## Route
- Namespace: `shu`
- Namespace Name: `上海大学`
- Route Path: `/jwb/:type?`
- Route Name: `教务部`
- Example: `_None_`
- URL: `www.shu.edu.cn`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `tuxinghuan, GhhG123`
- Source Location: `jwb.ts`
- Source Module: `() => import('@/routes/shu/jwb.ts')`

## Description
| 通知通告 | 新闻 | 政策文件(bug) |
| -------- | ---- | -------- |
| notice   | news | policy   |

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.shu.edu.cn/index`
- `target`: `/:type?`

## Raw JSON
```json
{
  "description": "| 通知通告 | 新闻 | 政策文件(bug) |\n| -------- | ---- | -------- |\n| notice   | news | policy   |",
  "location": "jwb.ts",
  "maintainers": [
    "tuxinghuan",
    "GhhG123"
  ],
  "module": "() => import('@/routes/shu/jwb.ts')",
  "name": "教务部",
  "path": [
    "/jwb/:type?"
  ],
  "radar": [
    {
      "source": [
        "www.shu.edu.cn/index"
      ],
      "target": "/:type?"
    }
  ]
}
```
