# 中時新聞網 - 分類

## Coverage
`index-only`

## Route
- Namespace: `chinatimes`
- Namespace Name: `中時新聞網`
- Route Path: `/:category?`
- Route Name: `分類`
- Example: `/chinatimes/realtimenews`
- URL: `www.chinatimes.com/`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `KingJem`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/chinatimes/index.ts')`

## Description
|     即時     |   熱門  |   政治  | 生活 | 娛樂 |  財經 |  國際 |   言論  |   兩岸  |   軍事   |   社會  |  健康  |  體育  |      科技      |   運勢  | 有影 |  寶島  |
| :----------: | :-----: | :-----: | :--: | :--: | :---: | :---: | :-----: | :-----: | :------: | :-----: | :----: | :----: | :------------: | :-----: | :--: | :----: |
| realtimenews | hotnews | politic | life | star | money | world | opinion | chinese | armament | society | health | sports | technologynews | fortune | tube | taiwan |

## Parameters
- `category`: 分類，見下表，留空為 `realtimenews`


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
  - `www.chinatimes.com/:category/`
  - `www.chinatimes.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "|     即時     |   熱門  |   政治  | 生活 | 娛樂 |  財經 |  國際 |   言論  |   兩岸  |   軍事   |   社會  |  健康  |  體育  |      科技      |   運勢  | 有影 |  寶島  |\n| :----------: | :-----: | :-----: | :--: | :--: | :---: | :---: | :-----: | :-----: | :------: | :-----: | :----: | :----: | :------------: | :-----: | :--: | :----: |\n| realtimenews | hotnews | politic | life | star | money | world | opinion | chinese | armament | society | health | sports | technologynews | fortune | tube | taiwan |",
  "example": "/chinatimes/realtimenews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "KingJem"
  ],
  "module": "() => import('@/routes/chinatimes/index.ts')",
  "name": "分類",
  "parameters": {
    "category": "分類，見下表，留空為 `realtimenews`"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.chinatimes.com/:category/",
        "www.chinatimes.com/"
      ]
    }
  ],
  "url": "www.chinatimes.com/"
}
```
