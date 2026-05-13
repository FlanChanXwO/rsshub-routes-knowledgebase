# Telecompaper - News

## Coverage
`index-only`

## Route
- Namespace: `telecompaper`
- Namespace Name: `Telecompaper`
- Route Path: `/news/:caty/:year?/:country?/:type?`
- Route Name: `News`
- Example: `/telecompaper/news/mobile/2020/China/News`
- URL: `telecompaper.com`
- Language: `en`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/telecompaper/news.ts')`

## Description
Category

| WIRELESS | BROADBAND | VIDEO     | GENERAL | IT | INDUSTRY RESOURCES |
| -------- | --------- | --------- | ------- | -- | ------------------ |
| mobile   | internet  | boardcast | general | it | industry-resources |

::: tip
  If `country` or `type` includes empty space, use `-` instead. For example, `United States` needs to be replaced with `United-States`, `White paper` needs to be replaced with `White-paper`

  Filters in [INDUSTRY RESOURCES](https://www.telecompaper.com/industry-resources) only provides `Content Type` which corresponds to `type`. `year` and `country` are not supported.
:::

## Parameters
- `caty`: Category, see table below
- `year`: Year. The year in respective category page filter, `all` for unlimited year, empty by default
- `country`: Country or continent, `all` for unlimited country or continent, empty by default
- `type`: Type, can be found in the `Types` filter, `all` for unlimited type, unlimited by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
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
    "journal"
  ],
  "description": "Category\n\n| WIRELESS | BROADBAND | VIDEO     | GENERAL | IT | INDUSTRY RESOURCES |\n| -------- | --------- | --------- | ------- | -- | ------------------ |\n| mobile   | internet  | boardcast | general | it | industry-resources |\n\n::: tip\n  If `country` or `type` includes empty space, use `-` instead. For example, `United States` needs to be replaced with `United-States`, `White paper` needs to be replaced with `White-paper`\n\n  Filters in [INDUSTRY RESOURCES](https://www.telecompaper.com/industry-resources) only provides `Content Type` which corresponds to `type`. `year` and `country` are not supported.\n:::",
  "example": "/telecompaper/news/mobile/2020/China/News",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/telecompaper/news.ts')",
  "name": "News",
  "parameters": {
    "caty": "Category, see table below",
    "country": "Country or continent, `all` for unlimited country or continent, empty by default",
    "type": "Type, can be found in the `Types` filter, `all` for unlimited type, unlimited by default",
    "year": "Year. The year in respective category page filter, `all` for unlimited year, empty by default"
  },
  "path": "/news/:caty/:year?/:country?/:type?"
}
```
