# Market
사용해보고 싶던 기술들을 적용한 중고거래 사이트 토이 프로젝트입니다

# Market
사용해보고 싶던 기술들을 적용한 중고거래 사이트 토이 프로젝트입니다

# 필요 기능

## 회원가입 / 로그인 (일단 oauth로 해놓고, 나중에 JWT)
oauth로 접속해도 필수정보는 가입시 추가로 받을 생각
Spring Security, JWT, JPA

## 마이페이지 기능
내가 등록한 상품, 찜한 상품, 내 정보 수정, 나의 즐겨찾기 할 주소 같은거 넣어주면 될 거 같다

## 권한 관리 (일반 사용자 / 관리자)
Spring Security Role로 사용자, 관리자 나눌 예정 (ROLE_USER, ROLE_ADMIN)
관리자는 모든 글 수정, 삭제, 전체 공지 제공 기능이 추가 됨.

## 상품 등록 / 수정 / 삭제
MultipartFile

## 상품 목록 / 상세 조회
페이징 처리할때 리스트 형식으로 구현..?

## 찜하기 기능 (좋아요)

## 인기 상품 조회
Redis 캐시 (@Cacheable, @CacheEvict), 조회수 기반 정렬

## 채팅 기능 (사용자 간 실시간 채팅)
WebSocket, STOMP, Kafka (메시지 중계), JPA (채팅 저장)

## 알림 기능 (관리자 → 사용자 푸시)
Kafka (알림 이벤트 생성), Redis Pub/Sub, WebSocket (또는 FCM)

## 상품 / 사용자 신고 기능
JPA, 관리자 전용 처리 기능, 이벤트로 Market
사용해보고 싶던 기술들을 적용한 중고거래 사이트 토이 프로젝트입니다

# 필요 기능

## 회원가입 / 로그인 (일단 oauth로 해놓고, 나중에 JWT)
oauth로 접속해도 필수정보는 가입시 추가로 받을 생각
Spring Security, JWT, JPA

## 마이페이지 기능
내가 등록한 상품, 찜한 상품, 내 정보 수정, 나의 즐겨찾기 할 주소 같은거 넣어주면 될 거 같다

## 권한 관리 (일반 사용자 / 관리자)
Spring Security Role로 사용자, 관리자 나눌 예정 (ROLE_USER, ROLE_ADMIN)
관리자는 모든 글 수정, 삭제, 전체 공지 제공 기능이 추가 됨.

## 상품 등록 / 수정 / 삭제
MultipartFile

## 상품 목록 / 상세 조회
페이징 처리할때 리스트 형식으로 구현..?

## 찜하기 기능 (좋아요)

## 인기 상품 조회
Redis 캐시 (@Cacheable, @CacheEvict), 조회수 기반 정렬

## 채팅 기능 (사용자 간 실시간 채팅)
WebSocket, STOMP, Kafka (메시지 중계), JPA (채팅 저장)

## 알림 기능 (관리자 → 사용자 푸시)
Kafka (알림 이벤트 생성), Redis Pub/Sub, WebSocket (또는 FCM)

## 상품 / 사용자 신고 기능

## 키워드 알람받기
스프링 이벤트

관리자 기능

사용자 목록 조회, 신고 관리, 상품 차단/삭제

Spring Security (ROLE_ADMIN 보호된 API)

AOP 적용

공통 로깅, 요청 시간 측정, 예외 공통 처리

Spring AOP, @Aspect, MDC (로그 추적)

에러 핸들링 / 공통 응답 포맷

@ControllerAdvice, ResponseEntity, Custom Error DTO

API 문서화

Springdoc OpenAPI (Swagger 자동 문서화)

테스트

단위 테스트 (JUnit5, Mockito)

통합 테스트 (MockMvc, Embedded Kafka, Testcontainers)

DB 설계 / 연동

PostgreSQL, JPA, ERD 기반 설계

이벤트 기반 비동기 처리

Kafka (채팅, 알림, 신고 처리 비동기 처리)

조회 최적화 및 캐싱

Redis, Spring Cache

로컬 개발환경 구성

Docker, Docker Compose (PostgreSQL, Redis, Kafka 포함)
