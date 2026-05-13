# 厚生労働省 - 毎月勤労統計調査 全国調査（月別結果）

## Coverage
`index-only`

## Route
- Namespace: `mhlw`
- Namespace Name: `厚生労働省`
- Route Path: `/mhlw/monthly-labour-survey`
- Route Name: `毎月勤労統計調査 全国調査（月別結果）`
- Example: `/mhlw/monthly-labour-survey`
- URL: `www.mhlw.go.jp/toukei/list/30-1a.html`
- Language: `_None_`
- Categories: `government`
- Maintainers: `TonyRL`
- Source Location: `monthly-labour-survey.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.mhlw.go.jp/toukei/list/30-1a.html`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/mhlw/monthly-labour-survey",
  "heat": 1,
  "location": "monthly-labour-survey.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "毎月勤労統計調査 全国調査（月別結果）",
  "path": "/monthly-labour-survey",
  "radar": [
    {
      "source": [
        "www.mhlw.go.jp/toukei/list/30-1a.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:37:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "毎月勤労統計調査（全国調査・地方調査） 結果の概要について紹介しています。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "269340703253877760",
      "image": "https://www.mhlw.go.jp/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.mhlw.go.jp/toukei/list/30-1a.html",
      "title": "毎月勤労統計調査（全国調査・地方調査） 結果の概要｜厚生労働省",
      "type": "feed",
      "url": "rsshub://mhlw/monthly-labour-survey"
    }
  ],
  "url": "www.mhlw.go.jp/toukei/list/30-1a.html"
}
```
