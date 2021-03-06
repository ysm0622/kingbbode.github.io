---
layout:     post
title:      Fast-Campus Java Web Programming Camp 5일차
author:     kingbbode
tags:       spring
subtitle:   강의 정리
category:  study
outlink: 0
---

다섯번째 강의
===========

배운 것
-------

### GIT

-	자동으로 생성(Build 혹은 IDE 설정으로 생성되는)되는 파일들은 굳이 버전 관리 시스템에서 관리할 필요가 없다

	-	ex) .mvn, .git, target 등
	-	.gitignore를 통해 제외시킬 수 있다
	-	[제공해주는 사이트](gitignore.io)가 있다

-	git remote -v : 원격 저장소 확인

-	git remote set-url origin : URL 변경

### JPA

쿼리 작성을 추상화하여 메서드로 제공

-	쿼리에 투자하는 비용을 개발에 쓸 수 있음
-	쿼리를 모른 상태로 사용하고 개발에 몰두하고, 나중에 쿼리를 알아가는 식으로 접근하는 학습 방법을 추천(기존 방식과 반대)

학습비용이 많이 들지만, 쿼리 작업에 너무 많은 시간을 쏟는 것보다 **개발에 몰두할 수 있는 ORM을 사용하는 것을 추천**

-	95% 이상 ORM으로 처리 가능하다.
-	일부 복잡한 쿼리는 ORM의 기능 중 SQL을 사용할 수 있는 기능을 사용하여 처리 가능하다.

Dialect : 각각 다른 데이터베이스의 특화, 고유된 설정을 지원할 수 있다.

**모든 Model의 연관 관계를 맺어줄 필요없다.** 연관 관계를 정의하고 잘 끊는 것이 중요하다!

### Controller

`Spring`의 `Server Side Template`은 `Controller`의 `Scope`에 속한다.
