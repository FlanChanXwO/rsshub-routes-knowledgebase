# 摩点 - 众筹

## Coverage
`index-only`

## Route
- Namespace: `modian`
- Namespace Name: `摩点`
- Route Path: `/zhongchou/:category?/:sort?/:status?`
- Route Name: `众筹`
- Example: `/modian/zhongchou`
- URL: `modian.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `nczitzk`
- Source Location: `zhongchou.ts`
- Source Module: `() => import('@/routes/modian/zhongchou.ts')`

## Description
分类

| 全部 | 游戏  | 动漫   | 出版       | 桌游       |
| ---- | ----- | ------ | ---------- | ---------- |
| all  | games | comics | publishing | tablegames |

| 卡牌  | 潮玩模型 | 影视       | 音乐  | 活动       |
| ----- | -------- | ---------- | ----- | ---------- |
| cards | toys     | film-video | music | activities |

| 设计   | 科技       | 食品 | 爱心通道 | 动物救助 |
| ------ | ---------- | ---- | -------- | -------- |
| design | technology | food | charity  | animals  |

| 个人愿望 | 其他   |
| -------- | ------ |
| wishes   | others |

  排序

| 最新上线  | 金额最高   | 评论最多     |
| --------- | ---------- | ------------ |
| top_time | top_money | top_comment |

  状态

| 全部 | 创意 | 预热    | 众筹中 | 众筹成功 |
| ---- | ---- | ------- | ------ | -------- |
| all  | idea | preheat | going  | success  |

## Parameters
- `category`: 分类，见下表，默认为全部
- `sort`: 排序，见下表，默认为最新上线
- `status`: 状态，见下表，默认为全部


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `zhongchou.modian.com/:category/:sort/:status`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "分类\n\n| 全部 | 游戏  | 动漫   | 出版       | 桌游       |\n| ---- | ----- | ------ | ---------- | ---------- |\n| all  | games | comics | publishing | tablegames |\n\n| 卡牌  | 潮玩模型 | 影视       | 音乐  | 活动       |\n| ----- | -------- | ---------- | ----- | ---------- |\n| cards | toys     | film-video | music | activities |\n\n| 设计   | 科技       | 食品 | 爱心通道 | 动物救助 |\n| ------ | ---------- | ---- | -------- | -------- |\n| design | technology | food | charity  | animals  |\n\n| 个人愿望 | 其他   |\n| -------- | ------ |\n| wishes   | others |\n\n  排序\n\n| 最新上线  | 金额最高   | 评论最多     |\n| --------- | ---------- | ------------ |\n| top_time | top_money | top_comment |\n\n  状态\n\n| 全部 | 创意 | 预热    | 众筹中 | 众筹成功 |\n| ---- | ---- | ------- | ------ | -------- |\n| all  | idea | preheat | going  | success  |",
  "example": "/modian/zhongchou",
  "location": "zhongchou.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/modian/zhongchou.ts')",
  "name": "众筹",
  "parameters": {
    "category": "分类，见下表，默认为全部",
    "sort": "排序，见下表，默认为最新上线",
    "status": "状态，见下表，默认为全部"
  },
  "path": "/zhongchou/:category?/:sort?/:status?",
  "radar": [
    {
      "source": [
        "zhongchou.modian.com/:category/:sort/:status"
      ]
    }
  ]
}
```
