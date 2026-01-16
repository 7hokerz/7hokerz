## Hi there 👋

## 현재 진행중인 프로젝트

### 서버에만 모든 작업을 몰아주지 마세요: 스트리밍 아키텍처로 구현한 오디오 추출 & 업로드 최적화 시스템
**2025.08 - 진행 중** | 개인 & 학교 프로젝트

**Tech Stack**
- Backend: Express.js, TypeScript
- Frontend: Next.js
- Infrastructure: Google Cloud Run, Firebase App Hosting, Firebase Storage
- External API: OpenAI STT API

**주요 개선**
- **웹워커** 기반 FFmpeg.wasm 처리로 메인 스레드 블로킹 방지 및 UX 개선
- **청크 단위 분할 및 스트리밍 처리**로 외부 API의 파일 크기 제한 해결
- **적응형 업로드 및 백프레셔 패턴**으로 사용자 네트워크 환경별 최적화
- **스트리밍 아키텍처** 구현으로 서버 메모리 사용량 **97%** 감소
- 독립 Connection Pool 구성으로 외부 API 통신 안정성 향상

**주요 작업** [포트폴리오 링크 (비공개)]
1. 클라이언트 사이드 최적화 
2. 서버 사이드 및 네트워크 최적화
3. 트레이드오프 분석 및 결론

#### 사이트

- 기능 테스트 사이트 
(추후 게시 예정)

- 해당 기능이 포함된 실서비스 운영 사이트 
[(인공지능기반 학습 도움 문제 자동 생성 사이트)](https://quizgen.kr)

#### Repository
  - [Frontend](https://github.com/7hokerz/transcribe-frontend)

  - [Backend](https://github.com/7hokerz/transcribe-backend)


#### 추가 작업 중 (예정)
  - Cloud Tasks (태스크 큐) 도입
  - FFmpeg 트랜스코딩 도입
  - API 서버와 전사 워커 서버 분리


<!--
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2F7hokerz&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
**7hokerz/7hokerz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
