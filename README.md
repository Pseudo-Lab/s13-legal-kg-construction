<h1 align="center"> 법률 지식 그래프 구축해보기 </h1>

<div align="center">
<a href="https://pseudo-lab.com"><img src="https://img.shields.io/badge/PseudoLab-S13-3776AB" alt="PseudoLab"/></a>
<a href="https://discord.gg/EPurkHVtp2"><img src="https://img.shields.io/badge/Discord-BF40BF" alt="Discord Community"/></a>
<a href="https://github.com/Pseudo-Lab/s13-legal-kg-construction/stargazers"><img src="https://img.shields.io/github/stars/Pseudo-Lab/s13-legal-kg-construction" alt="Stars Badge"/></a>
<a href="https://github.com/Pseudo-Lab/s13-legal-kg-construction/network/members"><img src="https://img.shields.io/github/forks/Pseudo-Lab/s13-legal-kg-construction" alt="Forks Badge"/></a>
<a href="https://github.com/Pseudo-Lab/s13-legal-kg-construction/pulls"><img src="https://img.shields.io/github/issues-pr/Pseudo-Lab/s13-legal-kg-construction" alt="Pull Requests Badge"/></a>
<a href="https://github.com/Pseudo-Lab/s13-legal-kg-construction/issues"><img src="https://img.shields.io/github/issues/Pseudo-Lab/s13-legal-kg-construction" alt="Issues Badge"/></a>
<a href="https://github.com/Pseudo-Lab/s13-legal-kg-construction/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/Pseudo-Lab/s13-legal-kg-construction?color=2b9348"></a>
</div>
<br>

> 저희 팀에서는 여러 분야에 걸쳐서 지식 그래프를 구축해보고 이를 활용하는 사례들을 쌓아나가려 합니다. 첫 번째 프로젝트에서는 법률 분야의 문서들을 가공해 지식 그래프를 구축하고 이를 오픈소스로 공유하는 활동을 진행합니다.

# 프로젝트 계획서

## ✨ Why this project?

### 우리가 이걸 왜 만들까요?

* 지식 그래프라는 기술을 접해보신 분들, 잘은 모르더라도 왠지 모를 흥미가 느껴지지 않나요? 평소에 많은 사유와 고민을 하는 사람들이라면 어느 분야에 특화된 지식, 나아가 '나'라는 개인의 페르소나까지도 담아낼 수 있다는 가능성이 매력적으로 다가올 것입니다.
* 이번 프로젝트의 일차적인 목표는 거창한 서비스나 어플리케이션을 만드는 것이 아닙니다. 우리의 목표는 지식 그래프를 구축하는 파이프라인을 **한 차례 경험**해보는 것입니다.
* 이번 기수에서는 그 중에서도 법률 데이터를 다루려고 합니다. 명확한 논리와 규칙, 체계가 강조되는 분야인만큼 지식 그래프 구축을 경험해보기에 좋은 실습 대상이 될 것입니다.
* 또한, 이렇게 개발한 지식 그래프를 다른 사람들도 사용할 수 있도록 공개하고 관련된 자료들을 만들어볼 것입니다. 이를 통해 오픈소스 생태계에 기여해보는 경험도 해보실 수 있습니다!

---

## 🎯 Goal

### 우리가 이번 시즌에 만들고 싶은 것

* [ ] Milestone 1: 법률 문서 수집 (우리에게 필요한 데이터가 담긴 문서들을 수집합니다.)
* [ ] Milestone 2: 법률 지식 그래프 구축 (GitHub 레포지토리를 통해 우리가 만든 법률 지식 그래프를 공개합니다.)
* [ ] Milestone 3: 지식 그래프 소개 (학회나 PseudoCon 발표를 통해 우리가 만든 지식 그래프를 다른 사람들에게 선보입니다.)

### 📦 Expected Outcome

최종적으로 다음과 같은 결과물을 만드는 것을 목표로 합니다.

* `Result / Product`: 구축 완료된 법률 지식 그래프(Graph DB)
* `Open Source Repository`: 가짜연구소 Github Repository 공개 데이터셋/코드
* `Documentation & Demo`: 소개 문서 및 학회/PseudoCon 발표 자료

---

# 🗺️ Weekly Roadmap

> **프로젝트의 12주 여정**
> 활동은 매주 수요일에 진행됩니다.

