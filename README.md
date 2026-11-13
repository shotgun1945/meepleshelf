# meepleshelf

A web app that turns your board game collection into a 3D bookshelf.

Pick a shelf (for example, a Kallax-style cube shelf) and place each game box on it — upright or stacked flat, decided box by box. Boxes are drawn at their real size, so you can see whether a game fits a shelf cell and how full each cell is.

## Status

Early prototype. Nothing to run yet.

## Data

- Collection and box dimensions come from the [BoardGameGeek XML API](https://boardgamegeek.com/wiki/page/BGG_XML_API2) (game versions carry width, length and depth).
- The front of each box uses the game's BGG cover image. Side faces are generated from the cover's dominant colors and the game title.
- Games without dimensions on BGG fall back to size-class defaults, which users can override with their own measurements.

Powered by BoardGameGeek. This is a non-commercial hobby project and is not affiliated with BoardGameGeek.

---

## 소개

보유한 보드게임을 실제 상자 크기대로 3D 책장에 배치하고 꾸미는 웹앱입니다. 책장 종류를 고른 뒤, 상자마다 세워 꽂을지 눕혀 쌓을지를 정해 칸에 넣습니다.
