# La Poem - 시적인 독서 체험을 위한 도서 커뮤니티 플랫폼

**La Poem**은 대화형 챗봇과 독서 토론, 커뮤니티 기능이 결합된 웹 기반 도서 커뮤니티 플랫폼입니다.  
사용자는 다양한 사람들과 책과 관련된 의견을 자유롭게 나눌 수 있으며, 챗봇 '스텔라(Stella)'를 통해 인공지능과의  
독서 토론도 경험할 수 있습니다.


> 본 프로젝트는 프론트엔드, 백엔드, 챗봇 서버로 분리하여 3개의 레포지토리로 구성되었습니다.

**Repository**
- [Frontend Repository] https://github.com/ju22hy/proj_lapoem_front
- [Backend Repository] https://github.com/ju22hy/proj_lapoem_back
- [Chatbot Repository] https://github.com/ju22hy/proj_lapoem_chatbot

**Notion**
- https://plausible-timimus-25c.notion.site/RPA_-1ce01307430b8186b1b3de8a9ccc1359

**Figma**
- https://www.figma.com/design/ojCd1Ylhu1SMN1M5jISATy/AICC_2nd_Lapoeme?node-id=0-1&t=3tWxu1O6znbWbvNB-1

---

## 🛠 기술 스택

| 기술 | 설명 |
|------|------|
| **React** | 컴포넌트 기반 UI 구성, 재사용성 높은 구조로 대규모 페이지 구성에 적합 |
| **Redux** | 중앙 집중형 상태 관리로 컴포넌트 간 상태 공유 용이, 유지보수성과 예측 가능성 향상 |
| **JSX** | HTML과 JavaScript가 자연스럽게 결합된 문법으로 직관적인 코드 작성 가능 |

---

## 🙋🏻‍♀️ 담당 역할

- **프론트엔드 전체 폴더 구조 설계 및 초기 세팅**
  - 구조화된 폴더링 및 재사용 가능한 컴포넌트 구조 설계
- **화면 설계서 및 Figma 디자인 직접 제작**
- **주요 페이지 UI/UX 및 기능 구현**
  - `Main`, `Thread On` 페이지 담당
  - `Thread On` 기능 백엔드와 연동하여 구현
- **상태 관리 및 데이터 흐름 제어**
  - Redux Toolkit을 활용해 메인 및 스레드 페이지의 전역 상태를 설계하고 관리
  - `createAsyncThunk`를 사용해 스레드/도서 관련 비동기 요청 처리 로직 구현
  - 페이지 간 데이터 흐름과 조건부 api 호출 구현
- **DB 연동 후 프론트 유지 보수**
  - 담당 페이지의 데이터 상태 확인 및 기능 점검

---

## 📄 주요 페이지

- **Home**: 도서 관련 소식 전달 및 감성적 메인 페이지 
- **Book List**: 도서 목록, 도서 별 평점 및 리뷰 확인
- **Chat Stella**: 독서 토론 챗봇 채팅 페이지
- **Thread On**: 사용자들이 짧은 감상이나 의견을 나누는 스레드형 게시판
- **Community**: 자유게시판 및 마이포럼 기능
- **My Page**: 사용자의 회원 정보 관리

---
## 회고 및 느낀점
프론트엔드 구조 설계부터 실제 화면 구현, 상태 관리까지 직접 경험하며 실질적인 프로젝트 개발 흐름을 익힐 수 있었습니다.  
특히, 페이지 전반의 구조를 잡고 재사용 가능한 컴포넌트를 설계하면서 **초기 설계가 개발 효율성과 유지보수성에 미치는 영향**을 체감하게 되었습니다.  
메인 페이지와 스레드 기능 구현에서는 Redux Toolkit을 활용해 상태 흐름과 비동기 데이터 요청 처리를 구성하며 프론트엔드 전반에 대한 실전 역량을 높일 수 있었습니다.

또한, 프로젝트 중반에는 팀원 간의 소통 부족으로 일정과 구현 방향에 혼선이 생긴 일이 있었지만,  
Slack 메신저를 통한 소통과 **잦은 회의 제안을 통해 서로의 진행 상황을 정기적으로 공유**하며 문제를 해결해 나갔습니다.  
이 경험을 통해 협업에서의 **명확한 커뮤니케이션과 조율 능력의 중요성**을 다시금 느낄 수 있었습니다.

---

## 기타
> 실제 배포 시 페이지 이미지와 시연 영상은 PPT에서 확인 가능합니다.

- 📊 발표 ppt: https://docs.google.com/presentation/d/1_3Qnvyem_cIrD9mhtqh-EvrN_192ymu-qkAgFCW1fog/edit?usp=sharing
