# 乐山师范学院 - 教学部通知公告

## Coverage
`index-only`

## Route
- Namespace: `lsnu`
- Namespace Name: `乐山师范学院`
- Route Path: `/jiaowc/tzgg/:category?`
- Route Name: `教学部通知公告`
- Example: `/lsnu/jiaowc/tzgg`
- URL: `lsnu.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `nyaShine`
- Source Location: `jiaowc/tzgg.ts`
- Source Module: `() => import('@/routes/lsnu/jiaowc/tzgg.ts')`

## Description
| 实践教学科 | 教育运行科 | 教研教改科 | 学籍管理科 | 考试科 | 教材建设管理科 |
| ---------- | ---------- | ---------- | ---------- | ------ | -------------- |
| sjjxk      | jxyxk      | jyjgk      | xjglk      | ksk    | jcjsglk        |

## Parameters
- `category`: 分类名


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `lsnu.edu.cn/`
- `target`: `/jiaowc/tzgg`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 实践教学科 | 教育运行科 | 教研教改科 | 学籍管理科 | 考试科 | 教材建设管理科 |\n| ---------- | ---------- | ---------- | ---------- | ------ | -------------- |\n| sjjxk      | jxyxk      | jyjgk      | xjglk      | ksk    | jcjsglk        |",
  "example": "/lsnu/jiaowc/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jiaowc/tzgg.ts",
  "maintainers": [
    "nyaShine"
  ],
  "module": "() => import('@/routes/lsnu/jiaowc/tzgg.ts')",
  "name": "教学部通知公告",
  "parameters": {
    "category": "分类名"
  },
  "path": "/jiaowc/tzgg/:category?",
  "radar": [
    {
      "source": [
        "lsnu.edu.cn/"
      ],
      "target": "/jiaowc/tzgg"
    }
  ],
  "url": "lsnu.edu.cn/"
}
```
