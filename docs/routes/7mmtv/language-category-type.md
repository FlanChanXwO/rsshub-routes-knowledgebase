# 7mmtv - Category

## Coverage
`index-only`

## Route
- Namespace: `7mmtv`
- Namespace Name: `7mmtv`
- Route Path: `/:language?/:category?/:type?`
- Route Name: `Category`
- Example: `/7mmtv/zh/censored_list/all`
- URL: `7mmtv.tv`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/7mmtv/index.tsx')`

## Description
**Language**

| English | 日本語 | 한국의 | 中文 |
| ------- | ------ | ------ | ---- |
| en      | ja     | ko     | zh   |

  **Category**

| Chinese subtitles AV | Censored       | Amateur          | Uncensored       | Asian self-timer | H comics     |
| -------------------- | -------------- | ---------------- | ---------------- | ---------------- | ------------ |
| chinese_list        | censored_list | amateurjav_list | uncensored_list | amateur_list    | hcomic_list |

| Chinese subtitles AV random | Censored random  | Amateur random     | Uncensored random  | Asian self-timer random | H comics random |
| --------------------------- | ---------------- | ------------------ | ------------------ | ----------------------- | --------------- |
| chinese_random             | censored_random | amateurjav_random | uncensored_random | amateur_random         | hcomic_random  |

  **Server**

| All Server | fembed(Full DL) | streamsb(Full DL) | doodstream | streamtape(Full DL) | avgle | embedgram | videovard(Full DL) |
| ---------- | --------------- | ----------------- | ---------- | ------------------- | ----- | --------- | ------------------ |
| all        | 21              | 30                | 28         | 29                  | 17    | 34        | 33                 |

## Parameters
- `language`: Language, see below, `en` as English by default
- `category`: Category, see below, `censored_list` as Censored by default
- `type`: Server, see below, all server by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "**Language**\n\n| English | 日本語 | 한국의 | 中文 |\n| ------- | ------ | ------ | ---- |\n| en      | ja     | ko     | zh   |\n\n  **Category**\n\n| Chinese subtitles AV | Censored       | Amateur          | Uncensored       | Asian self-timer | H comics     |\n| -------------------- | -------------- | ---------------- | ---------------- | ---------------- | ------------ |\n| chinese_list        | censored_list | amateurjav_list | uncensored_list | amateur_list    | hcomic_list |\n\n| Chinese subtitles AV random | Censored random  | Amateur random     | Uncensored random  | Asian self-timer random | H comics random |\n| --------------------------- | ---------------- | ------------------ | ------------------ | ----------------------- | --------------- |\n| chinese_random             | censored_random | amateurjav_random | uncensored_random | amateur_random         | hcomic_random  |\n\n  **Server**\n\n| All Server | fembed(Full DL) | streamsb(Full DL) | doodstream | streamtape(Full DL) | avgle | embedgram | videovard(Full DL) |\n| ---------- | --------------- | ----------------- | ---------- | ------------------- | ----- | --------- | ------------------ |\n| all        | 21              | 30                | 28         | 29                  | 17    | 34        | 33                 |",
  "example": "/7mmtv/zh/censored_list/all",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/7mmtv/index.tsx')",
  "name": "Category",
  "parameters": {
    "category": "Category, see below, `censored_list` as Censored by default",
    "language": "Language, see below, `en` as English by default",
    "type": "Server, see below, all server by default"
  },
  "path": "/:language?/:category?/:type?"
}
```
