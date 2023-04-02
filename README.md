# 할일

- [x] 회원가입 폼
-   - [ ] 로그인 상태에서 들어올 수 없다.
    - [x] 폼이 있어야 한다.
    - [x] input[name="username"] 필드가 있어야 한다.
    - [x] input[name="password"] 필드가 있어야 한다.
    - [x] 폼 체크
- [ ] 회원가입 폼 처리
  - [ ] 로그인 상태에서 들어올 수 없다.
  - [x] 유효성 체크를 해야 한다.
  - [x] member 테이블에 회원이 저장되어야 한다.
  - [x] 처리 후에 / 로 이동해야 한다. 302
- [ ] 로그인 폼
  - [ ] 로그인 상태에서 들어올 수 없다.
  - [x] 폼이 있어야 한다.
  - [x] input[name="username"] 필드가 있어야 한다.
  - [x] input[name="password"] 필드가 있어야 한다.
  - [x] 폼 체크
- [ ] 로그인 폼 처리(스프링 시큐리티가 알아서 해줌)
  - [ ] 세션에 데이터가 들어있는지 확인
<hr>
# gramgram

## 서비스 개요
- 서비스명 : 그램그램
- 도메인 : gramgram.ai
- 인스타ID 기반 익명호감표시 서비스
- 인스타ID 기반 인기투표 서비스
- 본인의 인스타ID를 입력하면, 현재 자신에게 이성적으로 호감을 느끼고 있는 사람이 몇명인지 알 수 있다.

## 기술
- 스프링부트
- 스프링 시큐리티
- 스프링 OAUTH 2
- 스프링 DATA JPA
- MySQL
- 타임리프
- 테일윈드
- 데이지 UI
- 제이쿼리
- 지마켓 산스폰트
- 인스타그램 API
- TDD

## 배포
- 네이버 클라우드 플랫폼
- 도커
- NGINX
- 젠킨스
- GITHUB HOOKS
- CI/CD

## 기능
- 카카오 로그인
- 본인의 인스타ID 연동
	- 처음에는 수동입력
    - 추후에는 인스타API로 인증
    - 본인의 성별 입력
- 본인이 호감을 가지고 있는 상대를 등록
	- 5명까지 등록가능
    - 상대방의 인스타ID를 등록
		- 인스타ID 입력할 때 매력포인트 중 하나를 선택(외모, 성격, 능력)
- 본인의 인기를 확인
	- 나를 좋아하는 사람의 수 확인
    - 나를 좋아하는 여자의 수 확인
    - 나를 좋아하는 남자의 수 확인
    - 나를 외모 때문에 좋아하는 사람의 수
    - 나를 외모 때문에 좋아하는 여자의 수
    - 나를 외모 때문에 좋아하는 남자의 수
    - 나를 성격 때문에 좋아하는 사람의 수
    - 나를 성격 때문에 좋아하는 여자의 수
    - 나를 성격 때문에 좋아하는 남자의 수
    - 나를 능력 때문에 좋아하는 사람의 수
    - 나를 능력 때문에 좋아하는 여자의 수
    - 나를 능력 때문에 좋아하는 남자의 수
- 본인 인기의 변동내역
	- 시간별
    - 일별
    - 월별
