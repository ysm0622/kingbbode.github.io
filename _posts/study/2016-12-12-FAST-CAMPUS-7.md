---
layout:     post
title:      Fast-Campus Java Web Programming Camp 7일차
author:     kingbbode
tags:       spring
subtitle:   강의 정리
category:  study
outlink: 0
---

일곱번째 강의
==============

학생들의 질문
-------------

### 질문하는 방법

-	내가 이해한 내용으로 용어를 정리하는 것이 중요
-	문제의 원인을 찾는 방법은 지속적인 경험과 연습이다

### 프로그래밍 학습 추천 방법

-	개인별 프로젝트를 진행하는 것
-	직접 만들어보는 것이 좋다

배운 것
-------

### 알아야 할 것

스프링의 내부 동작 원리를 알기 위해 알아야 할 것!

-	HTTP
-	Servlet
	-	기본 API 사용법
	-	Servlet Filter
-	Spring MVC
-	Spring DI

웹 프로그래밍을 잘하려면,, **JAVA** 를 잘해야 한다!

### TDD

사람이 직접하는 테스트는 정교한 테스를 하기 힘들다

-	반복 작업
-	서버 실행 필요
-	UI가 필요

**JUnit 사용**

-	테스트명을 한글로라도 작성하여, 테스트가 어떤 테스트인지 알 수 있도록 하는 것이 좋다

-	프로덕트 패키지와 별게의 패키지로 생성되며, 빌드에 포함되지 않기 때문에 프로덕트에 영향 없다

-	`@Before`, `@After` 어노테이션으로 전처리, 후처리가 가능하다

	-	테스트는 테스트 간 영향을 받으면 안되므로, 전치리, 후처리는 각 테스트마다 실행된다

**리펙토링**

-	TDD를 통해 비지니스 로직의 리펙토링이 훨씬 수월해질 수 있다.
-	지속적이고 끊이없이 리펙토링을 시도해야한다.
-	시작부터 성능을 고려하는 것보다 작업을 쪼갠 후 성능을 고려하여 합치는 작업이 더 수월하다.
-	TDD를 통해 디버거 사용을 줄일 수 있다
-	메서드가 한가지 일만 하도록 해야한다.

[예제](https://github.com/kingbbode/tdd-jwp) (.gitignore 나중에 추가해서 다 들어감..)