---
category: Sommoner
uri: '/lol/summoner/v3/summoners/by-name/{소환사명}'
title: '소환사명으로 조회'
type: 'GET'

layout: null
---
소환사명으로 유저 정보를 조회합니다.

### 요청


* 발급받은 api_key를 URL파라미터에 포함해야 합니다.
[시작하기](#/getting-started) 참고

### 응답

해당하는 아이디의 정보를 리턴합니다.

```{
  "id": 1135567,
  "accountId": 439488,
  "name": "SKT T1 Faker",
  "profileIconId": 7,
  "revisionDate": 1493423674000,
  "summonerLevel": 30
}```

For errors responses, see the [response status codes documentation](#response-status-codes).