# 国家矿山安全监察局 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `gov/chinamine-safety`
- Namespace Name: `国家矿山安全监察局`
- Route Path: `/gov/chinamine-safety/xw/:category{.+}?`
- Route Name: `新闻`
- Example: `/gov/chinamine-safety/xw`
- URL: `www.chinamine-safety.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `xw.ts`
- Source Module: `_None_`

## Description
| 分类               | id       |
| ------------------ | -------- |
| 应急管理部要闻     | yjglbyw  |
| 国家矿山安监局要闻 | mkaqjcxw |
| 地方信息           | dfdt     |
| 党建专栏           | djzl     |
| 经验交流           | jyjl     |
| 新闻发布会         | xwfbh    |

## Parameters
- `category`: 分类，见下表，默认为应急管理部要闻


## Features
_None_

## Radar
### Rule 1
- `title`: `应急管理部要闻`
- `source`:
  - `www.chinamine-safety.gov.cn/xw/yjglbyw/`
- `target`: `/xw/yjglbyw`
### Rule 2
- `title`: `国家矿山安监局要闻`
- `source`:
  - `www.chinamine-safety.gov.cn/xw/mkaqjcxw/`
- `target`: `/xw/mkaqjcxw`
### Rule 3
- `title`: `地方信息`
- `source`:
  - `www.chinamine-safety.gov.cn/xw/dfdt/`
- `target`: `/xw/dfdt`
### Rule 4
- `title`: `党建专栏`
- `source`:
  - `www.chinamine-safety.gov.cn/xw/djzl/`
- `target`: `/xw/djzl`
### Rule 5
- `title`: `经验交流`
- `source`:
  - `www.chinamine-safety.gov.cn/xw/jyjl/`
- `target`: `/xw/jyjl`
### Rule 6
- `title`: `新闻发布会`
- `source`:
  - `www.chinamine-safety.gov.cn/xw/xwfbh/`
- `target`: `/xw/xwfbh`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 分类               | id       |\n| ------------------ | -------- |\n| 应急管理部要闻     | yjglbyw  |\n| 国家矿山安监局要闻 | mkaqjcxw |\n| 地方信息           | dfdt     |\n| 党建专栏           | djzl     |\n| 经验交流           | jyjl     |\n| 新闻发布会         | xwfbh    |",
  "example": "/gov/chinamine-safety/xw",
  "heat": 0,
  "location": "xw.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新闻",
  "parameters": {
    "category": "分类，见下表，默认为应急管理部要闻"
  },
  "path": "/xw/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.chinamine-safety.gov.cn/xw/yjglbyw/"
      ],
      "target": "/xw/yjglbyw",
      "title": "应急管理部要闻"
    },
    {
      "source": [
        "www.chinamine-safety.gov.cn/xw/mkaqjcxw/"
      ],
      "target": "/xw/mkaqjcxw",
      "title": "国家矿山安监局要闻"
    },
    {
      "source": [
        "www.chinamine-safety.gov.cn/xw/dfdt/"
      ],
      "target": "/xw/dfdt",
      "title": "地方信息"
    },
    {
      "source": [
        "www.chinamine-safety.gov.cn/xw/djzl/"
      ],
      "target": "/xw/djzl",
      "title": "党建专栏"
    },
    {
      "source": [
        "www.chinamine-safety.gov.cn/xw/jyjl/"
      ],
      "target": "/xw/jyjl",
      "title": "经验交流"
    },
    {
      "source": [
        "www.chinamine-safety.gov.cn/xw/xwfbh/"
      ],
      "target": "/xw/xwfbh",
      "title": "新闻发布会"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
