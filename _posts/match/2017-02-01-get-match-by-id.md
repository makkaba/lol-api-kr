---
category: Match
uri: '/lol/match/v3/matches/{matchId}'
title: '경기 정보 조회'
type: 'GET'

layout: null
---
`/lol/match/v3/matches/{matchId}`
경기ID로 경기 정보를 조회합니다.

### 요청


* 발급받은 api_key를 URL파라미터에 포함해야 합니다.
[시작하기](#/getting-started) 참고

### 응답

해당하는 아이디의 경기 DTO를 리턴합니다.

```{
  "gameId": 2804504366,
  "platformId": "KR",
  "gameCreation": 1493447504945,
  "gameDuration": 1221,
  "queueId": 2,
  "mapId": 11,
  "seasonId": 8,
  "gameVersion": "7.8.184.113",
  "gameMode": "CLASSIC",
  "gameType": "MATCHED_GAME",
  "teams": [...],
  "participants": [...],
  "participantIdentities": [...]
}```

For errors responses, see the [response status codes documentation](#response-status-codes).