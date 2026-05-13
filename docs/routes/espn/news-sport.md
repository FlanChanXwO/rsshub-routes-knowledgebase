# ESPN - News

## Coverage
`index-only`

## Route
- Namespace: `espn`
- Namespace Name: `ESPN`
- Route Path: `/news/:sport`
- Route Name: `News`
- Example: `/espn/news/nba`
- URL: `espn.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `weijianduan0302`
- Source Location: `news.tsx`
- Source Module: `() => import('@/routes/espn/news.tsx')`

## Description
Get the news feed of the sport you love on ESPN.
| Sport                |  sport  |  Sport         |  sport  |
|----------------------|---------|----------------|---------|
| 🏀 NBA                | nba     | 🎾 Tennis       | tennis  |
| 🏀 WNBA               | wnba    | ⛳️ Golf         | golf    |
| 🏈 NFL                | nfl     | 🏏 Cricket      | cricket |
| ⚾️ MLB                | mlb     | ⚽️ Soccer       | soccer  |
| 🏒 NHL                | nhl     | 🏎️ F1           | f1      |
| ⛹️ College Basketball | ncb      | 🥊 MMA          | mma     |
| 🏟️️ College Football   | ncf     | 🏈 UFL          | ufl     |
| 🏉 Rugby              | rugby   | 🃏 Poker        | poker   |

## Parameters
- `sport`: sport category, can be nba, nfl, mlb, nhl etc.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `espn.com/:sport*`
- `target`: `/news/:sport`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Get the news feed of the sport you love on ESPN.\n| Sport                |  sport  |  Sport         |  sport  |\n|----------------------|---------|----------------|---------|\n| 🏀 NBA                | nba     | 🎾 Tennis       | tennis  |\n| 🏀 WNBA               | wnba    | ⛳️ Golf         | golf    |\n| 🏈 NFL                | nfl     | 🏏 Cricket      | cricket |\n| ⚾️ MLB                | mlb     | ⚽️ Soccer       | soccer  |\n| 🏒 NHL                | nhl     | 🏎️ F1           | f1      |\n| ⛹️ College Basketball | ncb      | 🥊 MMA          | mma     |\n| 🏟️️ College Football   | ncf     | 🏈 UFL          | ufl     |\n| 🏉 Rugby              | rugby   | 🃏 Poker        | poker   |",
  "example": "/espn/news/nba",
  "location": "news.tsx",
  "maintainers": [
    "weijianduan0302"
  ],
  "module": "() => import('@/routes/espn/news.tsx')",
  "name": "News",
  "parameters": {
    "sport": "sport category, can be nba, nfl, mlb, nhl etc."
  },
  "path": "/news/:sport",
  "radar": [
    {
      "source": [
        "espn.com/:sport*"
      ],
      "target": "/news/:sport"
    }
  ]
}
```
