---
title: '응답코드'

layout: null
---

### Success

* 성공 시 `200 OK`를 돌려줍니다.
* `GET` 메소드의 경우, 해당 모델의 DTO를 돌려주는 경우가 많습니다.

### Error

* 에러 처리가 되어있는 경우, 메세지와 코드가 함께 전달됩니다.

```{
  "status": {
    "message": "Unauthorized",
    "status_code": 401
  }
}```