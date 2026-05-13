# National Yang Ming Chiao Tung University - 資訊學院公告

## Coverage
`index-only`

## Route
- Namespace: `nycu`
- Namespace Name: `National Yang Ming Chiao Tung University`
- Route Path: `/cs/:category?`
- Route Name: `資訊學院公告`
- Example: `/nycu/cs/all`
- URL: `nycu.edu.tw`
- Language: `zh-TW`
- Categories: `university`
- Maintainers: `simbafs`
- Source Location: `cs.ts`
- Source Module: `() => import('@/routes/nycu/cs.ts')`

## Description
|    名稱    |       Name       |    :category     |
| :--------: | :--------------: | :--------------: |
|  全部公告  |       All        |       all        |
|   獎學金   |   Scholarships   |   scholarship    |
| 課程/演講  |     Courses      |     courses      |
|   研究所   |    Graduates     |     graduate     |
|   學士班   |  Undergraduates  |  undergraduate   |
|  入學公告  |    Admissions    |    candidate     |
|  獲獎捷報  |      Awards      |      awards      |
|  系內徵才  |   Internal Job   |      campus      |
|  企業徵才  |   Industry Job   |   corporation    |
|   系計中   | Computer Center  |       cscc       |
|  活動競賽  |     activity     |     activity     |
| 資訊人院刊 | NYC CCS MAGAZINE | NYC CCS MAGAZINE |

## Parameters
- `category`: categories, see below


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "|    名稱    |       Name       |    :category     |\n| :--------: | :--------------: | :--------------: |\n|  全部公告  |       All        |       all        |\n|   獎學金   |   Scholarships   |   scholarship    |\n| 課程/演講  |     Courses      |     courses      |\n|   研究所   |    Graduates     |     graduate     |\n|   學士班   |  Undergraduates  |  undergraduate   |\n|  入學公告  |    Admissions    |    candidate     |\n|  獲獎捷報  |      Awards      |      awards      |\n|  系內徵才  |   Internal Job   |      campus      |\n|  企業徵才  |   Industry Job   |   corporation    |\n|   系計中   | Computer Center  |       cscc       |\n|  活動競賽  |     activity     |     activity     |\n| 資訊人院刊 | NYC CCS MAGAZINE | NYC CCS MAGAZINE |",
  "example": "/nycu/cs/all",
  "location": "cs.ts",
  "maintainers": [
    "simbafs"
  ],
  "module": "() => import('@/routes/nycu/cs.ts')",
  "name": "資訊學院公告",
  "parameters": {
    "category": "categories, see below"
  },
  "path": "/cs/:category?"
}
```
