# 上海交通大学 - 计算机学院 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `sjtu`
- Namespace Name: `上海交通大学`
- Route Path: `/sjtu/cs/tzgg/:category`
- Route Name: `计算机学院 - 通知公告`
- Example: `/sjtu/cs/tzgg/bkspy`
- URL: `www.cs.sjtu.edu.cn/notice-xssw-bkspy.html`
- Language: `_None_`
- Categories: `university`
- Maintainers: `BeaCox`
- Source Location: `cs/tzgg.tsx`
- Source Module: `_None_`

## Description
| 本科生培养 | 研究生培养 | 国际交流 | 党建德育 | 团学工作 | 职业发展 | 其他 |
| ---------- | ---------- | -------- | -------- | -------- | -------- | ---- |
| bkspy      | yjspy      | gjjl     | djdy     | txgz     | zyfz     | qt   |

## Parameters
- `category`: 通知类别


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
  - `www.cs.sjtu.edu.cn/notice-xssw-bkspy.html`
- `target`: `/cs/tzgg/bkspy`
### Rule 2
- `source`:
  - `www.cs.sjtu.edu.cn/notice-xssw-yjspy.html`
- `target`: `/cs/tzgg/yjspy`
### Rule 3
- `source`:
  - `www.cs.sjtu.edu.cn/notice-xssw-gjjl.html`
- `target`: `/cs/tzgg/gjjl`
### Rule 4
- `source`:
  - `www.cs.sjtu.edu.cn/notice-xssw-djdy.html`
- `target`: `/cs/tzgg/djdy`
### Rule 5
- `source`:
  - `www.cs.sjtu.edu.cn/notice-xssw-txgz.html`
- `target`: `/cs/tzgg/txgz`
### Rule 6
- `source`:
  - `www.cs.sjtu.edu.cn/notice-xssw-zyfz.html`
- `target`: `/cs/tzgg/zyfz`
### Rule 7
- `source`:
  - `www.cs.sjtu.edu.cn/notice-xssw-qt.html`
- `target`: `/cs/tzgg/qt`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 本科生培养 | 研究生培养 | 国际交流 | 党建德育 | 团学工作 | 职业发展 | 其他 |\n| ---------- | ---------- | -------- | -------- | -------- | -------- | ---- |\n| bkspy      | yjspy      | gjjl     | djdy     | txgz     | zyfz     | qt   |",
  "example": "/sjtu/cs/tzgg/bkspy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "cs/tzgg.tsx",
  "maintainers": [
    "BeaCox"
  ],
  "name": "计算机学院 - 通知公告",
  "parameters": {
    "category": "通知类别"
  },
  "path": "/cs/tzgg/:category",
  "radar": [
    {
      "source": [
        "www.cs.sjtu.edu.cn/notice-xssw-bkspy.html"
      ],
      "target": "/cs/tzgg/bkspy"
    },
    {
      "source": [
        "www.cs.sjtu.edu.cn/notice-xssw-yjspy.html"
      ],
      "target": "/cs/tzgg/yjspy"
    },
    {
      "source": [
        "www.cs.sjtu.edu.cn/notice-xssw-gjjl.html"
      ],
      "target": "/cs/tzgg/gjjl"
    },
    {
      "source": [
        "www.cs.sjtu.edu.cn/notice-xssw-djdy.html"
      ],
      "target": "/cs/tzgg/djdy"
    },
    {
      "source": [
        "www.cs.sjtu.edu.cn/notice-xssw-txgz.html"
      ],
      "target": "/cs/tzgg/txgz"
    },
    {
      "source": [
        "www.cs.sjtu.edu.cn/notice-xssw-zyfz.html"
      ],
      "target": "/cs/tzgg/zyfz"
    },
    {
      "source": [
        "www.cs.sjtu.edu.cn/notice-xssw-qt.html"
      ],
      "target": "/cs/tzgg/qt"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "上海交通大学计算机学院（网络空间安全学院、密码学院）通知公告 - 研究生培养 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1143706728773058560",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cs.sjtu.edu.cn/notice-xssw-yjspy.html",
      "title": "上海交通大学计算机学院 - 通知公告 - 研究生培养",
      "type": "feed",
      "url": "rsshub://sjtu/cs/tzgg/yjspy"
    }
  ],
  "url": "www.cs.sjtu.edu.cn/notice-xssw-bkspy.html"
}
```
