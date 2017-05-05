---
category: Match
uri: '/lol/match/v3/timelines/by-match/{matchId}'
title: '타임라인 조회'
type: 'GET'

layout: null
---
해당 경기의 시간별 정보를 조회합니다.

### 요청


* 발급받은 api_key를 URL파라미터에 포함해야 합니다.
[시작하기](#/getting-started) 참고

### 응답

경기의 타임라인 정보를 리턴합니다.

```{
  "frames": [
    {
      "participantFrames": {
        "1": {
          "participantId": 1,
          "position": {
            "x": 561,
            "y": 581
          },
          "currentGold": 500,
          "totalGold": 500,
          "level": 1,
          "xp": 0,
          "minionsKilled": 0,
          "jungleMinionsKilled": 0,
          "dominionScore": 0,
          "teamScore": 0
        },
        2: {
          ...
        },...
      },
      "events": [],
      "timestamp": 169
    },...
  ],
  "frameInterval": 60000
}```