---
layout: single
title:  "리액트로 크롬 익스텐션 만들기 - Prologue"
---

# 3월의 프로젝트 - 1

  3월 한달간 진행할 프로젝트는 바로 **엽이네 집** 나만의 크롬 확장 프로그램 만들기이다.

  만들게 된 계기는 이번에 네이버 **실시간 검색어**가 사라져서 네이버를 주 홈페이지로 딱히 할 필요가 없어져서 만들기로 결정했다. 막상 아예 안쓰자니 그건 좀 그렇고 필요한 기능들만 쏙쏙 빼와서 나만의 홈 화면을 만드는 걸 목표로 하고있다.



### 기능

* 날씨, 시간
* 오늘의 운세
* 메모장
* 사용자 선택 가능한 검색 기능
* 유튜브 급상승 동영상 리스트
* 내가 관심 있는 주식 차트 현황
* 실시간 이슈

### 추후 추가 예정

- 네이버 자주 가는 카페
- 메일(구글, 네이버)  확인할 수 있게 하기



개발에 앞서 구현을 1차와 2차로 나누었는데 1차에서는 고정적인 사용자 정보를 가지고 외부에서 가져오는 방식으로 진행하고

> ex) 날씨 위치, 오늘의 운세 사용자 정보, 주식 차트 값 **고정**

2차에서는 홈페이지의 사용자가 값을 입력해서 원하는 정보를 가져올 수 있게끔 수정할 예정

> ex) 홈페이지에서 위의 정보들을 사용자가 입력 및 저장



React를 이용해서 구현할 생각이다. 



**1달이면 충분하겠지????????**

