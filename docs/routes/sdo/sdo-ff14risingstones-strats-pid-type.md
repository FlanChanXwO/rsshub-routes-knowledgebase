# 盛趣游戏在线 - 攻略

## Coverage
`index-only`

## Route
- Namespace: `sdo`
- Namespace Name: `盛趣游戏在线`
- Route Path: `/sdo/ff14risingstones/strats/:pid?/:type?`
- Route Name: `攻略`
- Example: `/sdo/ff14risingstones/strats/1,2/refine`
- URL: `sdo.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `KarasuShin`
- Source Location: `ff14risingstones/strats.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `pid`: {"default": "all", "description": "分区id，默认显示所有分区，可通过 `,` 拼接多个分区 id 进行筛选", "options": [{"label": "全部", "value": "all"}, {"label": "新手指引", "value": "1"}, {"label": "副本攻略", "value": "2"}, {"label": "战斗职业", "value": "3"}, {"label": "PVP", "value": "4"}, {"label": "生产采集", "value": "5"}, {"label": "投影外观", "value": "6"}, {"label": "房屋装修", "value": "7"}, {"label": "骑士", "value": "8"}, {"label": "武僧", "value": "9"}, {"label": "战士", "value": "10"}, {"label": "龙骑士", "value": "11"}, {"label": "吟游诗人", "value": "12"}, {"label": "白魔法师", "value": "13"}, {"label": "黑魔法师", "value": "14"}, {"label": "召唤师", "value": "15"}, {"label": "学者", "value": "16"}, {"label": "忍者", "value": "17"}, {"label": "机工士", "value": "18"}, {"label": "暗黑骑士", "value": "19"}, {"label": "占星术士", "value": "20"}, {"label": "武士", "value": "21"}, {"label": "赤魔法师", "value": "22"}, {"label": "青魔法师", "value": "23"}, {"label": "绝枪战士", "value": "24"}, {"label": "舞者", "value": "25"}, {"label": "钐镰客", "value": "26"}, {"label": "贤者", "value": "27"}, {"label": "猫魅族", "value": "28"}, {"label": "拉拉菲尔族", "value": "29"}, {"label": "人族", "value": "30"}, {"label": "精灵族", "value": "31"}, {"label": "维埃拉族", "value": "32"}, {"label": "敖龙族", "value": "59"}, {"label": "硌狮族", "value": "60"}, {"label": "鲁加族", "value": "61"}, {"label": "无人岛", "value": "62"}, {"label": "特殊场景探索", "value": "63"}, {"label": "游戏资讯", "value": "64"}, {"label": "内容考据", "value": "65"}, {"label": "摄影截图", "value": "66"}, {"label": "金碟游乐场", "value": "67"}, {"label": "综合", "value": "68"}, {"label": "其他", "value": "69"}, {"label": "国际服资讯翻译", "value": "70"}, {"label": "游戏资讯整理", "value": "71"}, {"label": "其他", "value": "72"}]}
- `type`: {"description": "攻略类型，默认不做筛选", "options": [{"label": "置顶", "value": "top"}, {"label": "精华", "value": "refine"}]}


## Features
- `requireConfig`: [{"description": "值为 Cookie 头中 ff14risingstones 值", "name": "SDO_FF14RISINGSTONES"}, {"description": "值为与在网页端获取 Cookie 时相匹配的 User-Agent 值", "name": "SDO_UA"}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/sdo/ff14risingstones/strats/1,2/refine",
  "features": {
    "requireConfig": [
      {
        "description": "值为 Cookie 头中 ff14risingstones 值",
        "name": "SDO_FF14RISINGSTONES"
      },
      {
        "description": "值为与在网页端获取 Cookie 时相匹配的 User-Agent 值",
        "name": "SDO_UA"
      }
    ]
  },
  "heat": 0,
  "location": "ff14risingstones/strats.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "攻略",
  "parameters": {
    "pid": {
      "default": "all",
      "description": "分区id，默认显示所有分区，可通过 `,` 拼接多个分区 id 进行筛选",
      "options": [
        {
          "label": "全部",
          "value": "all"
        },
        {
          "label": "新手指引",
          "value": "1"
        },
        {
          "label": "副本攻略",
          "value": "2"
        },
        {
          "label": "战斗职业",
          "value": "3"
        },
        {
          "label": "PVP",
          "value": "4"
        },
        {
          "label": "生产采集",
          "value": "5"
        },
        {
          "label": "投影外观",
          "value": "6"
        },
        {
          "label": "房屋装修",
          "value": "7"
        },
        {
          "label": "骑士",
          "value": "8"
        },
        {
          "label": "武僧",
          "value": "9"
        },
        {
          "label": "战士",
          "value": "10"
        },
        {
          "label": "龙骑士",
          "value": "11"
        },
        {
          "label": "吟游诗人",
          "value": "12"
        },
        {
          "label": "白魔法师",
          "value": "13"
        },
        {
          "label": "黑魔法师",
          "value": "14"
        },
        {
          "label": "召唤师",
          "value": "15"
        },
        {
          "label": "学者",
          "value": "16"
        },
        {
          "label": "忍者",
          "value": "17"
        },
        {
          "label": "机工士",
          "value": "18"
        },
        {
          "label": "暗黑骑士",
          "value": "19"
        },
        {
          "label": "占星术士",
          "value": "20"
        },
        {
          "label": "武士",
          "value": "21"
        },
        {
          "label": "赤魔法师",
          "value": "22"
        },
        {
          "label": "青魔法师",
          "value": "23"
        },
        {
          "label": "绝枪战士",
          "value": "24"
        },
        {
          "label": "舞者",
          "value": "25"
        },
        {
          "label": "钐镰客",
          "value": "26"
        },
        {
          "label": "贤者",
          "value": "27"
        },
        {
          "label": "猫魅族",
          "value": "28"
        },
        {
          "label": "拉拉菲尔族",
          "value": "29"
        },
        {
          "label": "人族",
          "value": "30"
        },
        {
          "label": "精灵族",
          "value": "31"
        },
        {
          "label": "维埃拉族",
          "value": "32"
        },
        {
          "label": "敖龙族",
          "value": "59"
        },
        {
          "label": "硌狮族",
          "value": "60"
        },
        {
          "label": "鲁加族",
          "value": "61"
        },
        {
          "label": "无人岛",
          "value": "62"
        },
        {
          "label": "特殊场景探索",
          "value": "63"
        },
        {
          "label": "游戏资讯",
          "value": "64"
        },
        {
          "label": "内容考据",
          "value": "65"
        },
        {
          "label": "摄影截图",
          "value": "66"
        },
        {
          "label": "金碟游乐场",
          "value": "67"
        },
        {
          "label": "综合",
          "value": "68"
        },
        {
          "label": "其他",
          "value": "69"
        },
        {
          "label": "国际服资讯翻译",
          "value": "70"
        },
        {
          "label": "游戏资讯整理",
          "value": "71"
        },
        {
          "label": "其他",
          "value": "72"
        }
      ]
    },
    "type": {
      "description": "攻略类型，默认不做筛选",
      "options": [
        {
          "label": "置顶",
          "value": "top"
        },
        {
          "label": "精华",
          "value": "refine"
        }
      ]
    }
  },
  "path": "/ff14risingstones/strats/:pid?/:type?",
  "topFeeds": []
}
```
