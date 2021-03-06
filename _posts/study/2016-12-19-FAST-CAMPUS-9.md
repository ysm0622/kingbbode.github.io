---
layout:     post
title:      Fast-Campus Java Web Programming Camp 9일차
author:     kingbbode
tags:       spring
subtitle:   강의 정리
category:  study
outlink: 0
---

아홉번째 강의
=============

객체 지향 관련 이야기
---------------------

### 객체 지향 프로그래밍에 익숙해 지려면 어떻게 해야 하나요?

-	요구사항이 명확한 프로그래밍
-	약간은 복잡한 로직이 있는 프로그래밍
-	DB 연동이 없도록 연습
-	특별히 UI에 대한 고려는 하지 않도록 연습
-	웹 프로그래밍은 객체지향을 연습하기 위한 좋은 시작은 아니다.

### 객체 지향 연습을 위한 좋은 예

-	이번 실습과 같은 HTTP 웹 서버
-	프레임워크 또는 라이브러리 구현해 보기
-	볼링 게임 점수판(단, UI는 콘솔)
-	체스 게임(단, UI는 콘솔)
-	지뢰 찾기 게임(단, UI는 콘솔)

### 내가 생각하는 가장 좋은 연습 방법

-	서로 코드 리뷰해 줄 스터디 그룹(2, 3명이도 충분)을 만든다.
-	앞의 추천 애플리케이션 중의 하나를 각자 구현하고, 상호 코드 리뷰한다.
	-	테스트 코드를 만든다. 테스트하기 쉬운 코드를 구현하기 위해 노력한다.
-	다른 사람의 코드에서 힌트를 얻거나, 피드백 받은 내용을 리팩토링한다.
-	상호 코드 리뷰 => 리팩토링 과정 반복한다.
-	몇 개월이 지난 후 똑같은 애플리케이션을 다시 한번 구현한다.

### 객체 지향 프로그래밍을 위한 좀 더 구체적인 실천 방법(객체 지향 생활 체조)

-	규칙 1: 한 메서드에 오직 한 단계의 들여쓰기만 한다.
-	규칙 2: else 예약어를 쓰지 않는다.
-	규칙 3: 모든 원시값과 문자열을 포장한다.
-	규칙 4: 한 줄에 점을 하나만 찍는다.
-	규칙 5: 줄여쓰지 않는다(축약 금지).
-	규칙 6: 모든 엔티티를 작게 유지한다.
-	규칙 7: 2개 이상의 인스턴스 변수를 가진 클래스를 쓰지 않는다.
-	규칙 8: 일급 콜렉션을 쓴다.
-	규칙 9: 게터/세터/프로퍼티를 쓰지 않는다.
-	참고 URL : https://developerfarm.wordpress.com/2012/02/03/object_calisthenics_summary/

배운 것
-------

### Request, Response

### 세션과 쿠키

-	세션과 쿠키는 같은 방식으로 동작한다.

### 네트워크 학습 방법

### 객체 분리 설계

### TDD 중요성

### System.out.println 절대 쓰지말자

-	성능 낭비
-	제거가 힘듬
-	디버깅을 위해 코드를 주석처리?

**Logging 라이브러리 사용하자**

### Servlet 구조를 이해하자

### Servlet 기본 디렉토리를 이해하자

- WEB-INF 중요
