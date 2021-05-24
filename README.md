# FINAL PROJECT

### 목적

- 독립영화와 무명배우를 소개하여 독립 영화 활성화

---

- `git switch -c <브랜치 이름>` : 브랜치 생성 후에 이동
- 생성한 브랜치에서 작업하기
- `git add .` -> `git commit -m <commit message>`
- `git push origin <브랜치 이름`
- gitlab에서 merge하기
- `git switch master` : master로 이동하기
- `git pull origin master` : 변경된 상태 받아보기
- `git brach -d <브랜치 이름>`
- `git branch` : 삭제되었는지 확인하기

---

- `python manage.py loaddata articles/movies.json` : movie 테이블에 영화 데이터 넣기

---



### 역할

- 김문희
  - 디자인
  - PPT
  - 프론트 엔드
- 김민환
  - 백엔드

---

### 컴포넌트 구성

- App.vue

  - header(컴포넌트 x)
    - header의 메뉴를 누르면 router로 페이지 이동
  - Main
    - 영화목록 (포스터만 보여주고)
      - 영화 상세페이지 -> 캐러셀
    - 개인 추천 영화
    - 오늘의 배우 -> 일단 랜덤
    - 커뮤니티 페이지 간략히 보여주기
  - **서비스 소개 페이지**
    - 무빈디 소개하기
  - **우리 배우들**
    - 배우검색기능
    - 배우목록 (무한 스크롤)

  - **커뮤니티**
    - 영화리뷰 - 댓글
    - 구인구직
    - 자유게시판[옵션]
  - 프로필
    - 팔로우 팔로워
    - sns ID (인스타, 카카오톡) -> 연락처
    - 프로필정보
    - 필모 -> 클릭하면 영화로 이동
    - 내가 좋아요한 영화
    - 내가 작성한 리뷰
  - 검색결과 페이지 -> 검색했을 때 새로운 페이지로 이동
    - 검색결과가 없습니다 -> 아래의 영화는 어떠세요
    - 검색 성공했을 때 -> 해당 영화 출력 -> 해당 영화와 비슷한 영화 추천

- 로그인-회원가입-로그아웃

  - 새로운 페이지로 이동

---

### 오늘의 목표

- 5월 20일
  - 디자인 완성
  - 모델완성 및  테스트 -> 이미지 오류 안나게하기
  - 메인 컴포넌트 구성
- 5월 21일
  - 메인, 커뮤니티 페이지 완성시키기
  - **로그인, 로그아웃** 완료

---

### 스케줄

- 5/21까지
  - 기본 기능 완성시키기
  - 배치, 색 등 기본적인 css 입히기
  - 로그인 회원가입 로그아웃
- `문희` : 5/23까지 마이페이지 디자인 완료 및 커뮤니티 마이페이지 기능구현하기
- 5/24까지
  - 데이터베이스에 데이터 적재시키기 (영화, 배우 데이터)
- 5/24 상황
  - 메인 페이지 60%, 커뮤니티 70%, 배우 70%
  - 소개 페이지, 프로필 해야함
  - 커뮤니티, 소개 페이지 완성시키기
  - 메인페이지 80%까지 -> 영화목록, 오늘의 배우
  - 영화 상세페이지 만들기
  - 프로필 구조잡기
- 5/25
  - 기능 완성시키기
- 5/26
  - 오류 수정
  - 디자인 수정
  - 바->아이콘이미지 수정
  - 로고 이미지
- 5/27 
  - 발표 연습 및 놀기
