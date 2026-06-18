# 👋 Backend Developer 우서윤

안녕하세요.  
끊임없이 성장하고 싶은 백엔드 개발자 **우서윤**입니다.

Spring Boot 기반의 백엔드 개발을 중심으로  
성능 개선과 안정적인 서비스 설계에 관심을 가지고 있습니다.

# Contact

- GitHub : [wooarling](https://github.com/wooarling)
- Blog : [Velog](https://velog.io/@wooarling/posts)


# 🏆 Awards
-🥉 2025 교내 해커톤 장려상

# 📑 Projects

## 📚 [UEIC](https://github.com/2026-team3/ueic-backend.git)

> 토익 맞춤형 스터디 매칭 플랫폼

### 📅 개발 기간
2026.03 ~ 2026.04

### 💡 프로젝트 소개
사용자의 취약 분야를 분석하고 학습 성향을 기반으로  
적합한 스터디원을 추천해주는 토익 스터디 매칭 플랫폼입니다.

자체 테스트를 통해 사용자의 약점을 파악하고,  
해시태그 기반 학습 스타일 분석을 통해 비슷한 성향의 사용자를 추천하도록 구현했습니다.

### 👨‍💻 담당 기능
- 취약 분야 테스트 기능 구현
- DB 기반 랜덤 문제 출제 로직 개발
- Rule-Based 기반 카테고리 1차 필터링 구현
- Jaccard Similarity 기반 사용자 매칭 정렬 구현

### 🛠 기술 스택
`Java` `Spring Boot` `MySQL` `Docker` 

##📚 [CONEXT](https://github.com/wooarling/hackerton-dswu.git)
> IT 직무 적성 테스트와 커뮤니티 기능을 결합한 플랫폼

### 📅 개발 기간
2025.11~ (2주 동안 진행)

### 💡 프로젝트 소개
사용자의 적성을 분석하여 적합한 IT 분야를 추천하고 직무별 게시판을 통해 
정보 공유가 가능하도록 구현한 팀 프로젝트입니다.

### 👨‍💻 담당 기능
-JWT + Session 기반 사용자 인증 및 권한 처리 구현
-게시글 CRUD API 및 댓글 기능 개발
-좋아요 / 스크랩 기능 구현
-익명 게시글 작성 기능 구현
-사용자 활동 조회 API (내 글 / 내 댓글 / 내 스크랩) 개발

### 🛠 기술 스택
'Python' 'Django' 'Django REST Framework' 'SQLite'

## 📦 [공공데이터 기반 아동복지급식정보 수집 프로젝트](https://github.com/wooarling/wealth.git)

> 공공데이터 API를 활용한 대용량 데이터 수집 및 성능 개선 개인 프로젝트

### 📅 개발 기간
2025.12 ~ 2026.01

### 💡 프로젝트 소개
공공데이터포털 API를 활용하여 약 27만 건 이상의 아동복지급식정보 데이터를 수집하고  
DB에 적재하는 개인 프로젝트입니다.

초기에는 단순 적재 방식으로 구현했으나, 대용량 데이터 처리 성능 개선을 위해  
Thread Pool 기반 병렬 처리 구조로 리팩토링하였습니다.

### ⚙️ 담당 및 개선 내용
- CommandLineRunner 기반 초기 데이터 적재 구현
- ExecutorService(Thread Pool) 기반 병렬 처리 구조 개선
- MAX_THREADS = 5 설정으로 페이지 단위 동시 처리
- JSON 파싱 및 DB 저장 로직 분리
- uniqueKey 기반 중복 데이터 방지

### 🛠 기술 스택
`Java` `Spring Boot` `MySQL`