| Week    | 날짜        | 주요 활동 | 결과물 |
| ------- | ----------  | ----- | --- |
| **W01** | 2026.10.07  | **Hello, Everyone!** <br> OT 진행, 목적/스코프/타임라인 설명, 스터디 참여 이유 공유 | 팀원 소개 및 목표 공유 |
| **W02** | 2026.10.14  | **Stepping on the Shoulders of Giants (1/2)** <br> 참고할 사례 발표 및 공유 | 스터디 발표자료 |
| **W03** | 2026.10.21  | **Stepping on the Shoulders of Giants (2/2)** <br> 논문, 학술자료, GitHub 레포 분석 | 스터디 발표자료 |
| **W04** | 2026.10.28  | **협업 체계 논의하기** <br> 각자의 역할과 협업 관리 체계 논의 | 역할 분담표 및 체계 |
| **W05** | 2026.11.04  | **데이터 수집 (1/3)** <br> 법률 데이터 수집 및 관리 계획 | 데이터 수집 |
| **W06** | 2026.11.11  | **데이터 수집 (2/3) + 온톨로지 설계** <br> 수집 중간 점검 및 온톨로지 논의 | 데이터 수집, 온톨로지 초안 |
| **W07** | 2026.11.18  | **데이터 수집 (3/3) + 온톨로지 설계** <br> 지식 그래프 온톨로지 확정 | 최종 데이터셋 |
| **W08** | 2026.11.25  | **Buffer Week** <br> 여유를 두고 미흡한 점이나 추가 작업 검토 |  |
| **W09** | 2026.12.02  | **Graph DB 생성하기 + 문서 파싱 및 적재 (1/3)** | Graph DB 생성 및 적재 시작 |
| **W10** | 2026.12.09  | **문서 파싱 및 데이터 적재 (2/3)** <br> 적재 과정 중간 점검 |  |
| **W11** | 2026.12.16  | **문서 파싱 및 적재 (3/3) + 소개 문서 만들기** <br> 다른 사용자를 위한 기능 고민 | DB 적재 완료 및 소개 문서 |
| **W12** | 2026.12.23  | **Finished!** <br> 프로젝트 마무리 & 다음 기수 활동 논의 | 최종 결과물 및 회고 |

---

# 👥 Team

## Core Team

모임 정원은 최대 8명으로 구성되어 협업을 진행합니다.

| Role         | Name    | LinkedIn    |담당           |
| ------------ | ------- | ------- | ------------ |
| 🧭 Builder   | `남궁민상` | [msnamgoong](https://www.linkedin.com/in/msnamgoong/) | 프로젝트 리딩      |
| 🧑‍💻 Member | `@name` | | `__________` |
| 🧑‍💻 Member | `@name` | | `__________` |
| 🎨 Member    | `@name` | | `__________` |

---

# 📚 Archive

## 결과물

* 🔗 Repository: `TBA`
* 🌐 Demo: `TBA`
* 📝 Blog / Article: `TBA`
* 🎥 Presentation: `TBA`


## 🌱 참여 안내 (How to Engage)
- 빌더로 참여 — 프로젝트 기획·운영 주도
- 러너로 참여 — 연구·개발·테스트 등 실행
- 청강 참여 — 공개 세션 참여 가능

❗️참여 링크: [가짜연구소 디스코드](https://discord.gg/EPurkHVtp2)
❗️커뮤니케이션 채널: 디스코드 

**누구나 청강을 통해 모임을 참여하실 수 있습니다.**  
1. 특별한 신청 없이 정기 모임 시간에 맞추어 디스코드 #Room-GH 채널로 입장
2. Magical Week 중 행사에 참가
3. Pseudo Lab 행사에서 만나기

## Acknowledgement 🙏

이 프로젝트는 가짜연구소 Open Academy로 진행됩니다.
여러분의 참여와 기여가 ‘우연한 혁명(Serendipity Revolution)’을 가능하게 합니다. 모두에게 깊은 감사를 전합니다.
This project is developed as part of Pseudo-Lab's Open Research Initiative. Special thanks to our contributors and the open source community for their valuable insights and contributions.

## About Pseudo Lab 👋🏼

[Pseudo-Lab](https://pseudo-lab.com/) is a non-profit organization focused on advancing machine learning and AI technologies. Our core values of Sharing, Motivation, and Collaborative Joy drive us to create impactful open-source projects. With over 5k+ researchers, we are committed to advancing machine learning and AI technologies.

<h2>Contributors 😃</h2>
<a href="https://github.com/Pseudo-Lab/s13-legal-kg-construction/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Pseudo-Lab/s13-legal-kg-construction" />
</a>
<br><br>

<h2>License 🗞</h2>

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
