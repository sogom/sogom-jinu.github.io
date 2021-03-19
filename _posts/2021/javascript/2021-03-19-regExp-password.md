---
title : 정규표현식 _ 비밀번호
layout: single
author_profile : true
read_time : true
related : true
categories:
- javaScript
tags :
- regExp
description: 영어대문자, 소문자, 숫자 포함 10~12자리 입력
---

### 영어대문자, 소문자, 숫자 포함 10~12자리 입력
``` javaScript
let regexp = /^(?=.{10,12})(?=.*[a-z])(?=.*[A-Z])(?=.*[0-9]).*$/g;
```