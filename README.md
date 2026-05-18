<h1 align="center">진태영 · iOS Developer 👋</h1>

<p align="center">
  기술 지식을 토대로 도메인을 넘나들며 사용자 문제를 측정 가능한 형태로 해결하는 iOS 개발자입니다.
</p>

<br>

## 🧭 About Me

> 개발자의 일은 코드 안에서 끝나지 않는다고 생각합니다.

- **기술 깊이**로 사용자 문제를 해결하고, **다른 팀과의 업무 프로세스를 함께 개선**하며, **비즈니스 협상으로 앱의 사업 성장까지 주도**하는 iOS 개발자입니다.
- 사용자가 명시적으로 보고하지 않은 문제까지 직접 발견·해결하며, 완성도 높은 사용자 경험에 책임을 가집니다.
- 진단·측정·해결안을 *팀 발표·컨벤션·가이드 문서*로 정착시켜 동료와 함께 더 나은 구조를 고민합니다.
- AI를 *단순 코딩 보조*가 아닌 *설계·검토 단계까지 함께 설계하는 파트너*로 다룹니다.

<br>

## 🛠 Tech Stack

**Language**
<p>
  <img src="https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
</p>

**Framework**
<p>
  <img src="https://img.shields.io/badge/SwiftUI-0D0D0D?style=flat&logo=swift&logoColor=blue"/>
  <img src="https://img.shields.io/badge/UIKit-2396F3?style=flat&logo=UIKit&logoColor=white"/>
  <img src="https://img.shields.io/badge/Combine-F05138?style=flat&logo=Swift&logoColor=white"/>
  <img src="https://img.shields.io/badge/RxSwift-B7178C?style=flat&logo=ReactiveX&logoColor=white"/>
  <img src="https://img.shields.io/badge/AVFoundation-000000?style=flat&logo=apple&logoColor=white"/>
  <img src="https://img.shields.io/badge/WebKit-FF6B00?style=flat&logo=webkit&logoColor=white"/>
</p>

**Architecture**
<p>
  <img src="https://img.shields.io/badge/TCA-1F4F8B?style=flat&logo=swift&logoColor=white"/>
  <img src="https://img.shields.io/badge/MVVM-444444?style=flat"/>
  <img src="https://img.shields.io/badge/Clean%20Architecture-444444?style=flat"/>
</p>

**Tools**
<p>
  <img src="https://img.shields.io/badge/Claude%20Code-CC785C?style=flat&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=white"/>
  <img src="https://img.shields.io/badge/Maestro-7C3AED?style=flat&logo=ios&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=Git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/>
</p>

<br>

## 💼 Career

### ㈜피피 (PPFriends) · iOS 개발자 · 2024.01 ~ 현재
반려동물 기반 소셜 커머스 플랫폼 — iOS 단독 개발

**Selected Highlights**

- 🎬 **동영상 편집·업로드 자체 구현** (AVFoundation) — 업로드 시간 **-67%** (5개 영상 1분 30초 → 30초). HDR→SDR 코덱 무관 변환을 위한 자체 `HDRVideoCompositor` 구현
- 🛒 **앱 내 쇼핑 (PG · 헤드리스 커머스) 신규 도입** — PG 협상으로 월별 정산액 **+2,000만원**, WKWebView 하이브리드 결제 모듈 + 헤드리스 REST API 통합으로 신규 매출 채널 확보
- 🏗 **자체 SwiftUI Router 아키텍처 설계** — RouterCoordinator + Router + RootView 3-tier · Signal 패턴 단방향 흐름. iOS 26 NavigationStack onAppear 이슈 해결
- 🔄 **Cross-Screen 데이터 동기화 시스템** — NotificationCenter + Combine 기반 Pub-Sub 패턴 + Protocol 채택만으로 자동 구독되는 구조. 게시글 좋아요·댓글·스크랩 → 목록 자동 반영. Compile-time 타입 안전성 · weak reference · DI 기반 테스트 용이성 확보
- 🔥 **Firebase Crashlytics 사용자 도메인 에러 진단 환경 구축** — Moya `PluginType` 기반 자동 수집 + **41개 민감정보 자동 마스킹**으로 CS 즉시 진단
- ⚡ **SwiftUI 리스트 렌더링 최적화** — Xcode Instruments 측정·진단 후 3단계 리팩토링으로 CPU **-86%**, 13개 화면 일괄 적용 + 사내 컨벤션 정착
- 🤖 **Claude Code 기반 QA 시트 AI 자동변환** — 기획·QA 파트의 만성 병목 해결로 QA 시트 작성 **5일 → 1일** (-80%)
- ⚙️ **Maestro 기반 Release QA 자동화 파이프라인** — iOS·Android 222 Flow + 단일 출처 ID 동기화로 출시 검증 **2일 → 3시간** (-87.5%)
- 🎨 **UIKit Storyboard → SwiftUI 점진적 마이그레이션** (2024.05 ~ 2025.06, 약 1년) — 지분 50% 이상, Alert·Toast 시스템 제외 거의 전 화면 마이그레이션. 코드베이스 SwiftUI 통일성 확보 + 후속 SwiftUI 최적화·Router 아키텍처 작업의 토대
- 🔐 **NICE 본인인증 + SNS Login 통합** (2024.10 ~ 2024.11) — NICE 본인인증 SDK + 카카오·구글·애플·페이스북·네이버 5개 SNS Login 라이브러리 통합 + 회원가입 로직 리뉴얼

<br>

## 📚 Publication

### SwiftUI 상태 관리부터 테스트까지 — iOS 개발자를 위한 TCA 1.0
**공동저자 7인** · 사도출판 · 2023.11.07 · ISBN 9791188786855

국내 최초 The Composable Architecture(TCA) 가이드라인 집필서.
TCA의 핵심 개념부터 상태 관리·바인딩·비즈니스 로직 구조화·Navigation·Dependency 등 SwiftUI 연동 방법에 대한 상세 설명 작성.

📖 [RIDIBOOKS](https://ridibooks.com/books/2773000087)

<br>

## 🚀 Personal Project

### 📱 Memorizing — App Store 출시
에빙하우스 망각곡선 기반 반복 학습 암기장 플랫폼

- **역할**: iOS 개발 (팀) · **기간**: 2023.01 ~ 2023.02 (7주)
- **기술**: Store MVVM Singleton Architecture · Firebase · Notification · Core Data · async/await · Social SignIn
- 🔗 [App Store](https://apps.apple.com/kr/app/메모라이징-memorizing/id1670026920) · [README](https://github.com/elisha0103/finalproject-memorizing)

<br>

## 🎓 Education

**멋쟁이사자처럼 · 앱스쿨 1기** (Swift 문법·iOS 생태계·애자일 개발 방법론)
- Swift 문법 및 iOS 생태계를 이해하고 비즈니스 로직 구현 학습
- 애자일 개발 방법론 적용 + 팀 단위 성장 주도 (팀 피드백·코드 리뷰·주기적 회고·토론 스터디)
- 진행: 프로토타입 → MVP → 해커톤 → **앱스토어 배포 프로젝트(Memorizing)**

<br>

## 📫 Contact

- **Email**: elisha01039@gmail.com
- **Blog**: [elisha0103.tistory.com](https://elisha0103.tistory.com)

<br>

---
