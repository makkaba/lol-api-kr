---
category: Match
uri: '/lol/match/v3/matchlists/by-account/{accountId}'
title: '경기 상세 조회'
type: 'GET'

layout: null
---
`/lol/match/v3/matchlists/by-account/{accountId}`
경기 리스트를 상세 조회합니다.

### 요청


* 발급받은 api_key를 URL파라미터에 포함해야 합니다.
[시작하기](#/getting-started) 참고
* 가능한 URL 쿼리 파라미터  
beginTime, endIndex, season, champion, beginIndex, queue, endTime

### 응답

해당하는 아이디의 경기 DTO를 리턴합니다.

```{
  "matches": [...]
  "startIndex": 0,
  "endIndex": 1662,
  "totalGames": 1662,
}```