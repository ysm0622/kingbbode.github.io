---
layout:     post
title:      Fast-Campus Java Web Programming Camp 1일차
author:     kingbbode
tags:       spring
subtitle:   강의 정리
category:  study
outlink: 0
---

*스프링 프레임워크를 사용하면서도 스프링이 어떻게 동작하는 것일까, 무엇을 기반으로 어떻게 동작하는가? 하는 생각을 많이하였다. 그래서 큰맘 먹고 선배 개발자가 적극 추천한 박재성 교수님의 자바 웹 프로그래밍 2기를 거금을 투자하여 수강하기로 하였다.<br>거금이 들어간 만큼 열심히, 성실히 배워서 목적을 이루고 수업을 마쳤으면 좋겠다.*

---

첫번째 강의
===========

### 시작의 말

-	지식 공유는 나를 위한 것!
	-	커뮤니티에서 Q&A부터 시작하여 지식을 공유하면서 성장하자!
-	강사는 요구사항과 힌트를 제시, 수강자가 문제를 해결하는 방식으로 수업을 진행!(실습이 많다!)
-	수강생은 강사가 무엇을 주기를 기대하지 말고 스스로 생각하고 깨닫기 위해 노력해야 한다!
-	의식적인 연습 중요!
	-	현재보다 높은 난이도로 도전
	-	변화하는 반복
	-	피드백-개선을 반복

<br>

한 내용
-------

### Git 기본 Command

```
git init
git remote add origin 'git 주소'
gst -> alias 'git status'
git add .
git commit -m '메세지'
git push
git pull
```

-	init : 여기가 깃 저장소다 선언!
-	remote : 원격 저장소 지정
	-	-v : 원격 주소
-	gst : 현재 로컬과 원격 저장소의 변경내역을 확인 가능!
-	add : commit할 내용을 지정!
	-	뒤에 옵션으로 파일명
	-	.은 전체 파일
-	commit : 로컬 저장소에 저장
-	push : 로컬 저장소 내용을 원격 저장소로 저장
-	pull : 원격 저장소 변경 내역을 로컬 저장소로 가져온다.

### Maven 빌드

```
./mvwn clean package
```

-	clean : 기존 빌드 내용 삭제
-	package : 빌드

### 배포

```
java -jar jar이름.jar &
```

-	& : BackGround 실행 옵션

수업 후 느낀 점
---------------

### Git

-	콘솔 커멘드로 직접 쳐보니 헷갈려서 충격!
	-	commit
	-	push
	-	remote add
	-	pull

### Linux

-	apt-get, yum 등을 사용하지 않고 수동 설치해보니 헷갈려서 충격!

<br>*전체적으로 Console을 통해 직접 해보는 것이 어려움. 툴에 의존하지말고 Command 익숙해지는게 중요할 듯.<br>툴도 좋지만 기본을 알고 쓰자!*
