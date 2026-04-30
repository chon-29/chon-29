<div align="center">

<!-- Header Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:e0f2fe,50:bae6fd,100:7dd3fc&height=200&section=header&text=Son%20Hyungeun&fontSize=52&fontColor=0369a1&fontAlignY=38&desc=Security%20Engineer%20%7C%20Cloud%20%7C%20CERT%20%7C%20Reversing&descAlignY=58&descSize=16&descColor=0369a1&animation=fadeIn" />

</div>

<div align="center">

[![Portfolio](https://img.shields.io/badge/🌐_PORTFOLIO-준비중-0ea5e9?style=for-the-badge&logoColor=white)](#)
[![Blog](https://img.shields.io/badge/📝_BLOG-chon29.tistory.com-0ea5e9?style=for-the-badge&logoColor=white)](https://chon29.tistory.com/category)
[![LinkedIn](https://img.shields.io/badge/💼_LINKEDIN-hyungeun--son-0284c7?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hyungeun-son-28a7663b3)
[![Email](https://img.shields.io/badge/📧_EMAIL-son29ag@gmail.com-0ea5e9?style=for-the-badge&logoColor=white)](mailto:son29ag@gmail.com)

</div>

---

## 👋 소개

안녕하세요, **손형은**입니다.

**클라우드 보안 · CERT · 리버싱 / 악성코드 분석**에 관심을 갖고 있는 보안 엔지니어 지망생입니다.  
AWS 환경에서의 침해 사고 탐지와 악성코드 분석을 중심으로  
다양한 보안 영역을 탐구하며 성장하고 있습니다.

> 🦫 Baby Beavers 1기 (2026.03 ~)  
> 🥇 상명대 캡스톤디자인 경진대회 **대상** (2026.02)  
> 🏆 대한전기학회 18회 **대상** (2025.10)  
> 🛡️ KITRI 화이트햇 스쿨 3기 수료 (2025.03 ~ 2025.09)  
> 🎓 상명대학교 정보보안공학과 입학 (2023.03)

---

## 🛠️ 기술 스택

<div align="center">

| 영역 | 기술 |
|---|---|
| **Cloud** | 인프라 구축 · Terraform |
| **CERT** | 침해사고 탐지 · 로그 분석 · SIEM · 취약점 관리 · SCA · Incident Response |
| **Reversing / Malware** | 악성코드 분석 · 리버싱 · 정적·동적 분석 · ML 기반 분류 |
| **Dev & Infra** | Python · Bash · PowerShell · Linux · Docker · Git · MCP |

</div>

---

## 🚀 대표 프로젝트

### 🤖 자율형 AI Agent(OpenClaw)를 활용한 취약점 분석 자동화
> 캡스톤디자인 4-1학기 · skrr 팀 | **2026.03 ~ 진행 중**

Discord Bot UI를 통해 사용자 명령을 받아 AI 에이전트가 자동으로 취약점을 스캔하고 MITRE ATT&CK 시나리오와 매핑하여 보고서를 생성하는 자율형 보안 분석 시스템 개발.

- OpenClaw Agent — Vulnerability Scanner · MITRE ATT&CK Scenario Mapper 스킬 설계
- 스캔 결과 기반 공격 시나리오 자동 생성
- Discord Bot 인터페이스 연동 및 취약점 리포트 시각화

🔗 [lhywk/openclaw-vulnerability-scanner](https://github.com/lhywk/openclaw-vulnerability-scanner)

---

### 🦦 Baby Beavers 1기 — 클라우드 보안 & 레드팀 학습
> Baby Beavers · Justin Beavers 팀 | **2026.03 ~ 진행 중**

공격자 관점의 레드팀 시나리오를 설계하고 AWS 인프라를 직접 구축하며 클라우드 보안을 심화 학습 중.

- 레드팀 관점의 공격 시나리오 설계 및 실습
- Terraform을 활용한 AWS 인프라 구축 및 자동화
- 횡적 이동(Lateral Movement) 공격 기법 연구

🔗 [Beaver-Dam-Community/GnawLab](https://github.com/Beaver-Dam-Community/GnawLab)

---

### 🔍 MCP 기반 소프트웨어 구성 요소 분석 및 취약점 관리 시스템
> 캡스톤디자인 3-2학기 · 타이거개구리 팀 | **2025.10.23** | 🏆 **대한전기학회 18회 대상** | 🥇 **상명대 캡스톤 대상 (2026.02)**

MCP(Model Context Protocol) 기반으로 소프트웨어 구성 요소(SCA)를 자동 분석하고,  
CVE 데이터베이스와 연동하여 **취약점을 탐지·관리·보고**하는 통합 시스템 구현.

- 소프트웨어 의존성 자동 파싱 및 구성 요소 목록화
- CVE 데이터베이스 연동 취약점 자동 매핑
- MCP 기반 자동화 파이프라인 설계

🔗 [lhywk/mcp-sca-vms](https://github.com/lhywk/mcp-sca-vms)

---

### ☁️ AWS 클라우드 환경의 로그 기반 침해 사고 탐지 환경 구축
> 화이트햇 스쿨 3기 · AWS 애쓰지 말라고 했지 팀 | **2025.05 ~ 2025.08**

AWS 환경에서 실제 공격 시나리오에 대응하는 로그 기반 침해 사고 탐지 파이프라인 설계 및 구현.

- CloudTrail · CloudWatch · GuardDuty 등 AWS 네이티브 보안 서비스 활용
- 이상 행위 탐지 룰셋 설계 및 알림 자동화

🔗 [whs-dontdothat-aws](https://github.com/whs-dontdothat-aws)

---

### 🦠 악성코드 유사도 기반 논문 추천 및 연구 동향 시각화 서비스
> KISIA AI 보안 기술개발 교육과정 · 가락동 패거리 팀 | **2024.06 ~ 2024.10**

악성코드 파일을 입력받아 악성 여부를 판별하고, 임베딩 기반 유사도 검색으로  
관련 논문을 추천하며 시계열 연구 동향을 시각화하는 서비스 개발.

- 악성코드 데이터셋 종류별 labeling 및 임베딩 모델 구축
- arxiv 논문 크롤링 자동화 및 메타데이터 DB 구축
- 유사도 기반 관련 논문 추천 + 시계열 연구 동향 시각화
- citation · reference 분석으로 논문 연관성 파악

---

## 🏅 자격증

<div align="center">

| 취득일 | 자격증 |
|:---:|---|
| 2026.04.03 | 🐧 **리눅스마스터 2급** |
| 2026.03.11 | 💻 **정보처리기사** (필기 합격) |
| 2026.03.06 | 📊 **ADsP : 데이터 분석 준전문가** |
| 2025.07.27 | ☁️ **AWS Certified Cloud Practitioner** |

</div>

---

## 📅 경험 및 활동

<div align="center">

| 기간 | 내용 |
|:---:|---|
| 2026.03 ~ | 🤖 상명대학교 캡스톤디자인 4-1 — skrr 팀 (OpenClaw, 진행 중) |
| 2026.03 ~ | 🦫 Baby Beavers 1기 — Justin Beavers 팀 (진행 중) |
| 2026.02 | 🥇 상명대 캡스톤디자인 경진대회 **대상** |
| 2025.10.23 | 🏆 대한전기학회 18회 **대상** |
| 2025.03 ~ 2025.09 | 🛡️ KITRI 화이트햇 스쿨 3기 수료 |
| 2024.06 ~ 2024.10 | 🦠 KISIA AI 보안 기술개발 교육과정 — 악성코드 트랙 수료 |
| 2023.03 ~ | 🎓 상명대학교 정보보안공학과 입학 |

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=chon29&show_icons=true&theme=default&bg_color=f0f9ff&border_color=bae6fd&title_color=0ea5e9&icon_color=0ea5e9&text_color=0f172a&hide_border=false" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chon29&layout=compact&theme=default&bg_color=f0f9ff&border_color=bae6fd&title_color=0ea5e9&text_color=0f172a" />
</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7dd3fc,50:bae6fd,100:e0f2fe&height=120&section=footer" />

</div>
