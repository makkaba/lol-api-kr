---
category: Static
uri: '/lol/static-data/v3/champions'
title: '챔피언의 리소스 조회'
type: 'GET'

layout: null
---
챔피언의 리소스(정적 데이터)를 조회합니다.

### 요청


* 발급받은 api_key를 URL파라미터에 포함해야 합니다.
[시작하기](#/getting-started) 참고
* 가능한 URL 파라미터  


|KEY|VALUE|TYPE|etc|
|---|---|---|---|
|version|7.9.1, ...|string|data dragon버전입니다|
|champListData|all, allytips, altimages, blurb, enemytips, image, info, lore, partype, passive, recommended, skins, spells, stats, tags|string||
|dataById|true/false|boolean||
|locale|en_US, ...|string||

### 응답

챔피언의 리소스 데이터를 리턴합니다.

```
{
  "type": "champion",
  "format": "full",
  "version": "7.9.1",
  "data": {
      "Jax": {},
      ...
  },
  "keys": {
    "1": "Annie",
    ...
  }
}```