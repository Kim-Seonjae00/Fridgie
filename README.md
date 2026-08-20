# Fridgie

Fridgie는 냉장고 속 식재료를 관리하고, 사용자가 보유한 재료를 기반으로 만들 수 있는 레시피를 추천받을 수 있도록 기획한 냉장고 기반 레시피 앱입니다.

현재는 프로젝트 기획과 개발환경 세팅을 진행한 단계입니다.

## 프로젝트 소개

많은 사람들이 냉장고에 어떤 재료가 있는지 정확히 기억하지 못하거나, 가지고 있는 재료를 어떻게 활용해야 할지 고민하는 경우가 많습니다.

Fridgie는 이러한 문제를 해결하기 위해 사용자의 냉장고 속 재료를 기준으로 식재료 관리와 레시피 추천을 연결하는 서비스를 목표로 합니다.

향후에는 영수증 OCR을 통한 재료 등록, 요리 기록 공유, 사용자 간 식재료 공유 기능까지 확장할 계획입니다.

## 주요 기능

- 냉장고 식재료 등록 및 관리
- 보유 재료 기반 레시피 추천
- 영수증 OCR을 통한 식재료 자동 등록
- 요리 기록 및 레시피 커뮤니티
- 사용자 간 식재료 공유 및 채팅

## 기술 스택

### Frontend

- Flutter
- Dart
- Material 3
- HTTP Client
- Secure Storage

### Backend

- Java 21
- Spring Boot 3
- Spring Web
- Spring Data JPA
- Spring Security
- MySQL
- JWT

## 프로젝트 구조

```text
Fridgie
├── backend      # Spring Boot 기반 API 서버
├── frontend     # Flutter 기반 모바일 앱
└── docs         # 기획 및 설계 문서
