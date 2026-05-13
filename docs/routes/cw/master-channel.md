# 天下雜誌 - 主頻道

## Coverage
`index-only`

## Route
- Namespace: `cw`
- Namespace Name: `天下雜誌`
- Route Path: `/master/:channel`
- Route Name: `主頻道`
- Example: `/cw/master/8`
- URL: `cw.com.tw`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `master.ts`
- Source Module: `() => import('@/routes/cw/master.ts')`

## Description
| 主頻道名稱 | 主頻道 ID |
| ---------- | --------- |
| 財經       | 8         |
| 產業       | 7         |
| 國際       | 9         |
| 管理       | 10        |
| 環境       | 12        |
| 教育       | 13        |
| 人物       | 14        |
| 政治社會   | 77        |
| 調查排行   | 15        |
| 健康關係   | 79        |
| 時尚品味   | 11        |
| 運動生活   | 103       |
| 重磅外媒   | 16        |

## Parameters
- `channel`: 主頻道 ID，可在 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
    "traditional-media"
  ],
  "description": "| 主頻道名稱 | 主頻道 ID |\n| ---------- | --------- |\n| 財經       | 8         |\n| 產業       | 7         |\n| 國際       | 9         |\n| 管理       | 10        |\n| 環境       | 12        |\n| 教育       | 13        |\n| 人物       | 14        |\n| 政治社會   | 77        |\n| 調查排行   | 15        |\n| 健康關係   | 79        |\n| 時尚品味   | 11        |\n| 運動生活   | 103       |\n| 重磅外媒   | 16        |",
  "example": "/cw/master/8",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "master.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/cw/master.ts')",
  "name": "主頻道",
  "parameters": {
    "channel": "主頻道 ID，可在 URL 中找到"
  },
  "path": "/master/:channel"
}
```
