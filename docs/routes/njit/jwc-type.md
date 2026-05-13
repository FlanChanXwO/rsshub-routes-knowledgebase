# 南京工程学院 - 南京工程学院教务处

## Coverage
`index-only`

## Route
- Namespace: `njit`
- Namespace Name: `南京工程学院`
- Route Path: `/jwc/:type?`
- Route Name: `南京工程学院教务处`
- Example: `/njit/jwc/jx`
- URL: `jwc.njit.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `zefengdaguo`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/njit/jwc.ts')`

## Description
| 教学 | 考试 | 信息 | 实践 |
| ---- | ---- | ---- | ---- |
| jx   | ks   | xx   | sj   |

## Parameters
- `type`: 默认为 `jx`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 教学 | 考试 | 信息 | 实践 |\n| ---- | ---- | ---- | ---- |\n| jx   | ks   | xx   | sj   |",
  "example": "/njit/jwc/jx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [
    "zefengdaguo"
  ],
  "module": "() => import('@/routes/njit/jwc.ts')",
  "name": "南京工程学院教务处",
  "parameters": {
    "type": "默认为 `jx`"
  },
  "path": "/jwc/:type?"
}
```
