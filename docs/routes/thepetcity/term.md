# PetCity 毛孩日常 - 分類

## Coverage
`index-only`

## Route
- Namespace: `thepetcity`
- Namespace Name: `PetCity 毛孩日常`
- Route Path: `/:term?`
- Route Name: `分類`
- Example: `/thepetcity`
- URL: `thepetcity.co/`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `TonyRL, bigfei`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/thepetcity/index.ts')`

## Description
| Column Name       | TermID |
| -------------------- | ------ |
| Knowledge飼養大全     | 3      |
| Funny News毛孩趣聞    | 2      |
| Raise Pets 養寵物新手  | 5      |
| Hot Spot 毛孩打卡點    | 4      |
| Pet Staff 毛孩好物    | 1      |

## Parameters
- `term`: 見下表，留空為全部文章


## Features
_None_

## Radar
### Rule 1
- `title`: `Pet Staff 毛孩好物`
- `source`:
  - `thepetcity.co/category/cute-item`
  - `thepetcity.co/`
- `target`: `/1`
### Rule 2
- `title`: `Funny News毛孩趣聞`
- `source`:
  - `thepetcity.co/category/funny-news`
  - `thepetcity.co/`
- `target`: `/2`
### Rule 3
- `title`: `Knowledge飼養大全`
- `source`:
  - `thepetcity.co/category/knowledge`
  - `thepetcity.co/`
- `target`: `/3`
### Rule 4
- `title`: `Hot Spot 毛孩打卡點`
- `source`:
  - `thepetcity.co/category/hot-spot`
  - `thepetcity.co/`
- `target`: `/4`
### Rule 5
- `title`: `Raise Pets 養寵物新手`
- `source`:
  - `thepetcity.co/category/raise-cats`
  - `thepetcity.co/`
- `target`: `/5`
### Rule 6
- `title`: `PetCity 毛孩日常 | 飼養竉物、竉物用品、萌寵趣聞`
- `source`:
  - `thepetcity.co/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| Column Name       | TermID |\n| -------------------- | ------ |\n| Knowledge飼養大全     | 3      |\n| Funny News毛孩趣聞    | 2      |\n| Raise Pets 養寵物新手  | 5      |\n| Hot Spot 毛孩打卡點    | 4      |\n| Pet Staff 毛孩好物    | 1      |",
  "example": "/thepetcity",
  "location": "index.ts",
  "maintainers": [
    "TonyRL",
    "bigfei"
  ],
  "module": "() => import('@/routes/thepetcity/index.ts')",
  "name": "分類",
  "parameters": {
    "term": "見下表，留空為全部文章"
  },
  "path": "/:term?",
  "radar": [
    {
      "source": [
        "thepetcity.co/category/cute-item",
        "thepetcity.co/"
      ],
      "target": "/1",
      "title": "Pet Staff 毛孩好物"
    },
    {
      "source": [
        "thepetcity.co/category/funny-news",
        "thepetcity.co/"
      ],
      "target": "/2",
      "title": "Funny News毛孩趣聞"
    },
    {
      "source": [
        "thepetcity.co/category/knowledge",
        "thepetcity.co/"
      ],
      "target": "/3",
      "title": "Knowledge飼養大全"
    },
    {
      "source": [
        "thepetcity.co/category/hot-spot",
        "thepetcity.co/"
      ],
      "target": "/4",
      "title": "Hot Spot 毛孩打卡點"
    },
    {
      "source": [
        "thepetcity.co/category/raise-cats",
        "thepetcity.co/"
      ],
      "target": "/5",
      "title": "Raise Pets 養寵物新手"
    },
    {
      "source": [
        "thepetcity.co/"
      ],
      "target": "",
      "title": "PetCity 毛孩日常 | 飼養竉物、竉物用品、萌寵趣聞"
    }
  ],
  "url": "thepetcity.co/"
}
```
