---
layout: post
title: "Ubuntu에서 CURL 라이브러리 설치하기"
excerpt: "Ubuntu에서 CURL 라이브러리를 설치하는 방법입니다."
date: 2018-04-16 14:06:00
categories: [Ubuntu]
tags: [Ubuntu, CURL]
comments: true
---



### Install

```
$sudo apt-get install libcurl4-openssl-dev
```



### Code::Blocks에서 라이브러리 링크

링크 옵션에 다음과 같이 옵션을 준다.

```
-lcurl
```

