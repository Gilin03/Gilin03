<div align="center">

# 👋 Hi, I'm Taebin

### Security · Network · Backend · Automation

보안과 네트워크를 중심으로
**직접 구현하고, 테스트하고, 문제를 해결하며 배우고 있습니다.**

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-Gilin03-181717?style=for-the-badge\&logo=github)](https://github.com/Gilin03)

</div>

---

## 👨‍💻 About Me

보안 기능을 직접 구현하고 실제 동작을 검증하는 과정에 관심이 있습니다.

단순히 기능을 만드는 것에서 끝내지 않고
**인증 · 접근 제어 · 로그 · 자동화 · 네트워크**가 서로 어떻게 연결되는지 이해하는 것을 목표로 공부하고 있습니다.

최근에는 **WebAuthn 패스키 인증**, **로그인 보안 이벤트 자동화**,
**REST API와 데이터베이스를 활용한 보안 기능 구현** 등을 진행하고 있습니다.

```text
Interested in
├─ 🛡️ Security Monitoring
├─ 🌐 Network Security
├─ 🔐 Authentication & Access Control
├─ ⚙️ Security Automation
└─ 💻 Backend Development
```

---

## 🛠 Tech Stack

### Security & Network

<p>
  <img src="https://img.shields.io/badge/WebAuthn-3423A6?style=flat-square&logo=webauthn&logoColor=white">
  <img src="https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
</p>

### Backend & Automation

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white">
  <img src="https://img.shields.io/badge/REST_API-009688?style=flat-square&logo=fastapi&logoColor=white">
</p>

### Frontend

<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
</p>

### Database & Infrastructure

<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
</p>

### Tools

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white">
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white">
</p>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔐 WebAuthn Passkey Authentication

비밀번호 대신 **WebAuthn 패스키**를 이용해
비공개 영역에 접근하는 인증 시스템입니다.

**Key Points**

* WebAuthn 등록 / 로그인
* Challenge 기반 인증
* 공개키 기반 서명 검증
* 패스키 추가 / 삭제
* 인증 사용자 전용 데이터
* 세션 관리
* Supabase Edge Function

**Stack**

`React` `Vite` `WebAuthn`
`Supabase` `PostgreSQL`

➡️ [Repository](https://github.com/Gilin03/webauthn-passkey-auth)

</td>
<td width="50%" valign="top">

### 🚨 Login Security Automation

로그인 보안 이벤트를 받아 위험도를 판정하고
대응 과정을 자동화한 프로젝트입니다.

**Flow**

```text
Python
   ↓
n8n Webhook
   ↓
Security Decision
   ↓
Slack / Discord / Telegram
   ↓
Flask REST API
   ↓
MySQL
   ↓
Security Dashboard
```

**Stack**

`Python` `n8n` `Flask`
`MySQL` `Docker`

➡️ [Repository](https://github.com/Gilin03/loginbot)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 📊 Exchange Rate Dashboard

외부 환율 API 데이터를 조회하고
기간별 환율 변화를 시각화한 웹 프로젝트입니다.

**Key Points**

* 외부 API 연동
* 환율 데이터 표시
* 기간별 데이터 조회
* 차트 시각화
* API 장애 상황 테스트

**Stack**

`React` `Vite` `Recharts`
`Supabase`

➡️ [Repository](https://github.com/Gilin03/exchange-rate-dashboard)

</td>
<td width="50%" valign="top">

### 🎮 RUN! 30

React와 Canvas를 활용한
**30초 생존형 러너 게임**입니다.

**Key Points**

* Canvas 기반 게임 루프
* 점프 / 숙이기 조작
* 충돌 판정
* 난이도 시스템
* 플레이 기록 저장
* 화면 효과 및 피드백

**Stack**

`React` `JavaScript` `Canvas API`

➡️ [Repository](https://github.com/Gilin03/run30-canvas-runner)

</td>
</tr>
</table>

---

## 🔎 What I'm Learning

현재는 기능 구현 경험을 **보안 관점의 문제 해결 능력**으로 확장하고 있습니다.

```text
Security Monitoring
      │
      ├─ Log Analysis
      ├─ Security Event Detection
      └─ Incident Response Automation

Network Security
      │
      ├─ TCP/IP
      ├─ VLAN / Routing
      ├─ ACL
      └─ Network Troubleshooting

Application Security
      │
      ├─ Authentication
      ├─ Authorization
      ├─ WebAuthn
      └─ Access Control

Automation
      │
      ├─ Python
      ├─ n8n
      └─ REST API
```

---

## 🎯 Current Focus

> **Security Monitoring · Network Security · Security Automation**

로그를 단순히 확인하는 것에서 끝나는 것이 아니라,

**이벤트 발생 → 탐지 → 판단 → 알림 → 대응 → 기록**

으로 이어지는 전체 흐름을 직접 구현하며 공부하고 있습니다.

---

## 📈 GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Gilin03&show_icons=true&hide_border=true&hide_title=true" height="160">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gilin03&layout=compact&hide_border=true" height="160">

</div>

---

<div align="center">

### 🔐 Build · Test · Analyze · Improve

기능이 **왜 동작하는지 이해하고**,
문제가 생기면 **직접 원인을 찾아 해결할 수 있는 사람**을 목표로 하고 있습니다.

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Gilin03\&style=flat-square)

</div>
