---
title: 핸디코어 PS팀 프로젝트 이력
layout: collection
permalink: /portfolio/handycore-ps/
classes: wide
header:
  show_title: false
author_profile: false
date: 2026-09-02
---

<style>
    :root {
      --accent: #ff0084;
      --accent-soft: #141010;
      --ink: #17171c;
      --muted: #696973;
      --line: #e8e8ee;
      --surface: #ffffff;
      --surface-alt: #f7f7fa;
      --max-width: 1180px;
      --radius-lg: 28px;
      --radius-md: 18px;
      --shadow: 0 22px 60px rgba(25, 25, 35, 0.08);
    }

    *,
    *::before,
    *::after {
      box-sizing: border-box;
      word-break: keep-all;
      overflow-wrap: normal;
    }
    .sidebar {
      text-align: center;
      z-index: 1;
    }
    body {
      margin: 0;
      font-family: Pretendard, "Noto Sans KR", -apple-system, BlinkMacSystemFont,
        "Segoe UI", sans-serif;
      line-height: 1.65;
    }

    a {
      text-decoration: none;
    }

    img, svg {
      display: block;
      max-width: 100%;
    }

    section#about strong {
      color: black;
    }
    section#skills h3 {
      color: black;
    }

    .container {
      width: min(calc(100% - 40px), var(--max-width));
      margin-inline: auto;
    }

    .site-header {
      position: sticky;
      top: 0;
      z-index: 30;
      background: transparent;
      border-bottom: 1px solid transparent;
      transition: border-color 0.28s ease, box-shadow 0.28s ease;
    }

    .site-header::before {
      content: "";
      position: absolute;
      inset: 0;
      background: rgba(20, 16, 16, 0.82);
      backdrop-filter: blur(18px);
      opacity: 0;
      transition: opacity 0.28s ease;
      pointer-events: none;
      z-index: 0;
    }

    .site-header.is-solid {
      border-bottom-color: rgba(232, 232, 238, 0.85);
      box-shadow: 0 10px 30px rgba(25, 25, 35, 0.08);
    }

    .site-header.is-solid::before {
      opacity: 1;
    }

    .site-header .container {
      position: relative;
      z-index: 1;
    }

    .nav {
      min-height: 72px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 24px;
    }

    .brand {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      font-weight: 900;
      letter-spacing: -0.03em;
    }

    .brand-mark {
      width: 38px;
      height: 38px;
      color: var(--accent);
    }

    .nav-links {
      display: flex;
      align-items: center;
      gap: 24px;
      font-size: 14px;
      font-weight: 700;
      color: var(--muted);
    }

    .nav-download-btn {
      width: 34px;
      height: 34px;
      min-height: 34px;
      padding: 0;
      border-radius: 999px;
      border: 1px solid rgba(255, 0, 132, 0.38);
      background: rgba(255, 0, 132, 0.08);
      color: var(--accent);
      display: inline-flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      transition: background 0.2s ease, border-color 0.2s ease, color 0.2s ease;
    }

    .nav-download-btn svg {
      width: 16px;
      height: 16px;
      stroke: currentColor;
    }

    .visually-hidden {
      position: absolute;
      width: 1px;
      height: 1px;
      padding: 0;
      margin: -1px;
      overflow: hidden;
      clip: rect(0, 0, 0, 0);
      border: 0;
      white-space: nowrap;
    }

    .nav-download-btn:hover {
      background: rgba(255, 0, 132, 0.16);
      border-color: rgba(255, 0, 132, 0.65);
      color: #ff2f9f;
    }

    .site-header.is-solid .nav-download-btn {
      background: rgba(255, 0, 132, 0.2);
      border-color: rgba(255, 0, 132, 0.72);
      color: #ff5ab1;
    }

    .nav-links a:hover {
      color: var(--accent);
    }

    .hero {
      display: grid;
      align-items: center;
      padding: 84px 0 40px;
    }

    .eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      padding: 8px 13px;
      border-radius: 999px;
      background: var(--accent-soft);
      color: var(--accent);
      font-size: 13px;
      font-weight: 800;
      letter-spacing: 0.08em;
      text-transform: uppercase;
    }

    .eyebrow::before {
      content: "";
      width: 7px;
      height: 7px;
      border-radius: 50%;
      background: var(--accent);
      box-shadow: 0 0 0 5px rgba(255, 0, 132, 0.12);
    }

    h1 {
      margin: 24px 0 20px;
      font-size: clamp(38px, 6vw, 68px);
      line-height: 1.08;
      letter-spacing: -0.06em;
    }

    .hero-title-accent {
      color: var(--accent);
    }

    .hero-copy {
      margin: 0;
      max-width: 760px;
      font-size: clamp(17px, 1.6vw, 20px);
      color: rgba(23, 23, 28, 0.62);
      letter-spacing: -0.01em;
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 34px;
    }

    .button {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      min-height: 48px;
      padding: 0 20px;
      border: 0;
      border-radius: 14px;
      font-weight: 800;
      font-size: 16px;
      line-height: 1;
      cursor: pointer;
      transition: 0.2s ease;
    }

    .button-primary {
      color: white;
      background: var(--accent);
      box-shadow: 0 12px 30px rgba(255, 0, 132, 0.24);
    }

    .button-primary:hover {
      transform: translateY(-2px);
      box-shadow: 0 16px 36px rgba(255, 0, 132, 0.3);
    }

    .button-secondary {
      border: 1px solid var(--line);
      background: white;
      color: var(--ink);
    }

    .button-secondary:hover {
      border-color: var(--accent);
      color: var(--accent);
    }

    section {
      padding: 90px 0;
    }

    .section-heading {
      display: grid;
      grid-template-columns: 0.6fr 1fr;
      gap: 48px;
      align-items: end;
      margin-bottom: 46px;
    }

    .section-kicker {
      color: var(--accent);
      font-size: 13px;
      font-weight: 900;
      letter-spacing: 0.13em;
      text-transform: uppercase;
    }

    .section-title {
      margin: 8px 0 0;
      font-size: clamp(30px, 4.4vw, 50px);
      line-height: 1.1;
      letter-spacing: -0.05em;
    }

    .section-description {
      margin: 0;
      color: var(--muted);
      font-size: 17px;
    }

    .about-grid {
      display: grid;
      grid-template-columns: 1.2fr 0.8fr;
      gap: 24px;
    }

    .panel {
      border: 1px solid var(--line);
      border-radius: var(--radius-lg);
      background: rgba(255, 255, 255, 0.9);
      box-shadow: 0 14px 38px rgba(25, 25, 35, 0.05);
    }

    .statement {
      padding: 42px;
      font-size: clamp(20px, 2.6vw, 28px);
      line-height: 1.45;
      font-weight: 800;
      letter-spacing: -0.03em;
    }

    .statement em {
      color: var(--accent);
      font-style: normal;
    }

    .principles {
      display: grid;
      gap: 1px;
      overflow: hidden;
    }

    .principle {
      padding: 22px 26px;
      background: white;
    }

    .principle strong {
      display: block;
      margin-bottom: 6px;
      font-size: 17px;
    }

    .principle p {
      margin: 0;
      color: var(--muted);
    }

    .skills-layout {
      display: grid;
      grid-template-columns: repeat(12, 1fr);
      gap: 18px;
    }

    .skill-card {
      min-height: 150px;
      padding: 26px;
      border: 1px solid var(--line);
      border-radius: var(--radius-md);
      background: white;
      transition: 0.25s ease;
    }

    .skill-card:hover {
      transform: translateY(-5px);
      border-color: rgba(255, 0, 132, 0.35);
      box-shadow: 0 18px 42px rgba(25, 25, 35, 0.08);
    }

    .skill-card:nth-child(1),
    .skill-card:nth-child(2) {
      grid-column: span 6;
    }

    .skill-card:nth-child(n+3) {
      grid-column: span 4;
    }

    .skill-number {
      color: var(--accent);
      font-size: 12px;
      font-weight: 900;
      letter-spacing: 0.12em;
    }

    .skill-card h3 {
      margin: 16px 0 10px;
      font-size: 21px;
      letter-spacing: -0.03em;
    }

    .skill-card p {
      margin: 0;
      color: var(--muted);
    }

    .experience {
      background: #15151a;
      color: white;
    }

    .experience .section-description {
      color: #a9a9b4;
    }

    .timeline {
      position: relative;
      display: grid;
      gap: 22px;
    }

    .timeline::before {
      content: "";
      position: absolute;
      left: 138px;
      top: 8px;
      bottom: 8px;
      width: 1px;
      background: #34343d;
    }

    .timeline-item {
      display: grid;
      grid-template-columns: 110px 1fr;
      gap: 56px;
      position: relative;
    }

    .timeline-item::before {
      content: "";
      position: absolute;
      left: 132px;
      top: 34px;
      width: 13px;
      height: 13px;
      border-radius: 50%;
      background: var(--accent);
      box-shadow: 0 0 0 6px rgba(255, 0, 132, 0.14);
    }

    .timeline-date {
      padding-top: 26px;
      font-size: 13px;
      color: #a9a9b4;
      font-weight: 800;
    }

    .timeline-card {
      padding: 28px 30px;
      border: 1px solid #303039;
      border-radius: 20px;
      background: #1d1d23;
    }

    .timeline-card h3 {
      margin: 0;
      font-size: 22px;
    }

    .timeline-role {
      margin: 5px 0 18px;
      color: var(--accent);
      font-weight: 800;
      font-size: 14px;
    }

    .timeline-card ul {
      margin: 0;
      padding-left: 18px;
      color: #cacad2;
      font-size: 14.5px;
    }

    .timeline-card li + li {
      margin-top: 7px;
    }

    .contact-box {
      padding: 58px;
      border-radius: 34px;
      background: var(--accent);
      color: white;
      display: grid;
      grid-template-columns: 1fr auto;
      gap: 32px;
      align-items: center;
      box-shadow: 0 24px 65px rgba(255, 0, 132, 0.25);
    }

    .contact-box h2 {
      margin: 0 0 10px;
      font-size: clamp(28px, 4vw, 42px);
      letter-spacing: -0.04em;
    }

    .contact-box p {
      margin: 0;
      max-width: 650px;
      color: rgba(255, 255, 255, 0.86);
    }

    .contact-box .button {
      background: white;
      color: var(--accent);
      white-space: nowrap;
    }

    footer {
      padding: 34px 0 50px;
      color: var(--muted);
      font-size: 14px;
    }

    .team-switch {
      display: inline-flex;
      gap: 8px;
      margin-top: 28px;
      padding: 6px;
      border-radius: 999px;
      background: var(--surface-alt);
    }

    .team-switch a {
      padding: 9px 18px;
      border-radius: 999px;
      font-size: 13px;
      font-weight: 800;
      color: var(--muted);
    }

    .team-switch a.is-active {
      background: var(--ink);
      color: white;
    }

    @media (max-width: 1024px) {
      .archive {
        margin-top: 2.5em;
      }
    }

    @media (max-width: 900px) {
      .about-grid,
      .section-heading,
      .contact-box {
        grid-template-columns: 1fr;
        gap: 24px;
      }

      .nav-links {
        gap: 12px;
      }

      .skill-card,
      .skill-card:nth-child(1),
      .skill-card:nth-child(2),
      .skill-card:nth-child(n+3) {
        grid-column: span 6;
      }
    }

    @media (max-width: 640px) {
      .container {
        width: min(calc(100% - 24px), var(--max-width));
      }

      section {
        padding: 64px 0;
      }

      .hero-actions {
        flex-direction: column;
      }

      .button {
        width: 100%;
      }

      .skill-card,
      .skill-card:nth-child(1),
      .skill-card:nth-child(2),
      .skill-card:nth-child(n+3) {
        grid-column: 1 / -1;
      }

      .timeline::before,
      .timeline-item::before {
        display: none;
      }

      .timeline-item {
        grid-template-columns: 1fr;
        gap: 10px;
      }

      .timeline-date {
        padding-top: 0;
      }

      .contact-box {
        padding: 34px 24px;
      }
    }

    @media print {
      .site-header,
      .hero-actions,
      .team-switch {
        display: none;
      }

      .sidebar {
        display: none !important;
      }

      @page {
        size: A4;
        margin: 14mm;
      }

      html,
      body {
        background: white;
        color: #111 !important;
        -webkit-print-color-adjust: exact;
        print-color-adjust: exact;
      }

      .hero-copy,
      .section-description,
      .timeline-date,
      .timeline-role,
      .principle p,
      .skill-card p {
        color: #222 !important;
      }

      .hero-title-accent,
      .section-kicker {
        color: #000 !important;
      }

      .experience,
      .timeline-card,
      .panel,
      .skill-card {
        background: #fff !important;
        border-color: #cfcfd8 !important;
      }

      .timeline::before,
      .timeline-item::before {
        display: none !important;
      }

      section {
        padding: 30px 0;
        break-inside: avoid;
      }

      .panel,
      .skill-card,
      .timeline-card {
        break-inside: avoid;
        box-shadow: none;
      }

      a {
        color: #111 !important;
      }
    }
