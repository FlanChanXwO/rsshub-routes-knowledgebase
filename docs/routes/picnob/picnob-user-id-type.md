# Instagram - User Profile - Pixnoy

## Coverage
`index-only`

## Route
- Namespace: `picnob`
- Namespace Name: `Instagram`
- Route Path: `/picnob/user/:id/:type?`
- Route Name: `User Profile - Pixnoy`
- Example: `/picnob/user/xlisa_olivex`
- URL: `www.instagram.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `TonyRL, micheal-death, AiraNadih, DIYgod, hyoban, Rongronggg9`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Instagram id
- `type`: Type of profile page (profile or tagged)


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
  - `www.pixnoy.com/profile/:id`
- `target`: `/user/:id`
### Rule 2
- `source`:
  - `www.pixnoy.com/profile/:id/tagged`
- `target`: `/user/:id/tagged`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/picnob/user/xlisa_olivex",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 38463,
  "location": "user.ts",
  "maintainers": [
    "TonyRL",
    "micheal-death",
    "AiraNadih",
    "DIYgod",
    "hyoban",
    "Rongronggg9"
  ],
  "name": "User Profile - Pixnoy",
  "parameters": {
    "id": "Instagram id",
    "type": "Type of profile page (profile or tagged)"
  },
  "path": "/user/:id/:type?",
  "radar": [
    {
      "source": [
        "www.pixnoy.com/profile/:id"
      ],
      "target": "/user/:id"
    },
    {
      "source": [
        "www.pixnoy.com/profile/:id/tagged"
      ],
      "target": "/user/:id/tagged"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 301 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "📚 幫助忙碌的你．提煉好書精華 📝 #閱讀前哨站．10分鐘每週多認識一本書 🎧 #下一本讀什麼．20分鐘快速聽懂一本書 👇 訂閱電子報．收聽Podcast ．看線上課程 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76501314147596288",
      "image": "https://sp1.pixnoy.com/a/a_15553397507_3631285038151332104362324843_95c00d485dc12c84ffa60294d184bcb0.jpg?o=aHR0cHM6Ly9zY29udGVudC1vcmQ1LTMuY2RuaW5zdGFncmFtLmNvbS92L3Q1MS4yODg1LTE5LzQ5NTkyNjc3MV8xODEwMzk2NDc5NzUxNzUwOF83NzEzODU3NDIzMjcxNTk1NzgyX24uanBnP3N0cD1kc3QtanBnX3MxNTB4MTUwX3R0NiZlZmc9ZXlKMlpXNWpiMlJsWDNSaFp5STZJbkJ5YjJacGJHVmZjR2xqTG1ScVlXNW5ieTQyTURBdVl6SWlmUSZfbmNfaHQ9c2NvbnRlbnQtb3JkNS0zLmNkbmluc3RhZ3JhbS5jb20mX25jX2NhdD0xMDAmX25jX29jPVE2Y1oyZ0ZMOUJkS1ZwNFdaQnFHZDV6c094XzVYTk5DMHlLeUhDRGJCMDcwak9kY1RsV0phdzdBaTVPVF9fNzZGSEtrRUJ6bnRPS1FwS25rcGxMWGJHSWx2dXBSJl9uY19vaGM9dmN1dTFDQ0xjdDBRN2tOdndHUGZ5NVcmX25jX2dpZD0wRkdUdDZObkhaM1BlOVZyMTRjX0lRJmVkbT1BTEdiSlBNQkFBQUEmY2NiPTctNSZvaD0wMF9BZjViQVZRVzRQSjByalM5ZE9ZcXpNSVk1cktwc3g3endNUGpaSWVUXzNEYzZnJm9lPTZBMDlCMzdBJl9uY19zaWQ9N2QzYWM1&h=0dcec6ff7777d8e28089636fadbe8bbb",
      "ownerUserId": null,
      "siteUrl": "https://www.pixnoy.com/profile/readingoutpost//",
      "title": "瓦基｜閱讀前哨站｜下一本讀什麼 (@readingoutpost/) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob/user/readingoutpost%2F"
    },
    {
      "description": "🕵️‍♂️ - Powered by RSSHub",
      "errorAt": "2026-03-02T06:05:44.633Z",
      "errorMessage": "503 Service Unavailable\n",
      "id": "60578834160918528",
      "image": "https://sp1.pixnoy.com/a/a_37308434192_56381528563818172856286031743230303854382834_811dc43be233d6fcc19e41f4f830ff21.jpg?o=aHR0cHM6Ly9zY29udGVudC1hdGwzLTMuY2RuaW5zdGFncmFtLmNvbS92L3Q1MS44Mjc4Ny0xNS82MDg3MTU4NzRfMTgwODUwNDkxMjMyNDIxOTNfNTE5MzExODAwNzE4NTgwNDQyNV9uLmpwZz9zdHA9ZHN0LWpwZ19zMTUweDE1MF90dDYmZWZnPWV5SjJaVzVqYjJSbFgzUmhaeUk2SW5CeWIyWnBiR1ZmY0dsakxtUnFZVzVuYnk0eE1ESTBMbU15SW4wJl9uY19odD1zY29udGVudC1hdGwzLTMuY2RuaW5zdGFncmFtLmNvbSZfbmNfY2F0PTEmX25jX29jPVE2Y1oyUUhOSzRLQUhmRVNjUUNZQlBkcVJidUtVT05Za1VlYUNsOEFqUnVyOTNrdW43aXFsQ1hZTG5VNHEyeERncXFfb3ZaWkp0TjRsZGxqT29Fc1JIQ1l3QncxJl9uY19vaGM9SEtuRUdpMGZfeE1RN2tOdndHbW5aUzkmX25jX2dpZD1lcGFlTlNURmtiNXhnLWFKTmJXUTJnJmVkbT1BTEdiSlBNQkFBQUEmY2NiPTctNSZvaD0wMF9BZnhlVjl5b25NRFppLUUtazNYYzh5WS1OX29ucWN0MmwzaGZFcm1UQl9pNVNnJm9lPTY5QURERjVEJl9uY19zaWQ9N2QzYWM1&h=5b8d665763b579ef1e47821d8fab1336",
      "ownerUserId": null,
      "siteUrl": "https://www.pixnoy.com/profile/minami_hamabe.official//",
      "title": "浜辺美波 Hamabe Minami (@minami_hamabe.official/) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob/user/minami_hamabe.official%2F"
    }
  ],
  "view": 2
}
```
