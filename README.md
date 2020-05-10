# 프로젝트 소개
야구 게임 어플리케이션 개발 프로젝트

# 서비스 이미지

<details markdown="1">
<summary> 메인, 상세페이지, Github OAuth </summary>

## 메인페이지
![메인페이지](https://github.com/codesquad-member-2020/sidedish-04/blob/develop/BE/serviceImages/1.png)

## 상세페이지
![상세페이지](https://github.com/codesquad-member-2020/sidedish-04/blob/develop/BE/serviceImages/%EC%83%81%EC%84%B8%ED%8E%98%EC%9D%B4%EC%A7%80.png)

## OAuth 로그인
![로그인](https://github.com/codesquad-member-2020/sidedish-04/blob/develop/BE/serviceImages/%EB%A1%9C%EA%B7%B8%EC%9D%B8%20%EB%B2%84%ED%8A%BC%20%ED%81%B4%EB%A6%AD%20%EC%8B%9C%20github%20OAuth.png)

</details>

# 프로젝트 속 나의 역할 
- 백엔드 개발자 : DB 설계, 배포 서버 운영, API 개발 

# 개발환경 [참고](https://www.slideshare.net/hyeonjaeCheon/ss-122972422)해서 수정하기.
- API 개발 : 스프링 프레임워크
- API 배포 : AWS EC2, Nginx
- 로그인 인증 : GitHub OAuth
- 데이터베이스 : AWS RDS, Mysql, Spring Data JDBC

# 설계 구조 
- ERD 사진 첨부 후 설명하기. 

# 구현 기능
## 4.1 Github OAuth를 이용한 로그인 기능 구현
### 4.1.1 OAuth 사용 이유 
- 회원 정보 DB를 직접 운영하지 않고도 로그인 기능을 구현하기 위함. 
### 4.1.2 어떻게 
- [GitHub 공식 가이드](https://developer.github.com/apps/building-oauth-apps/authorizing-oauth-apps/) 참고하며 구현. 

## Spring Jdbc Template 활용한 CRUD 구현 
### Jdbc Template 사용 이유 
- CrudRepositoy 제외하고 DB 쿼리를 직접 작성해서 Crud를 구현하고 싶은 욕구 
### 어떻게 
- 

# 어려움과 해결책
## 5.1 어려움 : 사용자 동시 접속 구현 
- 문제 : 혼자하는 야구게임이 아니라 사용자 2명이 진행하는 게임을 구현하는 방법
- 해결책 :  

### 5.2 어려움 : DB 테이블 설계  
- 문제 : 야구 게임에 필요한 테이블 설계에 어려움을 겪음. 
- 해결책 : 
 - '데이터 베이스 첫걸음'이라는 책을 통해 테이블 설계에 대한 지식을 얻고 테이블을 하나의 개념으로 바라보며 설계 시작.
 - "이 테이블(개념)이 가지는 속성이 무엇일까?" 라고 질문하면서 테이블 설계하기.
 - 테이블 설계 -> 실제 서비스 로직 생각 -> 테이블 수정. 이 과정으로 진행하기! 

## 프로젝트 피드백
 

## Api 문서 
[Api 문서](https://github.com/codesquad-member-2020/baseball-10/wiki/API-%EB%AC%B8%EC%84%9C)
