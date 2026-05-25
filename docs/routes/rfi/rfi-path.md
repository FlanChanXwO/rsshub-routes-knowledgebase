# Radio France Internationale - Generic News

## Coverage
`index-only`

## Route
- Namespace: `rfi`
- Namespace Name: `Radio France Internationale`
- Route Path: `/rfi/:path{.+}?`
- Route Name: `Generic News`
- Example: `/rfi`
- URL: `rfi.fr`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
::: tip

- To subscribe to [English News](https://www.rfi.fr/en/), which URL is `https://www.rfi.fr/en`, you can get the route as [`/rfi/en`](https://rsshub.app/rfi/en).
- To subscribe to [English Europe News](https://www.rfi.fr/en/europe/), which URL is `https://www.rfi.fr/en/europe`, you can get the route as [`/rfi/en/europe`](https://rsshub.app/rfi/en/europe).
- To subscribe to topic [Paris Olympics 2024](https://www.rfi.fr/en/tag/paris-olympics-2024/), which URL is `https://www.rfi.fr/en/tag/paris-olympics-2024`, you can get the route as [`/rfi/en/tag/paris-olympics-2024`](https://rsshub.app/rfi/en/tag/paris-olympics-2024).

:::

::: warning
This route does not support podcasts, please use the Offical RSS feed instead.
:::

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `rfi.fr/*path`
- `target`: `/:path`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "::: tip\n\n- To subscribe to [English News](https://www.rfi.fr/en/), which URL is `https://www.rfi.fr/en`, you can get the route as [`/rfi/en`](https://rsshub.app/rfi/en).\n- To subscribe to [English Europe News](https://www.rfi.fr/en/europe/), which URL is `https://www.rfi.fr/en/europe`, you can get the route as [`/rfi/en/europe`](https://rsshub.app/rfi/en/europe).\n- To subscribe to topic [Paris Olympics 2024](https://www.rfi.fr/en/tag/paris-olympics-2024/), which URL is `https://www.rfi.fr/en/tag/paris-olympics-2024`, you can get the route as [`/rfi/en/tag/paris-olympics-2024`](https://rsshub.app/rfi/en/tag/paris-olympics-2024).\n\n:::\n\n::: warning\nThis route does not support podcasts, please use the Offical RSS feed instead.\n:::",
  "example": "/rfi",
  "heat": 68,
  "location": "news.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "Generic News",
  "path": "/:path{.+}?",
  "radar": [
    {
      "source": [
        "rfi.fr/*path"
      ],
      "target": "/:path"
    }
  ],
  "topFeeds": [
    {
      "description": "同步、随时跟踪法广政治、文化、体育新闻，了解法国、中国与世界各地大事 - Powered by RSSHub",
      "errorAt": "2026-05-23T21:27:46.335Z",
      "errorMessage": "[GET] \"https://www.rfi.fr/cn/%E7%A7%91%E6%8A%80%E4%B8%8E%E6%96%87%E5%8C%96/20260523-%E7%AC%AC79%E5%B1%8A%E6%88%9B%E7%BA%B3%E7%94%B5%E5%BD%B1%E8%8A%82%E8%90%BD%E4%B8%8B%E9%A3%8E%E5%B8%B7%E5%B9%95-%E5%B3%A1%E6%B9%BE%E6%9C%AC%E5%B1%8A%E5%BD%B1%E8%8A%82%E7%9A%84%E9%87%91%E6%A3%95%E6%A6%88%E5%A5%96%E5%BE%97%E4%B8%BB%EF%BC%8C%E5%BD%B1%E7%89%87-%C2%B7%C2%B7%E5%B3%A1%E6%B9%BE-%E7%9A%84%E5%AF%BC%E6%BC%94%E5%85%8B%E9%87%8C%E6%96%AF%E6%B1%80%C2%B7%E8%92%99%E5%90%89-cristian-mungiu-%E4%BB%8E%E8%8B%8F%E6%A0%BC%E5%85%B0%E8%91%97%E5%90%8D%E5%A5%B3%E6%BC%94%E5%91%98%E8%92%82%E5%B0%94%E8%BE%BE%C2%B7%E6%96%AF%E6%96%87%E9%A1%BF%E6%89%8B%E4%B8%AD%E6%8E%A5%E8%BF%87%E4%BA%86%E6%9C%AC%E6%AC%A1%E5%BD%B1%E8%8A%82%E7%9A%84%E6%9C%80%E9%AB%98%E5%A5%96%E9%A1%B9-%E4%BB%96%E8%A1%A8%E7%A4%BA-%E4%BF%84%E5%9B%BD%E5%AF%BC%E6%BC%94%E5%AE%89%E5%BE%B7%E7%83%88%C2%B7%E5%85%B9%E7%BB%B4%E4%BA%9A%E9%87%91%E9%87%87%E5%A4%AB%E7%9A%84-%E5%BC%A5%E8%AF%BA%E9%99%B6-minotaur-%E6%91%98%E5%8F%96%E4%BA%86%E8%AF%84%E5%AE%A1%E5%9B%A2%E5%A4%A7%E5%A5%96%E8%AF%84%E5%AE%A1%E5%9B%A2%E5%A5%96%E9%A2%81%E5%8F%91%E7%BB%99%E4%BA%86%E5%BE%B7%E5%9B%BD%E5%AF%BC%E6%BC%94%E7%93%A6%E8%8E%B1%E6%96%AF%E5%8D%A1%C2%B7%E6%A0%BC%E9%87%8C%E6%96%AF%E5%B7%B4%E8%B5%AB-valeska-grisebach-%E6%89%A7%E5%AF%BC%E7%9A%84-%E5%90%91%E5%BE%80%E7%9A%84%E5%86%92%E9%99%A9-%E6%9C%80%E4%BD%B3%E5%AF%BC%E6%BC%94%E5%A5%96%E9%A2%81%E7%BB%99%E4%BA%86%E8%A5%BF%E7%8F%AD%E7%89%99%E5%BD%B1%E7%89%87-%E9%BB%91%E8%89%B2%E7%8F%A0%E5%AD%90-%E7%9A%84%E5%AF%BC%E6%BC%94%E5%8F%8C%E4%BA%BA%E7%BB%84%E5%90%88%E5%93%88%E7%BB%B4%E5%B0%94%C2%B7%E5%8D%A1%E5%B0%94%E6%B2%83%E5%92%8C%E5%93%88%E7%BB%B4%E5%B0%94%C2%B7%E5%AE%89%E5%B8%83%E7%BD%97%E8%A5%BF%E4%BB%A5%E5%8F%8A-%E6%95%85%E5%9C%9F-%E4%B8%80%E7%89%87%E7%9A%84%E5%AF%BC%E6%BC%94-%E7%BC%96%E5%89%A7%E5%B8%95%E7%BB%B4%E5%B0%94%C2%B7%E5%B8%95%E5%A4%AB%E5%88%A9%E7%A7%91%E5%A4%AB%E6%96%AF%E5%9F%BA-%E6%9C%80%E4%BD%B3%E7%BC%96%E5%89%A7%E5%A5%96%E9%A2%81%E7%BB%99%E4%BA%86-%E6%88%91%E4%BB%AC%E7%9A%84%E6%95%91%E8%B5%8E-%E4%B8%80%E7%89%87%E7%9A%84%E7%BC%96%E5%89%A7-%E5%AF%BC%E6%BC%94%E5%9F%83%E5%8A%AA%E5%9F%83%E5%B0%94%C2%B7%E9%A9%AC%E9%9B%B7-emmanuel-marre-%E6%9C%80%E4%BD%B3%E5%A5%B3%E4%B8%BB%E8%A7%92%E5%A5%96%E5%BE%97%E4%B8%BB%E6%98%AF%E7%94%B1%E8%B5%B5%E5%A9%B7%E5%AE%A3%E5%B8%83%E7%9A%84%EF%BC%8C%E5%BE%97%E5%A5%96%E6%BC%94%E5%91%98%E6%98%AF%E6%BB%A8%E5%8F%A3%E9%BE%99%E4%BB%8B-hamaguchi-ryusuke-%E6%89%A7%E5%AF%BC%E7%9A%84-%E7%AA%81%E5%A6%82%E5%85%B6%E6%9D%A5-%E4%B8%80%E7%89%87%E7%9A%84%E4%B8%A4%E4%BD%8D%E4%B8%BB%E6%BC%94-%E6%AF%94%E5%88%A9%E6%97%B6%E5%A5%B3%E6%BC%94%E5%91%98%E7%BB%B4%E5%90%89%E5%B0%BC%C2%B7%E8%89%BE%E8%8F%B2%E6%8B%89-virginie-efira-%E5%92%8C%E6%97%A5%E6%9C%AC%E6%BC%94%E5%91%98%E5%86%88%E6%9C%AC%E5%A4%9A%E7%BB%AA%E6%91%98%E5%BE%97-%E6%9C%80%E4%BD%B3%E7%94%B7%E4%B8%BB%E8%A7%92%E5%A5%96%E7%88%86%E5%86%B7%E9%97%A8%E9%A2%81%E7%BB%99%E4%BA%86%E6%AF%94%E5%88%A9%E6%97%B6%E5%8D%A2%E5%8D%A1%E6%96%AF%C2%B7%E5%BE%B7%E9%9C%8D%E7%89%B9%E6%89%A7%E5%AF%BC%E7%9A%84-%E6%87%A6%E5%A4%AB-%E7%9A%84%E4%B8%A4%E4%BD%8D%E5%B9%B4%E8%BD%BB%E4%B8%BB%E6%BC%94%E5%9F%83%E5%8A%AA%E5%9F%83%E5%B0%94%C2%B7%E9%A9%AC%E5%9F%BA%E4%BA%9A-emmanuel-macchia-%E5%92%8C%E7%93%A6%E6%9C%97%E5%9D%A6%C2%B7%E5%86%88%E5%B8%95%E5%86%85-valentin-campagne-%E5%85%B8%E7%A4%BC%E4%B8%80%E5%BC%80%E5%A7%8B%EF%BC%8C%E5%85%88%E5%B0%86%E7%9F%AD%E7%89%87%E5%8D%95%E5%85%83%E7%9A%84%E9%87%91%E6%A3%95%E6%A6%88%E5%A5%96%E9%A2%81%E5%8F%91%E7%BB%99%E4%BA%86%E7%94%B1%E8%B4%B9%E5%BE%B7%E9%87%8C%E7%A7%91%C2%B7%E8%B7%AF%E6%98%93%E6%96%AF-federico-luis-%E6%8B%8D%E6%91%84%E7%9A%84-%E8%87%B4%E5%AF%B9%E6%89%8B-aux-adversaires-%EF%BC%8C%E5%92%8C%E5%BE%80%E5%B9%B4%E4%B8%80%E6%A0%B7%EF%BC%8C%E4%B8%93%E9%97%A8%E9%A2%81%E7%BB%99%E9%A6%96%E6%AC%A1%E5%85%A5%E5%9B%B4%E6%88%9B%E7%BA%B3%E7%94%B5%E5%BD%B1%E8%8A%82%E7%9A%84%E5%89%A7%E6%83%85%E9%95%BF%E7%89%87%E7%9A%84%E9%87%91%E6%91%84%E5%BD%B1%E6%9C%BA%E5%A5%96%EF%BC%8C%E4%BB%8A%E5%B9%B4%E9%A2%81%E7%BB%99%E4%BA%86%E5%8D%A2%E6%97%BA%E8%BE%BE%E5%A5%B3%E5%AF%BC%E6%BC%94%E7%8E%9B%E4%B8%BD%C2%B7%E5%85%8B%E8%8E%B1%E9%97%A8%E6%B1%80%C2%B7%E6%9D%9C%E8%90%A8%E8%B4%9D%E8%A9%B9%E5%8D%9A%E6%89%A7%E5%AF%BC%E7%9A%84-%E6%9C%AC%E5%B0%BC%E9%A9%AC%E7%BA%B3-%E9%9A%8F%E5%90%8E%E6%98%AF%E8%AF%84%E5%AE%A1%E5%9B%A2%E7%9A%84%E8%AF%84%E5%A7%94%E5%87%BA%E5%9C%BA-%E9%9A%8F%E5%90%8E%E6%98%AF%E5%9C%A8%E5%BD%B1%E8%8A%82%E9%97%AD%E5%B9%95%E5%BC%8F%E4%B8%8A%E9%A2%81%E5%8F%91%E8%A1%A8%E5%BD%B0%E8%8E%B7%E5%A5%96%E8%80%85%E8%81%8C%E4%B8%9A%E7%94%9F%E6%B6%AF%E7%9A%84%E8%8D%A3%E8%AA%89%E9%87%91%E6%A3%95%E6%A6%88%EF%BC%8C%E5%9B%A0%E6%95%85%E6%9C%AA%E8%83%BD%E5%87%BA%E5%B8%AD%E4%BB%AA%E5%BC%8F%E7%9A%84%E6%9C%AC%E5%B1%8A%E8%8E%B7%E5%A5%96%E8%80%85-%E7%BE%8E%E5%9B%BD%E6%AD%8C%E6%98%9F-%E6%BC%94%E5%91%98-%E5%AF%BC%E6%BC%94%E8%8A%AD%E8%8A%AD%E6%8B%89%C2%B7%E5%8F%B2%E7%BF%A0%E7%8F%8A%E7%89%B9%E5%88%AB%E8%AF%B7%E6%B3%95%E5%9B%BD%E5%BD%B1%E6%98%9F%E4%BC%8A%E8%8E%8E%E8%B4%9D%E5%B0%94%C2%B7%E4%BA%8E%E8%B4%9D%E5%B0%94%E4%BB%A3%E5%A5%B9%E9%A2%86%E5%8F%96%E9%87%91%E6%A3%95%E6%A6%88%EF%BC%8C%E5%B9%B6%E5%8F%91%E8%A1%A8%E4%BA%86%E9%95%BF%E7%AF%87%E4%BB%8B%E7%BB%8D%E6%84%9F%E8%A8%80-%E7%AC%AC79%E8%8A%82%E6%88%9B%E7%BA%B3%E5%BD%B1%E8%8A%82%E9%97%AD%E5%B9%95%E5%BC%8F%E6%98%AF%E7%94%B1%E8%89%BE%C2%B7%E6%B5%B7%E8%BE%BE%E6%8B%89%E4%B8%BB%E6%8C%81%EF%BC%8C%E5%A5%B9%E6%9B%BE%E5%9C%A85%E6%9C%8812%E6%97%A5%E4%B8%BB%E6%8C%81%E4%BA%86%E5%BD%B1%E8%8A%82%E7%9A%84%E5%BC%80%E5%B9%95%E5%BC%8F-%E6%91%98%E5%BE%97%E9%87%91%E6%A3%95%E6%A6%88\": 414 Request-URI Too Large\n",
      "id": "58701529235465216",
      "image": "https://s.rfi.fr/media/display/020b8dae-e6c1-11ee-a196-005056bfb2b6/w:1280/p:16x9/img-default-RFI.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.rfi.fr/cn/",
      "title": "法广 - 时事与新闻直播 - RFI - 法国国际广播电台",
      "type": "feed",
      "url": "rsshub://rfi/cn"
    },
    {
      "description": "Suivez toute l'information politique, culturelle, sportive en direct et en continu sur RFI. Les dernières informations, news et actualités en France et à l'international. - Powered by RSSHub",
      "errorAt": "2025-08-14T11:51:28.460Z",
      "errorMessage": "Unexpected non-whitespace character after JSON at position 4084 (line 4 column 13)\n",
      "id": "76670519253188608",
      "image": "https://s.rfi.fr/media/display/020b8dae-e6c1-11ee-a196-005056bfb2b6/w:1280/p:16x9/img-default-RFI.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.rfi.fr/fr/",
      "title": "RFI - Actualités, info, news en direct - Radio France Internationale",
      "type": "feed",
      "url": "rsshub://rfi/fr"
    }
  ],
  "url": "rfi.fr"
}
```
