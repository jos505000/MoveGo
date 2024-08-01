# 이사 커뮤니티 게시판
---

이사하기 위한 사람들이 모여 이사에 관한 다양한 이야기를 자유롭게 나눌 수 있는 게시판 서비스입니다.

## 사용 기술 스택
---
SpringBoot<br/>
Java<br/>
MySQL<br/>
JPA<br/>
Git<br/>

## 프로젝트 기능 및 설계
---
- 회원가입 기능 
  - 사용자는 회원가입 시 USER 권한(일반 권한)을 가진다.
  - 회원가입 시 아이디와 패스워드를 입력받으며, 아이디는 unique 해야한다.
  <br/>
 
- 로그인 기능
  - 로그인 시 회원가입 때 사용한 아이디와 패스워드가 일치해야 한다.
    <br/>
  
- 게시글 작성 기능
  - 로그인한 사용자는 게시글을 작성할 수 있다.
  - 사용자는 게시글 제목(텍스트), 게시글 내용(텍스트)을 작성할 수 있다.
    <br/>
- 게시글 편집 기능

  - 로그인한 사용자는 자신이 작성한 게시글을 편집할 수 있다.
  - 수정과 삭제가 가능하다.
  <br/>
- 게시글 목록 조회 기능

  - 모든 사용자는 게시글 목록을 조회할 수 있다.
  - 게시글은 최신순으로 기본 정렬된다.
  <br/>
- 특정 게시글 조회 기능

  - 모든 사용자는 특정 게시글을 조회할 수 있다.
  - 게시글 제목, 게시글 내용, 작성자 카테고리 중 하나를 선택하여 해당 카테고리에 원하는 정보를 입력해 게시글 조회가 가능하다.
  <br/>
- 댓글 작성 기능

  - 로그인한 사용자는 게시글에 댓글을 작성할 수 있다.
  - 사용자는 댓글 내용(텍스트)을 작성할 수 있다.
  <br/>
- 댓글 편집 기능

  - 로그인한 사용자는 자신이 작성한 댓글을 편집할 수 있다.
  - 수정과 삭제가 가능하다.
  <br/>
- 관리자 기능

  - 관리자는 MASTER 권한(관리자 권한)을 가진다.
  - 모든 게시글과 댓글의 삭제가 가능하다.
  
## ERD
  --- 

  <img width="939" alt="스크린샷 2024-08-01 오후 4 10 23" src="https://github.com/user-attachments/assets/383f84f4-267e-44ce-bc4a-4a6e0369ed4a">


  


  
  
