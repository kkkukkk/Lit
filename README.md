# Lit
Challenge Based SNS
 
 **Services**
 - Lits (챌린지)
 - Lit up (챌린지 인증)
 - Chatting
 - Follow/Following
 - Adminstration

 ## Tech stack & Open-source libraries
 ### DBMS
 * Oracle
### Front-end
 *  HTML/CSS
 *  JavaScript
 *  Jquery
 *  Thymeleaf
 *  Ajax
### Back-end
 * Spring-Boot
 * Maven
 * myBatis
 * Java
 * WebSocket
 * Hikari CP
 
## Environment  
  *  tomcat
  *  IntelliJ
  *  DBeaver
  *  jdk 11
  *  STS
  
----
**내가 구현한 기능**
### Front-end
** 인증 글 작성 publishing (Modal)
- 이미지 드래그&드롭 업로드
- 이미지 직접 업로드
- 이미지, 썸네일 미리보기
- 이미지 슬라이드
- 이미지 업로드 삭제
- 이미지 유효성 검사
- 챌린지 선택 유효성 검사  

** 인증 글 상세 publishing (Modal)
- 이미지 슬라이드
- 댓글 무한 스크롤

** 신고하기 publishing (Modal)
- 버튼으로 구분하여 신고 내용 클릭 시 바로 동작

### Back-end
** WebSocket 기반 채팅
- RoomId로 채팅 방을 구분하여 채팅
- RoomId로 채팅 내역 불러오기
- Ajax 활용 비동기 채팅 방 별 채팅 내역 불러오기
- WebSocket Message 활용 실시간 채팅 미리보기
- 자신과 채팅 상대 구분하여 메세지 띄우기 
- 채팅 상대 프로필 사진 표시

** 팔로워 / 팔로잉 목록 및 검색
- 팔로잉 목록 및 닉네임, 프로필 사진 띄우기
- 팔로워 목록 검색 및 닉네임, 프로필 사진 띄우기

# Images

* 팔로워/팔로잉 목록 및 검색 및 프로필 사진 표시  
![image](https://user-images.githubusercontent.com/93972072/178234598-8bdfde74-2cea-4326-8fc2-b0b8083d559c.png)


* 채팅  
![image](https://user-images.githubusercontent.com/93972072/178234991-f0f3bbd2-ea59-4f61-ae2f-092055060927.png)


**성과**
----
* Spring-Boot 기반 프로젝트 완성
* WebSocket 기반 단일 페이지 REST 방식의 채팅 구현
