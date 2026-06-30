# My Select Shop

Spring Boot와 JPA를 활용하여 관심 상품을 등록하고, 네이버 쇼핑 검색 API를 통해 상품 정보를 조회 및 관리하는 프로젝트입니다.

---

# 프로젝트 소개

My Select Shop은 사용자가 관심 있는 상품을 등록하고 관리할 수 있는 웹 애플리케이션입니다.

네이버 쇼핑 검색 API를 이용하여 상품 정보를 검색하고, 관심 상품을 저장하며, 희망 구매 가격(My Price)을 설정할 수 있습니다. 또한 Spring Security와 JWT를 적용하여 사용자 인증 및 권한 관리를 구현하였습니다.

---

# 기술 스택

* Java 21
* Spring Boot
* Spring Data JPA
* Spring Security
* JWT
* MySQL
* Gradle
* Lombok

---

# 프로젝트 구조

```text
src
 ├── config
 ├── controller
 ├── dto
 ├── entity
 ├── repository
 ├── security
 ├── service
 ├── util
 └── resources
```

---

# 주요 기능

## 회원 관리

* 회원가입
* 로그인
* JWT 기반 인증
* 사용자 권한(Role) 관리

---

## 상품 검색

* 네이버 쇼핑 API 연동
* 상품명 검색
* 검색 결과 조회

---

## 관심 상품 관리

* 관심 상품 등록
* 관심 상품 목록 조회
* 관심 상품 삭제
* 희망 구매 가격(My Price) 설정 및 수정

---

# 학습 내용

* Spring Boot 프로젝트 구성
* REST API 설계
* Spring Security
* JWT 인증
* Spring Data JPA
* 외부 API 연동
* DTO와 Entity 분리
* 계층형 아키텍처(Controller-Service-Repository)

---

# 실행 방법

### 프로젝트 실행

```bash
git clone https://github.com/yonghyun0325/myselectshop.git

cd myselectshop

./gradlew bootRun
```

또는 IntelliJ IDEA에서 실행할 수 있습니다.

---

# 향후 개선 사항

* Refresh Token 적용
* 예외 처리(Global Exception Handler)
* Validation 적용
* Swagger(OpenAPI) 적용
* Docker 배포
* 테스트 코드 작성

---

# 프로젝트 목적

Spring Boot 기반의 쇼핑 관리 서비스를 구현하며 Spring Security, JWT 인증, JPA, 외부 API 연동을 학습하기 위한 프로젝트입니다. 관심 상품 등록 및 희망 구매 가격 관리 기능을 구현하면서 실무에서 자주 사용하는 백엔드 개발 기술을 익히는 것을 목표로 하였습니다.
