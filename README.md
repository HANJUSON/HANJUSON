<!-- Header Banner -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=8B0029&height=180&section=header&text=HANJUSON&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Software%20Engineer%20%7C%20Korea%20University&descColor=B49B57&descAlignY=58&descSize=18" />

</div>

---

<!-- Intro -->
<div align="center">

### 👋 Hi, I'm 손한주 (Hanju Son)

**고려대학교(세종) 컴퓨터소프트웨어학과** · 3rd Year

**커널 레벨 시스템 프로그래밍(C)부터 풀스택 웹 서비스(TypeScript/React)까지**<br/>
직접 만들고, 측정하고, 문서로 남깁니다.

[![Email](https://img.shields.io/badge/Email-8B0029?style=flat-square&logo=gmail&logoColor=white)](mailto:sonhanju36@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-222222?style=flat-square&logo=github&logoColor=white)](https://github.com/HANJUSON)

</div>

---

<!-- About Me -->
## 🎓 About Me

```text
🏫  고려대학교(세종) 컴퓨터소프트웨어학과 — 3학년
🔬  프로그래밍 러닝센터(Programming Learning Center) 근무
🌏  관심 분야: Software Architecture, AI Engineering, 금융 시스템
```

---

<!-- Currently -->
## 🚀 Currently

- **KU AI 아이디어 챌린지 3조** 참여 중 (2026)
- **조던 룰 계산기** 기능 확장 — 시세 파이프라인 안정화
- 시스템 프로그래밍 · LLM 에이전트 오케스트레이션 심화 학습

---

<!-- Featured Projects -->
## 📌 Featured Projects

> 팀 프로젝트는 **제 실제 기여 범위**를 함께 적었습니다.

### 🖥️ [Liberal_OS](https://github.com/HANJUSON/Liberal_OS) — xv6 커널 기반 멀티 에이전트 OS
xv6 커널을 **직접 수정**해 5개 LLM 에이전트(파서 → 분류 → 원인분석 → 수정제안 → 평가)를
**OS 프로세스로** 격리·스케줄링·검증·캐싱하는 로그 트리아지 시스템.
Python `multiprocessing`이 아니라 `proc.c` · `syscall.c` · `verifier.c` · `cache.c` 커널 코드로 구현.

`C` `xv6` `Shell` · **2인 팀 · 커밋 66/108 (약 61%)** · [기술 보고서](https://github.com/HANJUSON/Liberal_OS/blob/main/docs/TECHNICAL_REPORT.md)

---

### 🏛️ [세종 민원 안내 AI](https://github.com/HANJUSON/2026-07-kosj-industry-practice-team01) — 근거 기반 민원 응대 챗봇 MVP
"근거를 확인할 수 있고, 불확실하면 안전하게 넘기는" 공공 AI 챗봇.
전입신고 **한 도메인을 좁고 깊게** 완성 — 모든 답변에 출처 배지·원문 스니펫을 표기하고,
근거가 부족하면 추측 대신 담당 부서로 연결합니다.

`Python` `JavaScript` `Docker` `RAG` · **5인 팀 · 커밋 42/72 (최다 기여)** · 2026 고려대 세종 산업체 실습

---

### 📈 [JORDANRULE](https://github.com/HANJUSON/JORDANRULE) — 조던 룰 리밸런싱 계산기
보유 종목의 현재가·전고점으로 리밸런싱 / 말뚝박기 표를 자동 생성하는 웹 앱.
나스닥 -3% 이벤트 경과 여부로 모드를 판별하고, 계산 규칙은 **SSOT 스펙 문서**로 단일화.
설계 판단은 **ADR(Architecture Decision Record)** 로 기록했습니다.

`React 18` `TypeScript (strict)` `Vite` `Supabase (Postgres/Auth/RLS)` `Vitest 55+ tests` · **개인 프로젝트**

---

### 🌐 [TCP vs UDP for HFT](https://github.com/HANJUSON/Network_2026_1) — 전송 프로토콜 지연 벤치마크
소형 HFT 거래소(주문서·체결 엔진)를 직접 만들어 동일 주문 흐름을 TCP·UDP로 실측.
loopback은 커널이 네트워크 스택을 우회하므로 **Docker bridge 격리망**을 구성하고
`tc netem`으로 재현 가능한 패킷 손실을 주입했습니다.
결과: **손실 1%에서 TCP P99 지연이 375µs → 204ms (545배) 폭증**, UDP는 374µs로 평탄.

`Python` `Docker` `tc netem` `Flask-SocketIO` · **4인 팀 · 벤치마크 시스템 단독 구현** — 팀의 유일한 1차 측정 데이터를 산출했습니다(타 팀원 파트는 문헌 조사) · [📹 데모 영상](https://youtu.be/AZ7Uc7IFcnU)

---

### 📚 [KUS-TUDY · Big O(S)](https://github.com/HANJUSON/kustudy2026) — 한 학기 학습공동체 기록
알고리즘 × 운영체제 × LLM. 매주 `이론 → 구현 → 검증` 사이클을 12주간 반복한 활동 전체 기록.

`12주차 활동 보고서` `주차별 결과물` · 4인 팀

---

<!-- Tech Stack -->
## 🛠️ Tech Stack

**주력** — 프로젝트에서 실제로 설계·구현한 스택

![Python](https://img.shields.io/badge/Python-8B0029?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-8B0029?style=flat-square&logo=c&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-8B0029?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-8B0029?style=flat-square&logo=react&logoColor=white)

**사용 경험 있음** — 과제·팀 프로젝트에서 다뤄본 스택

![Java](https://img.shields.io/badge/Java-B49B57?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-B49B57?style=flat-square&logo=javascript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-B49B57?style=flat-square&logo=docker&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-B49B57?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-B49B57?style=flat-square&logo=postgresql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-B49B57?style=flat-square&logo=linux&logoColor=white)
![Git](https://img.shields.io/badge/Git-B49B57?style=flat-square&logo=git&logoColor=white)

---

<!-- Interests -->
## 💡 Interests

| Area | Focus | 관련 프로젝트 |
|------|-------|--------------|
| 🏗️ Software Architecture | 시스템 설계, 커널 레벨 프로세스 관리 | Liberal_OS |
| 🤖 AI / LLM Applications | RAG, 에이전트 오케스트레이션 | 세종 민원 안내 AI |
| 💹 Finance Systems | 트레이딩 시스템, 저지연 네트워크 | JORDANRULE · TCP vs UDP |

---

<!-- Stats -->
## 📈 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=HANJUSON&show_icons=true&theme=default&title_color=8B0029&icon_color=B49B57&text_color=333333&border_color=8B0029&bg_color=ffffff&hide_border=false" />
&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HANJUSON&layout=compact&title_color=8B0029&text_color=333333&border_color=8B0029&bg_color=ffffff&hide_border=false" />

</div>

---

<!-- Footer -->
<div align="center">

**함께 일할 때 궁금한 점은 편하게 연락 주세요.**

[![Email](https://img.shields.io/badge/sonhanju36@gmail.com-8B0029?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sonhanju36@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=8B0029&height=100&section=footer" />

</div>
