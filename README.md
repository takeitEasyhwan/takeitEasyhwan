<div align = 'center'>
    <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=호기심+많은+개발자&fontSize=60" />
    <h3>호기심을 원동력 삼아 끊임없이 도전하며 나아가는 주니어 개발자입니다</h3>
    <br><br>
    <h1>👋 WHO ARE YOU?</h1>
</div>
<div align = 'center'>
  <table>
    <tr>
        <p>🗣️ <strong>Communication</strong> &nbsp;&nbsp;&nbsp; 🚀 <strong>Challenge spirit</strong> &nbsp;&nbsp;&nbsp; 🔥 <strong>Eagerness</strong></p>
    </tr>
    <tr>
      <td width="30%">
        <img src="https://github.com/user-attachments/assets/0f9678cf-bbec-42ed-b864-72d570f5d970" width="150" style="border-radius: 50%;" alt="profile"/>
      </td>
      <td width="70%" align="left">
        <p><strong>1. 리더쉽과 소통</strong><br>
        여러 프로젝트에서 PM을 맡아 팀원들과의 적극적인 소통을 통해 문제를 해결하고 프로젝트를 성공적으로 이끌었습니다.</p>
        <p><strong>2. 실무 중심의 문제 해결</strong><br>
        인턴십 동안 Salesforce 기반 클라우드 환경에서 기업 요구에 맞춘 API 개발, 트리거 수정, 인터페이스 구축 등 실제 업무 프로세스를 경험했습니다.</p>
        <p><strong>3. 새로운 분야에 도전</strong><br>
        AI와 자연어처리 등 새로운 기술 분야에 꾸준히 도전해왔으며, KoBART 기반 텍스트 요약 프로젝트를 통해 서비스 적용 가능한 기술을 탐구했습니다.</p>
      </td>
    </tr>
  </table>
</div>

<br>


<br>

<h1>💡 Projects</h1>
<br>

<h3 align="left">📱 QweR – KoBART 기반 QR 코드 요약 앱</h3>
<p><strong>역할:</strong> Android Developer, NLP Model Trainer</p>
<p>
QR 코드를 스캔해 본문을 요약하고 유해 콘텐츠를 차단하는 모바일 애플리케이션 <strong>‘QweR’</strong>를 개발했습니다. 
Android 프론트엔드와 KoBART 요약 모델 구축을 담당했습니다.
기사 데이터를 직접 수집하여 모델을 재학습했고, Batch Size 조정으로 처리 속도를 <strong>15초 → 10초</strong>로 단축했습니다. 
또한 ChatGPT API를 통합해 사용자가 요약 엔진을 선택할 수 있는 하이브리드 구조를 설계했습니다.
MVVM 패턴 기반 UI 구조를 적용해 유지보수성을 높였으며, 팀 내 기술 결정 과정에서 실험 리포트를 활용해 합리적인 방향을 제시했습니다.
</p>
<p><strong>성과:</strong> KoBART·ChatGPT 통합 구조로 정확도와 속도 균형을 달성하여, 팀 프로젝트 중 <strong>우수 프로젝트로 선정</strong>되었습니다.</p>
<p><strong>🧩 Tech Stack:</strong> Kotlin, KoBART, ChatGPT API, Android Studio, HuggingFace Transformers</p>
<p>
<a href="https://www.notion.so/2-QweR-b832eedf1d334f62ba4a4f6306dd0a76?pvs=21" target="_blank">📄 [시스템 개발 최종보고서 보기]</a>
</p>

<hr>

<h3 align="left">📊 Candly – AI 기반 주식 차트 학습 서비스</h3>
<p><strong>역할:</strong> PM, Fullstack Developer (React + Node.js)</p>
<p>
초보 투자자들이 실제 데이터를 기반으로 차트 해석과 재무 분석을 학습할 수 있는 웹 서비스 <strong>‘Candly’</strong>를 개발했습니다.  
Dart OpenAPI를 통해 KOSPI200 종목의 20년치 데이터를 수집하고, Python·Node.js 기반 데이터 전처리 파이프라인을 구축했습니다.  
PER·PBR·ROE 등 주요 지표를 자동 계산하고, React 기반 클라이언트에서 성장성·수익성 복합 그래프를 구현했습니다.  
또한 사용자별 학습 기록을 잔디형 캘린더로 시각화하여 데이터 기반 학습 경험을 제공했습니다.
</p>
<p><strong>성과:</strong> 데이터 로딩 속도 <strong>35% 개선</strong>, 차트 정확도 <strong>99%</strong> 유지. 4주 내 전체 기능을 완성하며 <strong>팀 최고 완성도 프로젝트</strong>로 평가받았습니다.</p>
<p><strong>🧩 Tech Stack:</strong> React, Node.js, Express, Python, Chart.js, AWS EC2, MariaDB</p>

