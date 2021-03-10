---
name: API 설계 및 구현
about: API 설계 및 구현을 위한 이슈 템플릿
title: "[기능] 타이틀"
labels: 서버
assignees: ''

---

## 📍 목적
> 목적

<br>

### 💡 API 명세서
> 1. 00 API
* Request

**URL :**  /api/00
**Method :** 00
**Content-type :** application/json; charset=utf-8
```js
{
   name: String,
   description: String
}
```
* 예시
```js
 { name: "개발하기", description: "로그인 기능 구현하기" }
```

<br>

* Response  

**Status** 
>**성공 :** 201 (Created)
>**실패 :** 400 (Bad Request)  

**Content-type :** application/json; charset=utf-8

* 성공
```js
{
   success: Boolean,
   msg: String
}
```
* 예시
```js
{
   success: true,
   msg: "00 등록에 성공하셨습니다."
}
```

<br>

* 실패
```js
{
   success: Boolean,
   msg: String (실패 원인)
}
```
* 예시
```js
{
   success: false,
   msg: "이름이 일치하지 않습니다."
}
```

<br>
<br>

> 1. 00 API
* Request

**URL :**  /api/00
**Method :** 00
**Content-type :** application/json; charset=utf-8
```js
{
   name: String,
   description: String
}
```
* 예시
```js
 { name: "개발하기", description: "로그인 기능 구현하기" }
```

<br>

* Response  

**Status** 
>**성공 :** 201 (Created)
>**실패 :** 400 (Bad Request)  

**Content-type :** application/json; charset=utf-8

* 성공
```js
{
   success: Boolean,
   msg: String
}
```
* 예시
```js
{
   success: true,
   msg: "00 등록에 성공하셨습니다."
}
```

<br>

* 실패
```js
{
   success: Boolean,
   msg: String (실패 원인)
}
```
* 예시
```js
{
   success: false,
   msg: "이름이 일치하지 않습니다."
}
```
