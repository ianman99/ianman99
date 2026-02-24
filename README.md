<div align="center">

# Hi there, I'm **ianman99** <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>

### Quantitative Finance Developer from Korea

<p>
  <a href="https://www.prober.kr"><img src="https://img.shields.io/badge/Website-prober.kr-0A66C2?style=for-the-badge&logo=google-chrome&logoColor=white"/></a>
  <a href="https://ianman99.tistory.com"><img src="https://img.shields.io/badge/Blog-Tistory-FF5722?style=for-the-badge&logo=tistory&logoColor=white"/></a>
  <a href="https://github.com/ianman99"><img src="https://img.shields.io/badge/GitHub-ianman99-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

</div>

---

## About Me

- **Financial Data Platform** & **Automated Trading System**을 구축하는 풀스택 개발자입니다
- [**Prober**](https://www.prober.kr) - 실시간 금융 시세 및 AI 시황 분석 커뮤니티 플랫폼 운영 (React + Node.js)
- DART(전자공시), KRX(한국거래소) 기반 금융 데이터 파이프라인 설계 및 운영
- 이벤트 드리븐 전략(자사주 매입 공시 기반) 자동 매매 시스템 개발
- 주식, 지수, 선물/옵션, 채권, 환율, 원자재, 암호화폐 등 멀티 자산 커버

---

## Tech Stack

<div align="center">

#### Language
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

#### Frontend
![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

#### Backend
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

#### Data & Database
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)

#### Infra & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)

#### API & Real-time
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![AIOHTTP](https://img.shields.io/badge/aiohttp-2C5BB4?style=for-the-badge&logo=aiohttp&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

#### Finance
![DART API](https://img.shields.io/badge/DART_API-003366?style=for-the-badge)
![KRX](https://img.shields.io/badge/KRX_API-FF0000?style=for-the-badge)
![XBRL](https://img.shields.io/badge/XBRL%2FArelle-006699?style=for-the-badge)
![TA--Lib](https://img.shields.io/badge/TA--Lib-228B22?style=for-the-badge)
![TradingView](https://img.shields.io/badge/TradingView-131622?style=for-the-badge&logo=tradingview&logoColor=white)

</div>

---

## Projects

> **금융 데이터 수집부터 자동 매매까지, 일관된 데이터 파이프라인 아키텍처**

```
  ┌─────────────────────── Data Collection Layer ───────────────────────┐
  │                                                                     │
  │  dart-fs-total ──────────► 재무제표 일괄 수집 (XBRL Bulk)            │
  │  dart-fs-xbrl ──────────► 재무제표 실시간 모니터링 (DART API)        │
  │  price-daily-collector ─► 일별 시세 수집 (멀티 소스)                 │
  │  price-realtime-collector► 실시간 시세 스트리밍 (WebSocket)          │
  │                                                                     │
  ├─────────────────────── Strategy Layer ──────────────────────────────┤
  │                                                                     │
  │  quant_buyback ─────────► 자사주 매입 공시 기반 자동 매매            │
  │                                                                     │
  ├─────────────────────── Storage Layer ───────────────────────────────┤
  │                                                                     │
  │  MySQL: price │ fin_db │ dart │ record                              │
  │                                                                     │
  └─────────────────────────────────────────────────────────────────────┘
```

<div align="center">

| Repository | Description |
|:---:|:---|
| [**dart-fs-xbrl**](https://github.com/ianman99/dart-fs-xbrl) | DART 공시 모니터링 → XBRL 파싱(Arelle) → 재무제표 DB 적재 |
| [**dart-fs-total**](https://github.com/ianman99/dart-fs-total) | DART 재무제표 일괄 다운로드 → 분류/정제 → MySQL 적재 파이프라인 |
| [**price-daily-collector**](https://github.com/ianman99/price-daily-collector) | KRX·Yahoo·Upbit·TradingView 일별 시세 수집 (9개 테이블) |
| [**price-realtime-collector**](https://github.com/ianman99/price-realtime-collector) | 네이버·KRX·TradingView·한경 실시간 시세 스트리밍 |
| [**quant_buyback**](https://github.com/ianman99/quant_buyback) | 자사주 매입 공시 감지 → 한국투자증권 API 자동 매매 봇 |

</div>

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats-sigma-five.vercel.app/api?username=ianman99&show_icons=true&theme=tokyonight&hide_border=true&locale=kr" alt="GitHub Stats" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ianman99&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

<img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=ianman99&layout=compact&theme=tokyonight&hide_border=true&locale=kr" alt="Top Languages" />

</div>

---

<div align="center">

<img src="https://komarev.com/ghpvc/?username=ianman99&style=flat-square&color=0891b2" alt="Profile Views"/>

</div>