<hr>

<h3 align="left">💹 SOL Assistant – 초보자 투자 어시스트 대시보드</h3>
<p><strong>역할:</strong> PM, Backend Developer</p>
<p>
신한투자증권 프로디지털 아카데미 파이널 프로젝트로, 초보 투자자를 위한 <strong>투자 어시스트 대시보드 ‘SOL Assistant’</strong>를 개발했습니다.  
실시간 시장 데이터와 사용자 투자 성향을 분석해 맞춤형 리포트를 제공하는 인앱 서비스로, <strong>확장성과 실시간성 확보</strong>를 핵심 목표로 삼았습니다.
</p>
<p>
4개의 마이크로서비스(<code>internal</code>, <code>external</code>, <code>chart-similarity</code>, <code>common</code>)로 시스템을 분리해 유연한 구조를 구축하고,  
사용자 행동 로그를 10초 간격으로 수집하여 <strong>Redis → Kafka → RDS</strong>로 이어지는 비동기 파이프라인을 구현했습니다.  
Kafka 기반 메시징 구조를 통해 서비스 간 통신 지연을 <strong>300ms → 40ms</strong>로 단축하고, Redis 캐싱으로 대시보드 조회 속도를 <strong>45%</strong> 개선했습니다.  
PM으로서 전체 아키텍처 정의, 데이터 흐름 설계, 장애 대응 시나리오 수립을 총괄하며, API 명세와 Kafka 토픽 구조를 주도적으로 설계했습니다.
</p>
<p><strong>성과:</strong> MSA 구조 완성 및 안정적 데이터 파이프라인 구축으로 <strong>최우수 프로젝트 선정</strong>.</p>
<p><strong>🧩 Tech Stack:</strong> Spring Boot, Kafka, Redis, MariaDB, Docker, AWS EC2, React</p>


<br>

<h1> 💼 Experience </h1>

| 회사 | 부서 | 직급 | 담당 업무 | 기간 |
|:------|:------|:------:|:------:|:------:|
| 대유넥스티어 | 사업 본부(Platform DIV) | 인턴 |Salesforce 기반 ERP, CRM 시스템 개발 <br> 프로젝트 수행 | 2023.07.24 ~ 2023.12.31 |

<br>

<h1> 🎓 Education </h1>

| 기관 | 전공 / 과정 | 기간 |
|:------|:-------------|:------:|
| 신한투자증권 프로디지털아카데미 6기 | 클라우드 기반 금융 ICT 교육 이수 | 2025.04.22 ~ 2025.10.24 |
| 건국대학교 | 컴퓨터공학부 졸업 | 2018.03.02 ~ 2024.02.22 |
| 한국디지털미디어고등학교 | 웹프로그래밍과 졸업 | 2015.03.02 ~ 2018.02.02 |

<br>



<h1>🧠 Tech Stack</h1>
<div>
<h3>| Backend</h3>

<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white"/> 
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/> 
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/> 
<img src="https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white"/> 
<img src="https://img.shields.io/badge/Apex-17541F?style=for-the-badge&logo=salesforce&logoColor=white"/>

<br>

<h3>| Frontend</h3>

<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/> 
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/> 
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"/> 

<br>

<h3>| Language / Data</h3>

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> 
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black"/>

<br>

<h3>| Cloud / Infra</h3>

<img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/> 
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> 

<br>

<h3>| Collaboration</h3>

<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"/> 
<img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"/> 
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/> 
</div>
<br>

<h1>🪪 Cert</h1>

| 자격증명 | 자격번호 | 취득일 | 발급기관 |
|:----------:|:-----------:|:-----------:|:----------------:|
| 정보처리기사 | 25202011396L | 2025.09.12 | 한국산업인력공단 |

<br>

<h1>🗣️ Language</h1>

| 언어 | 자격증명 | 등급 | 발급기관 |
|:------:|:------------:|:------:|:-------------:|
| 영어 | OPIc | IH | ACTFL |

<br>

<h1>♣️ Fun Fact</h1>

- 학과 학생회 **부학생회장** (2022.01.01 ~ 2022.12.31)  
- 공대 학생회 **기획국 국원** (2018.03.10 ~ 2018.12.31)  
- **IT 동아리 ‘비빔밥’** 활동 (2022.01.01 ~ 2023.06.30)

<br>


<br>

---

<div align="center"> 
  <i>Follow me around the web:</i>
  <br><br>
  <a href="https://www.instagram.com/_nxwhxj" target="_blank"><img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?&style=flat-square&logo=instagram&logoColor=white" alt="Instagram"></a>
  <a href="https://velog.io/@wlghks0508" target="_blank"><img src="https://img.shields.io/badge/Velog-%230077B5.svg?&style=flat-square&logo=linkedin&logoColor=white" alt="Velog"></a>
</div>
