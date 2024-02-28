
# NAROU 🧳
다른 사람들의 여행 경로를 한눈에 비교하고 싶나요? 🙋‍♀️
<br> 
나만의 여행을 위한 효율적인 루트를 계획하고 실시간으로 공유 해 보세요! ✈

## 목차
1. [프로젝트 기간](#1-프로젝트-기간)
2. [사용한 기술 스택](#2-사용한-기술-스택)
3. [팀원 소개](#3-팀원-소개)
4. [폴더 구조](#4-폴더-구조)
5. [설계](#5-설계)
6. [주요 기능 설명](#6-주요-기능-설명)
7. [서비스 화면](#7-서비스-화면)

----
### 1. 프로젝트 기간
  - 2024.01.06 ~ 2024.02.16

### 2. 사용한 기술 스택
  * React
  * node.js
  * zustand
  * styled-component
  * axios
  * mui material

### 3. 팀원 소개
  * 이우주
    - git 관리
    - 회원 관련 기능
    - 검색 및 필터

  * 이금현
    - 게시글, 코멘트 CRUD
    - 사진 Cropper
    - UI/UX

  * 나유경
    - 지도 API 관련 로직
    - 비교 페이지
    - 게시물 무한 스크롤 구현

### 4. 폴더 구조
```
  .
  ├── node_modules
  ├── public
  └── src
      ├── assets
          └── image
      ├── components
      ├── pages
      ├── router
      └── store
```

### 5. 설계

  - Figma
  <br>
  <img src="src/img/figma.png" width="700px" />
  <br>

  - FlowChart
  <br>
  <img src="src/img/flowchart.png" width="700px"/>
  <br>

### 6. 주요 기능 설명

  - 회원 관리
    - 멤버 회원가입/탈퇴, 중복 아이디 체크, 토큰 활용 인증, 인증코드 확인
    - 유저 닉네임 및 소개 조회/수정, 프로필 사진 등록/수정, 팔로우/팔로잉, 팔로우/팔로잉 목록 확인
    - 스크랩한 게시글 조회

  - 게시글 검색 및 필터 기능
    - 작성자, 제목으로 게시글 검색
    - 최신순, 인기순으로 게시글 정렬
    - 필터 조건을 설정하여 필터 검색
    - 사진 모드와 경로 모드로 게시글 조회
    - 무한스크롤

  - 게시글
    - 좋아요, 스크랩, 댓글
    - 태그 지정, 태그 기반 검색
    - 피드별 장소, 사진 등록(등록 시 Cropper로 줌 인/아웃 가능)
    - 피드 기반 경로 보여주기
    - 썸네일 등록

  - 비교
    - 두 게시글을 가져와 맵 상에서 경로 비교
    - 경로의 상세 정보 확인


### 7. 서비스 화면
  <table>
    <tr>
      <td>
        <p>메인페이지</p>
      </td>
    </tr>
    <tr>
      <td>
        <img src="src/img/main.gif" width="100%" />
      </td>
    </tr>
    <tr>
      <td>
        <p>무한스크롤</p>
      </td>
    </tr>
    <tr>
      <td>
        <img src="src/img/infinite_scroll.gif" width="100%" />
      </td>
    </tr>
    <tr>
      <td>
        <p>검색</p>
      </td>
    </tr>
    <tr>
      <td>
        <img src="src/img/search.gif" width="100%" />
      </td>
    </tr>
    <tr>
      <td>
        <p>게시글 작성</p>
      </td>
    </tr>
    <tr>
      <td>
        <img src="src/img/create.gif" width="100%" />
      </td>
    </tr>
    <tr>
      <td>
        <p>프로필</p>
      </td>
    </tr>
    <tr>
      <td>
        <img src="src/img/profile.gif" width="100%" />
      </td>
    </tr>
    <tr>
      <td>
        <p>스크랩</p>
      </td>
    </tr>
    <tr>
      <td>
        <img src="src/img/scrap.gif" width="100%" />
      </td>
    </tr>
    <tr>
      <td>
        <p>비교</p>
      </td>
    </tr>
    <tr>
      <td>
        <img src="src/img/compare.gif" width="100%" />
      </td>
    </tr>
  </table>