</style>

<header class="site-header">
  <div class="container nav">
    <a class="brand" href="/portfolio/" aria-label="포트폴리오로 이동">
      <svg class="brand-mark" viewBox="0 0 120 120" aria-hidden="true">
        <path d="M20 63c-9-3-14-11-12-17 2-5 7-6 14-2l8 4c2-24 18-40 40-42 22-2 42 13 46 35 3 17-3 31-15 43 18 3 31 1 39-8 5-6 9-10 12-9 6 2 9 15 7 27-5 31-31 48-71 48-31 0-58-12-68-31-8-15-5-29 10-45l-10-3Z"
          fill="none" stroke="currentColor" stroke-width="6" stroke-linecap="round" stroke-linejoin="round" />
        <circle cx="58" cy="38" r="5" fill="currentColor" />
        <path d="M31 48c9 6 18 7 29 2" fill="none" stroke="currentColor" stroke-width="5" stroke-linecap="round" />
      </svg>
      <span>Portfolio</span>
    </a>
    <nav class="nav-links" aria-label="주요 메뉴">
      <a href="#competency">핵심 역량</a>
      <a href="#projects">프로젝트 이력</a>
      <a href="#outcome">종합 성과</a>
      <button class="nav-download-btn" type="button" id="download-pdf-button" aria-label="PDF 다운로드" title="PDF 다운로드">
        <svg viewBox="0 0 24 24" fill="none" aria-hidden="true">
          <path d="M12 4v10" stroke-width="2" stroke-linecap="round"/>
          <path d="M8 10l4 4 4-4" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M5 19h14" stroke-width="2" stroke-linecap="round"/>
        </svg>
        <span class="visually-hidden">PDF 다운로드</span>
      </button>
    </nav>
  </div>
