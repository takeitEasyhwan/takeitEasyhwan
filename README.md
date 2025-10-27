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
<h3 align="left">💹 SOL Assistant – 초보자 투자 어시스트 대시보드</h3>
<p><strong>역할:</strong> PM, Backend Developer (spring)</p>
<p>신한투자증권 프로디지털 아카데미 파이널 프로젝트로, 초보 투자자를 위한 <strong>‘투자 어시스트 대시보드’</strong>를 개발했습니다.</p>
<strong>아키텍처 설계</strong>
<ul>
    <li>4개의 마이크로서비스(<code>internal</code>, <code>external</code>, <code>chart-similarity</code>, <code>common</code>)로 분리하여 서비스 간 결합도를 낮추고, 장애 전파 없는 독립 배포 구조 구현</li>
</ul>
<strong>MSA-external-service (뉴스, 차트 파트)</strong>  
<ul>
    <li>한국투자증권 Open API를 활용해 실시간 <strong>시세·거래량 데이터</strong> 수집</li>
    <li><strong>FinanceDataReader</strong>와 <strong>TA-Lib</strong> 기반으로 이동평균선, RSI 등 기술 지표 계산</li>
    <li><strong>섹터 뉴스 크롤러</strong> 제작 및 뉴스 요약 알고리즘 적용</li>
    <li>최신 시장 뉴스와 종목 차트를 통합하여 “오늘의 시장 흐름” 인사이트 제공</li>
</ul>
<strong>MSA-internal-service (매매 기록, 사용자 대시보드 파트)</strong>
<ul>
    <li>사용자별 <strong>매매 이력(user_trades)</strong>과 <strong>보유 종목(user_stocks)</strong> 관리 API 개발</li>
    <li><strong>Redis</strong>를 이용해 사용자별 투자 리포트 캐싱 → 대시보드 조회 속도 45% 향상</li>
    <li>거래 데이터 기반 <strong>수익률·보유일수·거래패턴 분석</strong> 로직 구현</li>
    <li>PM 역할로서 API 스펙, 도메인 설계, 오류 복구 시나리오 수립 주도</li>
</ul>
<strong>데이터 파이프라인:</strong>
<ul>
    <li>사용자 행동 로그를 10초 간격으로 수집 → <strong>Redis → Kafka → RDS</strong> 비동기 파이프라인 구축</li>
    <li>Kafka 메시징으로 서비스 간 통신 지연을 <strong>300ms → 40ms</strong>로 단축</li>
</ul>
<strong>협업 및 관리</strong>
<ul>
    <li>팀 리더로서 전체 시스템 아키텍처 정의, 데이터 흐름 설계, 장애 대응 프로세스 수립</li>
    <li>프론트·AI 파트와 협업하며 <strong>Kafka 토픽 설계, Redis 키 구조, API 명세서</strong>를 주도 작성</li>
</ul>
<p><strong>성과:</strong> 안정적인 실시간 아키텍처 구현</p>
<p><strong>🧩 Tech Stack:</strong> Spring Boot · Kafka · Redis · MariaDB · Docker · AWS EC2 · React</p>
<p>
  🔗 <a href="https://github.com/takeitEasyhwan/SOL-Assistant-backend-MSA" target="_blank">Backend GitHub Repository</a> <br>
</p>


<hr>

<h3 align="left">📊 Candly – AI 기반 주식 차트 학습 서비스</h3>
<p><strong>역할:</strong> PM, Fullstack Developer (React + Node.js)</p>
<p>초보 투자자들이 실제 데이터를 기반으로 차트 해석과 재무 분석을 학습할 수 있는 웹 서비스 <strong>‘Candly’</strong>를 개발했습니다.</p>

<ul>
  <li>Dart OpenAPI로 KOSPI200 종목의 20년치 데이터 수집</li>
  <li>Python·Node.js 기반 데이터 전처리 및 재무 지표(PER, PBR, ROE 등) 자동 계산</li>
  <li>React 클라이언트에서 성장성·수익성 복합 그래프 구현</li>
  <li>사용자별 학습 기록을 ‘잔디형 캘린더’로 시각화</li>
</ul>

<p><strong>성과:</strong> 데이터 로딩 속도 <strong>35%</strong> 개선 · 차트 정확도 <strong>99%</strong></p>
<p><strong>🧩 Tech Stack:</strong> React · Node.js · Express · Python · AWS EC2 · MongoDB</p>
<p>
  🔗 <a href="https://github.com/takeitEasyhwan/Candly-Server" target="_blank">Backend GitHub Repository</a> <br>
</p>
<p>
  🔗 <a href="https://github.com/takeitEasyhwan/Candly-Client" target="_blank">Frontend GitHub Repository</a> <br>
</p>
<hr>

<h3 align="left">📱 QweR – KoBART 기반 QR 코드 요약 앱</h3>
<p><strong>역할:</strong> Android Developer, NLP Model Trainer</p>
<p>QR 코드를 스캔해 본문을 요약하고, 유해 콘텐츠를 차단하는 모바일 앱 <strong>‘QweR’</strong>를 개발했습니다.</p>

<ul>
  <li>기사 데이터를 직접 수집하고 KoBART 모델을 재학습하여 요약 품질 개선</li>
  <li>Batch Size 조정으로 처리 속도 <strong>15초 → 10초</strong> 단축</li>
  <li>ChatGPT API 통합으로 KoBART·GPT 선택형 하이브리드 구조 설계</li>
  <li>Kotlin 기반 MVVM 아키텍처 적용, 실시간 요약 결과 반영</li>
  <li>실험 리포트를 통해 팀 내 기술 의사결정 주도</li>
</ul>

<p><strong>성과:</strong> 하이브리드 요약 시스템 완성 → <strong>우수 프로젝트 선정</strong></p>
<p><strong>🧩 Tech Stack:</strong> Kotlin · Android Studio · KoBART · ChatGPT API</p>
<p><a href="https://www.notion.so/2-QweR-b832eedf1d334f62ba4a4f6306dd0a76?pvs=21" target="_blank">📄 시스템 개발 보고서 보기</a></p>

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
