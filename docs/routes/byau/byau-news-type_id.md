# 黑龙江八一农垦大学 - 新闻网

## Coverage
`index-only`

## Route
- Namespace: `byau`
- Namespace Name: `黑龙江八一农垦大学`
- Route Path: `/byau/news/:type_id`
- Route Name: `新闻网`
- Example: `/byau/news/3674`
- URL: `xinwen.byau.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ueiu`
- Source Location: `xinwen/index.ts`
- Source Module: `_None_`

## Description
| 学校要闻 | 校园动态 |
| -------- | -------- |
| 3674     | 3676     |

## Parameters
- `type_id`: 栏目类型(从菜单栏获取对应 ID)


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `xinwen.byau.edu.cn/:type_id/list.htm`
- `target`: `/news/:type_id`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学校要闻 | 校园动态 |\n| -------- | -------- |\n| 3674     | 3676     |",
  "example": "/byau/news/3674",
  "heat": 0,
  "location": "xinwen/index.ts",
  "maintainers": [
    "ueiu"
  ],
  "name": "新闻网",
  "parameters": {
    "type_id": "栏目类型(从菜单栏获取对应 ID)"
  },
  "path": "/news/:type_id",
  "radar": [
    {
      "source": [
        "xinwen.byau.edu.cn/:type_id/list.htm"
      ],
      "target": "/news/:type_id"
    }
  ],
  "topFeeds": [],
  "url": "xinwen.byau.edu.cn"
}
```
