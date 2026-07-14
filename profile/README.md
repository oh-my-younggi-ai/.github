<!--
  이 파일은 GitHub Organization 프로필 랜딩이다.
  배포 위치: oh-my-younggi-ai/.github 레포의  profile/README.md
  (즉 이 dot-github/ 폴더가 `.github` 레포가 된다)
-->

<div align="center">

<!-- Header banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:141413,10:2B2A28,30:D97757,75:2B2A28,100:141413&height=100&section=header&text=&fontSize=0" width="100%"/>



<!-- Title Typing Effect -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Protest+Riot&pause=1000&color=D97757&size=40&center=true&vCenter=true&random=false&width=435&lines=Oh!+my+Younggi+Ai" alt="Typing SVG" /></a>

<br><br>
<div></div>
</div>

---

> AI 는 **도구**다. 문제를 푸는 건 사람이고, 무엇이 나아졌는지 판단하는 것도 사람이다.

Claude Code 로 **소프트웨어를 만드는 방식**과, 그 위에서 나온 **프로덕트**를 함께 쌓아가는 공간.

## 개발 원칙

- **측정으로 증명한다** — "좋아졌다"를 느낌이 아니라 baseline 대비 pass rate 로 말한다. eval 을 먼저 정의하고, 실패모드를 분석해 고친다.
- **개선은 끝나지 않는 루프다** — AI 와 함께 만들되, 무엇을 고칠지는 내가 판단한다. 한 번의 개선이 다음 개선을 부른다.
- **모든 개선에 이력을 남긴다** — 회차별 벤치 결과를 커밋해 개선 과정을 감사 가능하게 한다.

## 프로덕트 · *완성해서 쓰는 것*

| 프로젝트 | 설명 |
|---|---|
| [**cs-interview**](https://github.com/oh-my-younggi-ai/cs-interview) | CS 지식 위키 구축 + 그 위키 기준 AI 모의면접 (cs-wiki + cs-interviewer 한 쌍) |

## 챌린지 · *실측으로 겨룬 것*

| 프로젝트 | 설명 |
|---|---|
| [**2026-SCPC-Harness-Engineering-AI-Challenge**](https://github.com/oh-my-younggi-ai/2026-SCPC-Harness-Engineering-AI-Challenge) | 삼성 SCPC 2026 AI 트랙 — 순수 Python 규칙 기반 AI Agent Harness. 리더보드 **0.0882 → 0.8496**, 35 iterations · 15회 제출 전부 단일가설 실험으로 기록 |

<sub>회고: <a href="https://velog.io/@giyoul/1%ED%83%84-AI%ED%95%9C%ED%85%8C-%ED%95%B4%EC%BB%A4%ED%86%A4%EC%9D%84-%EC%8B%9C%EC%BC%9C%EB%B4%A4%EB%8B%A4-%EC%82%BC%EC%84%B1-SCPC-2026-AI-Challenge-DACON">AI한테 해커톤을 시켜봤다 1탄</a> · <a href="https://velog.io/@giyoul/2%ED%83%84-AI%ED%95%9C%ED%85%8C-%ED%95%B4%EC%BB%A4%ED%86%A4%EC%9D%84-%EC%8B%9C%EC%BC%9C%EB%B4%A4%EB%8B%A4-%EC%82%BC%EC%84%B1-SCPC-2026-AI-Challenge-DACON">2탄</a> · 에세이: <a href="https://velog.io/@giyoul/%ED%95%98%EB%84%A4%EC%8A%A4%EB%8A%94-%EC%96%B4%EB%94%94%EA%B9%8C%EC%A7%80-%EC%8C%93%EC%95%84%EC%95%BC-%ED%95%98%EB%8A%94%EA%B0%80">하네스는 어디까지 쌓아야 하는가</a></sub>

## 워크플로우 · *더 잘 만들기 위한 것*

| 프로젝트 | 설명 |
|---|---|
| [**skills**](https://github.com/oh-my-younggi-ai/skills) | Claude Code 스킬 모음 — product-planning, scenario-dev, iterative-refactor, design-doc, bmad-quick-dev, blog-voice |
| [**dotfiles**](https://github.com/oh-my-younggi-ai/dotfiles) | 도구 중립 규칙·컨벤션 + 커스텀 서브에이전트 6개 + Claude Code 설정 템플릿 |

## 개선 이력 · *측정된 것만*

| 스킬 | 회차 | 측정 결과 |
|---|---|---|
| product-planning | iter-01 (2026-07) | 결정론 채점 — floor **18/18 green** · 빈 상태 커버리지 **0.32 → 0.78** · Phase 도메인 근거율 **0 → 1.00** · 미해결 표기 0.67 → **0건** · 1.63× tokens |
| cs-wiki | iter-02 (2026-07) | 결정론 채점 v2 — 회귀 검사 **16/16 green** · 점검 recall **1.00** (3/3) · 갭 추천 정밀도 **1.00** · 대필 0건 |
| cs-wiki | iter-01 (2026-06) | pass rate **1.00** (15/15) vs baseline 0.53 · **Δ +0.47** · 1.46× tokens |
| scenario-dev | iter-01 (2026-06) | pass rate **1.00** (20/20) vs baseline 0.50 · **Δ +0.50** · 1.65× tokens |

실제 운영 지식베이스도 같은 도구로 측정한다 — 위키 건강검진에서 역링크 완전성 **0.70 → 0.91**,
고아 페이지 **12% → 0%** (측정 → 수정 → 재측정 루프).

<sub>iter-02 부터 LLM judge 없는 <b>결정론적 3층 채점</b>(회귀 바닥 / 진행 지표 / 확장 eval)으로 전환.
전문 기록은 각 repo 의 <code>benchmarks/</code>, 방법론은 <a href="https://github.com/oh-my-younggi-ai/skills/blob/main/BENCHMARKING.md">skills/BENCHMARKING.md</a>. 회차가 늘면 행 추가.</sub>

<br>

<div align="center">

<!-- Footer banner -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:141413,10:2B2A28,30:D97757,75:2B2A28,100:141413&height=40&section=footer&text=&fontSize=0" width="100%"/>

</div>
