---
title: arrow Function (화살표함수)
layout: single
author_profile: true
read_time: true
related: true
categories:
  - javascript
tags:
  - arrow Function
  - 화살표함수
description: arrow Function
---

기존 `function` 키워드를 이용해 생성하던 함수를 `=>` 를 이용해 함수를 생성한다.

```javascript
function sum(x, y) {
  return x + y;
}
```

```javascript
const sum = (x, y) => {
  return x + y;
};
// 혹은 아래와 같이 return 키워드를 사용하지않고 바로 리턴할 수 있다.
const sum = (x, y) => x + y;
```

## 화살표함수의 기본문법

```
    const/let 함수명 = (매개변수) => {실행구문}
```

```javascript
const multiple = (x, y) => {
  return x * y;
};
```

## 화살표함수를 하용하는 몇가지 방법

1. 매개변수가 하나인경우

```javascript
let potato = (x) => {
  return x + " potato";
};
```

2. 함수의 실행구문이 하나인 경우

```javascript
let potato = (x) => x + " potato";
```

3. 객체를 리턴해야 하는 경우

```javascript
let user = () => ({
  name: "sogom",
  age: 17,
});
// 소괄호를 감싸면 객체를 리턴할 수 있다.
```
