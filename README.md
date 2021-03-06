# Project <kakao_chatbot_ysUniv>

## Project : incomplete / Service : Stop / Server : AWS(Amazon Web Server) ##

## 기능 설명
1. 연성대학교 정보제공(장학금, 현장학습 등)
2. 연성대학교 위치의 날씨 정보 서비스.
3. 연성대학교에서 가까운 안양역의 상행선, 하행선 서비스.

## 사용 방법
1. 카카오 플러스 친구 '연성대 도우미 봇' 검색 <br>
2. 플러스 친구 추가 및 사용

## 프로젝트 내용
카카오톡의 플러스친구 기능을 이용한, 연성대학교 도우미 챗봇 개발.
카카오톡으로 쉬운 접근법 및 학생들의 편리를 위해 개발.

## 개발 인원
1인 (박진호)

## 개발 환경
Server : Amazon AWS(Seoul Server), Ubuntu Server 16.04 LTS (HVM) SSD Volume Type, pm2 <br>
IDE : Putty , Brackets <br>
Language : Node.js v8.11.4 , npm v5.6.0 <br>

## 개발 일정
2018/07/05 ~

## 개발 NOTE
### 코드 관리 <br>
노트북 코드 입력  Github 업로드  AWS(putty)에서 clone <br>

### 기능추가 예정
1. 연성대학교 학식 (학교 홈페이지의 node.js 크롤링이 안됨)

### 문제점 
1. 전철 서비스 서버의 불안정으로 조회 불안정. <br>
2. 날씨 시간(정각 ± 30 이내) 에러 ( 날씨 예보) <br>
3. 날씨 데이터 트래픽 초과시 서버 중단 발생. <br>

p.s aws의 무료 프론티어 -> 트래픽 초과 시 문제 발생(유료 변환) <br>

1. 날씨관련 00시 00분 전 후 사이 에러 발생<br>
![23](https://user-images.githubusercontent.com/24603994/47338003-3c1f6700-d6d1-11e8-98fb-770cd7fcfc04.PNG)



### 일지
2018.07.05 : 프로젝트 시작, 카카오플러스 연동 작업 <br>
2018.07.09 : github 연동 및 기능 구현, 오타 수정 <br>
2018.07.13 : 연성대학교 날씨 기능 추가 <br>
2018.07.17 : 안양역 상행/하행 시간 추가 <br>
2018.08.21 : 서버 재시작<br>
2018.10.22 : 서버 중단, 서비스 중단.
