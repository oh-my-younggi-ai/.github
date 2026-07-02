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
> AI 를 **도구**로 쓰되, 문제를 푸는 건 결국 개발자다.
> 그래서 나는 만든 것을 항상 **측정하고, 실패를 분석하고, 다시 측정한다.**

Claude Code 기반의 스킬과 도구를 설계·벤치마킹·반복 개선하는 개인 작업 공간.

## 만드는 방식 (원칙)

1. **eval 을 먼저 정의한다** — 무엇이 "잘 된 것"인지 기계가 판정할 수 있게.
2. **baseline 대비 측정한다** — "좋아졌다"를 느낌이 아니라 수치(pass rate)로 말한다.
3. **실패모드를 분석한다** — 왜 틀렸는지 뜯어보고 프롬프트/구조를 고친다.
4. **이력을 남긴다** — 회차별 벤치 결과를 커밋해서 개선 과정을 감사 가능하게 한다.

## 프로젝트

| 프로젝트 | 설명 |
|---|---|
| [**skills**](https://github.com/oh-my-younggi-ai/skills) | 내가 만든 Claude Code 스킬 모음 (scenario-dev, iterative-refactor, design-doc, bmad-quick-dev) |
| [**cs-interview**](https://github.com/oh-my-younggi-ai/cs-interview) | CS 지식 위키 구축 + 그 위키 기준 AI 모의면접 (cs-wiki + cs-interviewer 한 쌍) |
| [**dotfiles**](https://github.com/oh-my-younggi-ai/dotfiles) | 도구 중립 규칙·컨벤션 + 커스텀 서브에이전트 6개 + Claude Code 설정 템플릿 (Codex 등으로 확장 가능) |

## 개선 이력 (측정된 것만)

| 스킬 | 회차 | pass rate | baseline | Δ | 토큰 |
|---|---|---|---|---|---|
| cs-wiki | iter-01 | **1.00** (15/15) | 0.53 | **+0.47** | 1.46× |
| scenario-dev | iter-01 | **1.00** (20/20) | 0.50 | **+0.50** | 1.65× |

<sub>전문 기록은 각 repo 의 `benchmarks/`, 방법론은 <a href="https://github.com/oh-my-younggi-ai/skills/blob/main/BENCHMARKING.md">skills/BENCHMARKING.md</a>. 회차가 늘면 행 추가.</sub>

<br>

<div align="center">

<!-- Footer banner -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:141413,10:2B2A28,30:D97757,75:2B2A28,100:141413&height=40&section=footer&text=&fontSize=0" width="100%"/>

</div>
