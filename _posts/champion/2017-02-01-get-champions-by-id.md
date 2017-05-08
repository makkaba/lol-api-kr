---
category: Champion
uri: '/lol/platform/v3/champions/{id}'
title: '챔피언 상태 조회'
type: 'GET'

layout: null
---
`/lol/platform/v3/champions/{id}`
해당 챔피언의 상태를 조회합니다.

### 요청  

* 발급받은 api_key를 URL파라미터에 포함해야 합니다.
[시작하기](#/getting-started) 참고

### 응답

해당 챔피언의 상태를 리턴합니다.

```{
  "id": 63,
  "active": true,
  "botEnabled": true,
  "freeToPlay": true,
  "botMmEnabled": true,
  "rankedPlayEnabled": true
}```