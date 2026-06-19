## Hi there 👋

## Tech Stack

[![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)](https://nestjs.com/) [![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot) [![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://cloud.google.com/) [![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)](https://www.terraform.io/) [![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/) [![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/) [![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)](https://firebase.google.com/)


## Ongoing Project

### 서버에만 모든 작업을 몰아주지 마세요: 스트리밍 아키텍처로 구현한 오디오 추출 & 업로드 최적화 시스템
**2025.08 - 진행 중** | 개인 & 학교 프로젝트

**Tech Stack**
- Backend: Express.js, TypeScript
- Frontend: Next.js
- Infrastructure: Google Cloud Run, Firebase App Hosting, Firebase Storage
- External API: OpenAI STT API

**Key Improvements**
- **웹워커** 기반 FFmpeg.wasm 처리로 메인 스레드 블로킹 방지 및 UX 개선
- **청크 단위 분할 및 스트리밍 처리**로 외부 API의 파일 크기 제한 해결
- **적응형 업로드 및 백프레셔 패턴**으로 사용자 네트워크 환경별 최적화
- **스트리밍 아키텍처** 구현으로 서버 메모리 사용량 **97%** 감소
- 독립 Connection Pool 구성으로 외부 API 통신 안정성 향상

#### Site

- 기능 테스트 사이트 
(추후 게시 예정)
- 해당 기능이 포함된 실서비스 운영 사이트 
[Quizgen.kr - 인공지능기반 학습 도움 문제 자동 생성 사이트](https://quizgen.kr)

#### Repository
  - [Frontend](https://github.com/7hokerz/transcribe-frontend)
  - [Backend](https://github.com/7hokerz/transcribe-backend)


#### In Progress
  - Cloud Tasks (태스크 큐) 도입
  - FFmpeg 트랜스코딩 도입
  - API 서버와 전사 워커 서버 분리


## 🏆 Contribution

<p>
  <a href="https://github.com/firebase/firebase-tools"><img src="https://avatars.githubusercontent.com/u/1335026?s=48&v=4" alt="Firebase" width="32" height="32" /></a>
  <a href="https://github.com/genkit-ai/genkit"><img src="https://avatars.githubusercontent.com/u/166032008?s=48&v=4" alt="Genkit" width="32" height="32" /></a>
  <a href="https://github.com/google-gemini/gemini-cli"><img src="https://avatars.githubusercontent.com/u/161781182?s=48&v=4" alt="Google Gemini" width="32" height="32" /></a>
  <a href="https://github.com/googleapis/nodejs-storage"><img src="https://avatars.githubusercontent.com/u/16785467?s=48&v=4" alt="Google APIs" width="32" height="32" /></a>
  <a href="https://github.com/nodejs/undici"><img src="https://avatars.githubusercontent.com/u/9950313?s=48&v=4" alt="Node.js" width="32" height="32" /></a>
  <a href="https://github.com/DefinitelyTyped/DefinitelyTyped"><img src="https://avatars.githubusercontent.com/u/3637556?s=48&v=4" alt="DefinitelyTyped" width="32" height="32" /></a>
</p>

| Repository | PR | Summary |
| --- | --- | --- |
| `firebase/firebase-tools` | [#10669](https://github.com/firebase/firebase-tools/pull/10669) | Added the `apphosting:secrets:revokeaccess` command |
| `genkit-ai/genkit` | [#4209](https://github.com/genkit-ai/genkit/pull/4209) | Preserved legacy image URL handling when `contentType` is missing |
| `google-gemini/gemini-cli` | [#21123](https://github.com/google-gemini/gemini-cli/pull/21123) | Prevented unhandled `AbortError` crashes during stream loop detection |
| `googleapis/nodejs-storage` | [#2716](https://github.com/googleapis/nodejs-storage/pull/2716) | Fixed V4 policy URL generation in emulator mode |
| `nodejs/undici` | [#5009](https://github.com/nodejs/undici/pull/5009) | Updated JSDoc to reflect the `allowH2` default value |
| `DefinitelyTyped/DefinitelyTyped` | [#74884](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/74884) | Replaced `NodeJS.ReadableStream` with `stream.Readable` in `@types/pdfkit` |

<details>
<summary> Full Contribution List </summary>

| Repository | PR | Summary |
| --- | --- | --- |
| `genkit-ai/genkit` | [#4263](https://github.com/genkit-ai/genkit/pull/4263) | Fixed type overload shadowing for OpenAI models with specific suffixes |
| `genkit-ai/genkit` | [#4280](https://github.com/genkit-ai/genkit/pull/4280) | Generalized STT module naming and added `gpt-4o-mini-transcribe` |
| `genkit-ai/genkit` | [#4330](https://github.com/genkit-ai/genkit/pull/4330) | Added test coverage for the audio module |
| `genkit-ai/genkit` | [#4497](https://github.com/genkit-ai/genkit/pull/4497) | Fixed Google AI provider and model configuration in test apps |
| `genkit-ai/genkit` | [#4708](https://github.com/genkit-ai/genkit/pull/4708) | Fixed invalid model ID errors in transcription models |
| `genkit-ai/genkit` | [#4786](https://github.com/genkit-ai/genkit/pull/4786) | Added translation adapter and translation flow in test apps |
| `genkit-ai/genkit` | [#5036](https://github.com/genkit-ai/genkit/pull/5036) | Explicitly allowed `null` types in `promptDir` |
| `genkit-ai/genkit` | [#5201](https://github.com/genkit-ai/genkit/pull/5201) | Fixed `ValidationResponse` typing and cached AJV validators |

</details>

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
