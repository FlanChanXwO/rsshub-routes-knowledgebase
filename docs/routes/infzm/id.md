# 南方周末 - 频道

## Coverage
`index-only`

## Route
- Namespace: `infzm`
- Namespace Name: `南方周末`
- Route Path: `/:id`
- Route Name: `频道`
- Example: `/infzm/1`
- URL: `www.infzm.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `KarasuShin, ranpox, xyqfer`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/infzm/index.ts')`

## Description
下面给出部分参考：

| 推荐 | 新闻 | 观点 | 文化 | 人物 | 影像 | 专题 | 生活 | 视频 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 1    | 2    | 3    | 4    | 7    | 8    | 6    | 5    | 131  |

## Parameters
- `id`: 南方周末频道 id, 可在该频道的 URL 中找到（即 https://www.infzm.com/contents?term_id=:id)


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `infzm.com/contents`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "下面给出部分参考：\n\n| 推荐 | 新闻 | 观点 | 文化 | 人物 | 影像 | 专题 | 生活 | 视频 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| 1    | 2    | 3    | 4    | 7    | 8    | 6    | 5    | 131  |",
  "example": "/infzm/1",
  "location": "index.ts",
  "maintainers": [
    "KarasuShin",
    "ranpox",
    "xyqfer"
  ],
  "module": "() => import('@/routes/infzm/index.ts')",
  "name": "频道",
  "parameters": {
    "id": "南方周末频道 id, 可在该频道的 URL 中找到（即 https://www.infzm.com/contents?term_id=:id)"
  },
  "path": "/:id",
  "radar": [
    {
      "source": [
        "infzm.com/contents"
      ]
    }
  ]
}
```