</header>

<main id="top">
  <section class="hero">
    <div class="container">
      <span class="eyebrow">Project · 핸디코어 PS팀</span>
      <h1>
        신규 그룹웨어 구축과 전환을<br />
        <span class="hero-title-accent">설계부터 운영 반영까지 수행했습니다.</span>
      </h1>
      <p class="hero-copy">
        핸디코어 PS팀에서 다기관 그룹웨어 표준화, DB 마이그레이션, 컨테이너 배포 환경 구성,
        신규 전자결재시스템 전환, 데이터 이관 등 신규 구축·전환 프로젝트를 수행했습니다.
        기관별 환경 정보를 정리하고 표준 모듈을 적용해 다수 기관에 반복 가능한 구축 절차를 만들었습니다.
      </p>
      <div class="hero-actions">
        <a class="button button-primary" style="color: white;" href="#projects">프로젝트 이력 보기</a>
        <a class="button button-secondary" href="/portfolio/">← 포트폴리오로 돌아가기</a>
      </div>
      <div class="team-switch">
        <a class="is-active" href="/portfolio/handycore-ps/">PS팀 · 프로젝트</a>
        <a href="/portfolio/handycore-cs/">CS팀 · 유지보수</a>
      </div>
    </div>
  </section>

  <section id="skills">
    <div class="container">
      <div class="section-heading">
        <div>
          <span class="section-kicker">Competency</span>
          <h2 class="section-title">핵심 역량</h2>
        </div>
        <p class="section-description">신규 구축·전환 프로젝트에서 반복적으로 요구된 다섯 가지 역량입니다.</p>
      </div>
      <div class="skills-layout">
        <article class="skill-card">
          <span class="skill-number">01 · DB 마이그레이션</span>
          <h3>Oracle → Tibero 전환</h3>
          <p>테이블·인덱스·데이터 타입 변환과 제약조건 충돌 분석을 통해 DB 전환 정합성을 검증했습니다.</p>
        </article>
        <article class="skill-card">
          <span class="skill-number">02 · 컨테이너 배포</span>
          <h3>Docker · Kubernetes 환경 구성</h3>
          <p>그룹웨어 이미지, Dockerfile, Kubernetes YAML/ConfigMap을 구성해 반복 가능한 배포 환경을 마련했습니다.</p>
        </article>
        <article class="skill-card">
          <span class="skill-number">03 · 인증 연동</span>
          <h3>OTP · 외부 시스템 연동</h3>
          <p>OTP 인증 모듈 개발과 외부 라이선스 서버 연동 등 접근 보안 기능 구현을 지원했습니다.</p>
        </article>
        <article class="skill-card">
          <span class="skill-number">04 · 데이터 이관</span>
          <h3>조직 · 결재문서 이관</h3>
          <p>조직·사용자 데이터 매핑과 결재문서 이관 SQL·검증 절차를 관리해 데이터 정합성을 확보했습니다.</p>
        </article>
        <article class="skill-card">
          <span class="skill-number">05 · 전환 프로젝트 관리</span>
          <h3>시나리오 수립 · 검증</h3>
          <p>신규 시스템 전환 시나리오와 버전별 업그레이드 절차를 수립하고 순차 적용을 검증했습니다.</p>
        </article>
      </div>
    </div>
  </section>

  <section id="experience" class="experience">
    <div class="container">
      <div class="section-heading">
        <div>
          <span class="section-kicker">Projects</span>
          <h2 class="section-title">프로젝트 이력</h2>
        </div>
        <p class="section-description">다기관·고객사를 대상으로 수행한 신규 구축, 전환, 마이그레이션 프로젝트입니다.</p>
      </div>
      <div class="timeline">
        <article class="timeline-item">
          <div class="timeline-date">2024.10 — 2025</div>
          <div class="timeline-card">
            <h3>제주 테크노파크 외 다기관</h3>
            <div class="timeline-role">그룹웨어 표준화 · DB 마이그레이션</div>
            <ul>
              <li>Oracle → Tibero DB 전환을 위한 테이블·인덱스·데이터 타입 변환 및 마이그레이션 절차 검토·수행</li>
              <li>전자결재·메일 관련 테이블의 제약조건 충돌과 데이터 정합성 이슈 분석, 이관 오류 조치 지원</li>
              <li>기관별 사전 인터뷰, 환경 정보, 부서 코드·네트워크 자료를 관리해 다기관 표준화 설계 기반 마련</li>
              <li>HSO 표준 모듈과 KT 클라우드 POC 환경의 기관별 적용 지원</li>
            </ul>
          </div>
        </article>
        <article class="timeline-item">
          <div class="timeline-date">2025</div>
          <div class="timeline-card">
            <h3>가덕도 프로젝트</h3>
            <div class="timeline-role">OTP 인증 · Kubernetes 배포 환경</div>
            <ul>
              <li>OTP 인증 모듈(hip_otp) 및 외부 연동 자료를 기반으로 인증 기능 개발·연동 지원</li>
              <li>Tomcat 그룹웨어 이미지와 Kubernetes 배포 자료를 구성·관리하고 컨테이너 환경 적용 지원</li>
              <li>Relay Agent 라이선스 체크 오류 로그를 분석하고 외부 라이선스 서버 연동 이슈 대응</li>
              <li>그룹웨어 부서 코드 트리 구조 변경 작업 지원</li>
            </ul>
          </div>
        </article>
        <article class="timeline-item">
          <div class="timeline-date">2025.06</div>
          <div class="timeline-card">
            <h3>한국장애인고용공단</h3>
            <div class="timeline-role">신규 전자결재시스템 전환</div>
            <ul>
              <li>신규 전자결재시스템 전환을 위한 상세 시나리오 수립 및 검증 지원</li>
              <li>버전별(v8.3.13~v8.3.20) DB 업그레이드 SQL 준비·검토 및 순차 적용 지원</li>
              <li>고객사 커스터마이징 요구사항을 분석해 전환 환경에 반영 지원</li>
            </ul>
          </div>
        </article>
        <article class="timeline-item">
          <div class="timeline-date">2025.07</div>
          <div class="timeline-card">
            <h3>더존 → 핸디 그룹웨어 이관</h3>
            <div class="timeline-role">조직 · 사용자 · 결재문서 데이터 이관</div>
            <ul>
              <li>더존 MariaDB의 사용자·부서·직위·직책 데이터와 결재 완료문서를 핸디 TiberoDB로 이관하는 절차 구성</li>
              <li>조직·사용자 데이터 매핑 및 부서 코드 표준화 작업 지원</li>
              <li>결재문서 이관 SQL과 검증 절차를 관리해 데이터 정합성 확보 지원</li>
            </ul>
          </div>
        </article>
        <article class="timeline-item">
          <div class="timeline-date">2025.06 — 07</div>
          <div class="timeline-card">
            <h3>새마을금고</h3>
            <div class="timeline-role">업무형 게시판 · 업무지원플랫폼 설계</div>
            <ul>
              <li>업무형 게시판의 테이블 정의 및 프로그램 사양 설계 자료 작성·검토</li>
              <li>업무지원플랫폼 설치 가이드 및 제안 자료 관리</li>
            </ul>
          </div>
        </article>
        <article class="timeline-item">
          <div class="timeline-date">2024 — 2025</div>
          <div class="timeline-card">
            <h3>HSO 그룹웨어</h3>
            <div class="timeline-role">Docker · Kubernetes 컨테이너화</div>
            <ul>
              <li>설치 SQL·모듈·설정 파일을 컨테이너 환경에 적용하기 위한 배포 자료 구성</li>
              <li>Dockerfile과 Kubernetes 배포 YAML, ConfigMap 기반 환경설정 관리 자료 작성·관리</li>
              <li>오프라인 패키지 구성으로 망분리 환경의 설치·배포 가능성 확보 지원</li>
            </ul>
          </div>
        </article>
      </div>
    </div>
  </section>

  <section id="about">
    <div class="container">
      <div class="section-heading">
        <div>
          <span class="section-kicker">Outcome</span>
          <h2 class="section-title">종합 성과</h2>
        </div>
        <p class="section-description"></p>
      </div>
      <div class="about-grid">
        <div class="panel statement" style="display: flex; align-items: center; color: black;">
          <div>다기관 표준화부터 컨테이너 배포까지, <em>반복 가능한 구축 절차</em>로
          신규 프로젝트의 안정적인 시작을 만들었습니다.</div>
        </div>
        <div class="panel principles">
          <div class="principle">
            <strong>다기관 표준화 설계</strong>
            <p>기관별 환경 정보와 사전 인터뷰를 정리해 표준 모듈을 여러 기관에 반복 적용할 수 있는 설계 기반을 마련했습니다.</p>
          </div>
          <div class="principle">
            <strong>DB 전환 정합성 확보</strong>
            <p>Oracle → Tibero 전환에서 제약조건 충돌과 데이터 정합성 이슈를 분석해 이관 오류 대응 기반을 확보했습니다.</p>
          </div>
          <div class="principle">
            <strong>컨테이너 배포 환경 구성</strong>
            <p>Docker·Kubernetes 기반 배포 자료를 구성하고 오프라인 패키지까지 준비해 망분리 환경 설치 가능성을 확보했습니다.</p>
          </div>
          <div class="principle">
            <strong>데이터 이관 검증 체계</strong>
            <p>조직·사용자·결재문서 이관 절차와 검증 SQL을 관리해 신규 시스템 전환의 데이터 정합성을 지켰습니다.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section>
    <div class="container">
      <div class="contact-box">
        <div>
          <h2>유지보수 이력도 궁금하신가요?</h2>
          <p>CS팀에서 수행한 장애 분석과 운영 유지보수 이력은 별도 페이지에서 확인하실 수 있습니다.</p>
        </div>
        <a class="button" href="/portfolio/handycore-cs/">CS팀 이력 보기 ↗</a>
      </div>
    </div>
  </section>
</main>

<script>
  (function () {
    var header = document.querySelector('.site-header');
    var main = document.querySelector('main#top');
    var downloadPdfButton = document.getElementById('download-pdf-button');
    if (!header) return;

    if (downloadPdfButton) {
      downloadPdfButton.addEventListener('click', function () {
        window.print();
      });
    }

    var ticking = false;

    function updateHeaderState() {
      var shouldBeSolid = main ? main.getBoundingClientRect().top <= 0 : window.scrollY > 0;
      header.classList.toggle('is-solid', shouldBeSolid);
      ticking = false;
    }

    updateHeaderState();

    window.addEventListener('scroll', function () {
      if (ticking) return;
      ticking = true;
      window.requestAnimationFrame(updateHeaderState);
    }, { passive: true });
  })();
</script>
