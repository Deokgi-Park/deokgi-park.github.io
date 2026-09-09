---
title: 핸디코어 CS팀 유지보수 이력
layout: collection
permalink: /portfolio/handycore-cs/
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
      <a href="#projects">유지보수 이력</a>
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
      <span class="eyebrow">Maintenance · 핸디코어 CS팀</span>
      <h1>
        운영 중인 그룹웨어의 장애를<br />
        <span class="hero-title-accent">끝까지 추적해 해결했습니다.</span>
      </h1>
      <p class="hero-copy">
        핸디코어 CS팀에서 대형 의료원, 공항, 공공기관 등 다수 고객사의 그룹웨어 유지보수를 담당했습니다.
        전자결재, 문서유통, 메일, 모바일 연동 등 핵심 업무 기능의 장애를 로그·덤프 기반으로 분석하고,
        백업 후 이중화 서버에 순차 반영하는 절차로 운영 변경의 안정성을 지켰습니다.
      </p>
      <div class="hero-actions">
        <a class="button button-primary" style="color: white;" href="#projects">유지보수 이력 보기</a>
        <a class="button button-secondary" href="/portfolio/">← 포트폴리오로 돌아가기</a>
      </div>
      <div class="team-switch">
        <a href="/portfolio/handycore-ps/">PS팀 · 프로젝트</a>
        <a class="is-active" href="/portfolio/handycore-cs/">CS팀 · 유지보수</a>
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
        <p class="section-description">운영 중인 그룹웨어를 지키기 위해 반복적으로 요구된 다섯 가지 역량입니다.</p>
      </div>
      <div class="skills-layout">
        <article class="skill-card">
          <span class="skill-number">01 · 전자결재 · 문서유통</span>
          <h3>결재·문서 기능 유지보수</h3>
          <p>전자결재, 결재 연동, 문서함/기록물철, 문서 열람권한, 전자문서 유통 기능의 유지보수와 개선을 담당했습니다.</p>
        </article>
        <article class="skill-card">
          <span class="skill-number">02 · 메일 인프라</span>
          <h3>메일 시스템 장애 분석</h3>
          <p>메일 발송 큐, IMAP/SMTP, 인코딩, 첨부파일, JVM 메모리·GC·스레드 이슈를 분석하고 대응했습니다.</p>
        </article>
        <article class="skill-card">
          <span class="skill-number">03 · 연동 장애 대응</span>
          <h3>FIDO · SAP · ERP 연동</h3>
          <p>생체인증, ERP 결재 연동, 조직도 시스템 등 외부 연동 구간의 오류를 분석하고 조치했습니다.</p>
        </article>
        <article class="skill-card">
          <span class="skill-number">04 · 이중화 운영 배포</span>
          <h3>백업 · 순차 반영 절차</h3>
          <p>운영 서버와 클라이언트에 모듈·설정·JSP 패치를 백업 후 이중화 서버에 순차 반영했습니다.</p>
        </article>
        <article class="skill-card">
          <span class="skill-number">05 · 보안 · 인증서 갱신</span>
          <h3>SSL · 라이선스 · 모바일 앱</h3>
          <p>모바일 앱 빌드, SSL 인증서 및 라이선스 교체 등 보안 인증의 연속성을 지원했습니다.</p>
        </article>
      </div>
    </div>
  </section>

  <section id="experience" class="experience">
    <div class="container">
      <div class="section-heading">
        <div>
          <span class="section-kicker">Maintenance</span>
          <h2 class="section-title">유지보수 이력</h2>
        </div>
        <p class="section-description">고객사별로 수행한 장애 분석, 운영 패치, 기능 개선 이력입니다.</p>
      </div>
      <div class="timeline">
        <article class="timeline-item">
          <div class="timeline-date">2024.07 — 2025.04</div>
          <div class="timeline-card">
            <h3>웹한글 기안기(docjini) 연동</h3>
            <div class="timeline-role">호출 인터페이스 · 이미지 서명 호환성 개선</div>
            <ul>
              <li>웹한글 기안기에서 docjini를 호출하는 JavaScript 인터페이스 수정·적용 지원</li>
              <li>웹한글 v1/v2 환경 간 호출 코드 호환성 이슈를 분석하고 수정 샘플 제공</li>
              <li>WMF·TIFF 이미지 전자서명 화질 저하 이슈를 분석해 운영 가이드 작성·전달</li>
            </ul>
          </div>
        </article>
        <article class="timeline-item">
          <div class="timeline-date">2023</div>
          <div class="timeline-card">
            <h3>한국발명진흥회</h3>
            <div class="timeline-role">그룹웨어 업그레이드 · 문서 기능 개선</div>
            <ul>
              <li>그룹웨어 버전 업그레이드 및 결재 연동·서식 관리 관련 유지보수 지원</li>
              <li>수신문서 발송정보 탭 조회 기능 개발 요청을 분석하고 기능 개선 지원</li>
            </ul>
          </div>
        </article>
        <article class="timeline-item">
          <div class="timeline-date">2022 — 2024</div>
          <div class="timeline-card">
            <h3>하나유비에스</h3>
            <div class="timeline-role">그룹웨어 서버 이전 · 라이선스 적용</div>
            <ul>
              <li>SmartOffice·Oracle 기반 그룹웨어 신규 서버 이전 작업 지원</li>
              <li>라이선스 데이터 확인 및 운영 라이선스 파일 적용 지원</li>
            </ul>
          </div>
        </article>
        <article class="timeline-item">
          <div class="timeline-date">2022.08 — 2024.02</div>
          <div class="timeline-card">
            <h3>한국체육산업개발</h3>
            <div class="timeline-role">전자문서 · 결재 · 릴레이 연동 유지보수</div>
            <ul>
              <li>기안문·협조문 서명 누락 등 전자결재 오류를 분석·수정해 결재 문서의 완결성 개선</li>
              <li>handydef.ini 설정을 변경해 완료문서 첨부 목록과 대장 목록의 조회 결과를 일치시킴</li>
              <li>유통문서 수신 불가·누락, 릴레이 모듈 오류를 점검·수정해 전자문서 유통 정상화 지원</li>
              <li>열람등급·후임자 열람권한·열람 로그 기능을 유지보수해 문서 접근통제 강화</li>
              <li>웹 취약점 조치, 502 오류 대응, 클라우드 전환 작업 지원</li>
            </ul>
          </div>
        </article>
        <article class="timeline-item">
          <div class="timeline-date">2022.07 — 2024.01</div>
          <div class="timeline-card">
            <h3>코리아e플랫폼</h3>
            <div class="timeline-role">구축 테스트 · 메일 장애 분석 · 성능 개선</div>
            <ul>
              <li>결재서식 수정 후 단위·시나리오 테스트, 스키마 업데이트 검증 수행</li>
              <li>메일 수신·열람·인코딩·첨부파일·대용량 처리 및 Outlook 연동 문제를 분석·패치 지원</li>
              <li>Java OutOfMemoryError, 힙 덤프, Tomcat CPU 점유율 등 복합 장애 분석</li>
              <li>메일 엔진 GC를 Parallel GC에서 G1GC로 변경, Hedwig 엔진 및 IMAP/SMTP 분리 작업 지원</li>
              <li>SSL 인증서·라이선스 교체, 모바일 iOS 앱 업그레이드, 모니터링 셸 설치 지원</li>
            </ul>
          </div>
        </article>
        <article class="timeline-item">
          <div class="timeline-date">2022.07 — 2024.03</div>
          <div class="timeline-card">
            <h3>연세의료원</h3>
            <div class="timeline-role">차세대 그룹웨어 구축 · 유지보수</div>
            <ul>
              <li>모듈·설정·JSP 패치를 운영 서버·클라이언트에 반영, 백업 후 이중화 서버 순차 배포 절차 적용</li>
              <li>결재 연동, 반송대장, 조직도 연동, 태그·사용자 검색 등 고객 요청 기능 개선 관리</li>
              <li>모바일 SLO 연동, 모바일 앱 빌드, 모바일 라이선스·SSL 인증서 교체 지원</li>
              <li>FIDO 연동 및 추가 개발 요청을 작업계획서·회의록·장애보고서로 관리</li>
              <li>AppIron, 모바일 결재 불가, 세션 관련 장애를 로그·트레이스 기반으로 분석</li>
            </ul>
          </div>
        </article>
        <article class="timeline-item">
          <div class="timeline-date">2022.01 — 2023.04</div>
          <div class="timeline-card">
            <h3>인천공항운영서비스</h3>
            <div class="timeline-role">결재 · ERP 연동 · 조직 문서 유지보수</div>
            <ul>
              <li>결재 오류, 대결·전결, 결재 등급, 문서 열람권한 관련 설정을 분석·변경 지원</li>
              <li>ERP 결재 연동 오류, 지출결의서 수신처 오류, 서식 변경 등 처리</li>
              <li>부서 코드·직제 변경을 반영하고 그룹주소록 Excel 다운로드 오류 수정</li>
              <li>메일 발송 큐 정체, 대용량 첨부 발송 불가 등 메일·게시판 이슈 대응</li>
            </ul>
          </div>
        </article>
        <article class="timeline-item">
          <div class="timeline-date">2020.08 — 2023.11</div>
          <div class="timeline-card">
            <h3>인천국제공항보안</h3>
            <div class="timeline-role">그룹웨어 구축 · 유지보수</div>
            <ul>
              <li>착수부터 분석·설계·구축·테스트·이행까지 단계별 산출물과 운영자 매뉴얼 관리</li>
              <li>연동문서 오류 DB 정리, 발송 불가·미접수 문서 요청 대응</li>
              <li>서식 변경, 브라우저 호환성, 권한 설정 등 사용자 업무 환경 개선</li>
              <li>Tomcat 8.x/DBCP2 환경에서 Oracle CLOB ClassCastException을 분석해 해결 가이드 제공</li>
            </ul>
          </div>
        </article>
        <article class="timeline-item">
          <div class="timeline-date">상시</div>
          <div class="timeline-card">
            <h3>공통 기술 지원</h3>
            <div class="timeline-role">오류 분석 · 장애 대응 사례</div>
            <ul>
              <li>SAP 결재 연동의 중간 결재·반려 처리, 전표 중복 생성 이슈 분석 및 동기화 검토</li>
              <li>WebtoB CPU 부하와 Client IP 처리 모듈 문제를 분석해 패치 적용 방안 검토</li>
              <li>SMTP 타임아웃, 메일 포트 필터링, 인코딩 오류 등 메일 인프라 장애 전반 대응</li>
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
          <div>대형 의료원부터 공항 운영사까지, <em>백업과 이중화 절차</em>로
          운영 변경의 장애 위험을 낮춰 왔습니다.</div>
        </div>
        <div class="panel principles">
          <div class="principle">
            <strong>안정적 운영 배포</strong>
            <p>이중화 서버를 포함한 운영 배포에 백업·순차 반영·사후 점검 절차를 적용해 변경 작업의 장애 위험을 최소화했습니다.</p>
          </div>
          <div class="principle">
            <strong>성능 · 장애 분석</strong>
            <p>메일 시스템의 메모리·GC·스레드·IMAP/SMTP 이슈를 로그와 덤프 자료 기반으로 분석하고 운영 설정 개선을 지원했습니다.</p>
          </div>
          <div class="principle">
            <strong>업무 기능 개선</strong>
            <p>결재서식, 문서 조회, 열람권한, 조직정보, ERP 결재 연동 등 업무 규정과 직결된 기능을 수정·검증했습니다.</p>
          </div>
          <div class="principle">
            <strong>보안 · 인증 연속성</strong>
            <p>SSL 인증서, 라이선스, 모바일 앱, 모니터링 셸 교체·설치를 수행해 보안 인증과 운영 관제의 연속성을 확보했습니다.</p>
          </div>
          <div class="principle">
            <strong>협업 · 이력 관리</strong>
            <p>작업계획서, 장애보고서, 회의록, 테스트 자료로 요청부터 결과까지 관리해 개발·운영·고객 간 이력을 추적했습니다.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section>
    <div class="container">
      <div class="contact-box">
        <div>
          <h2>구축 프로젝트 이력도 궁금하신가요?</h2>
          <p>PS팀에서 수행한 다기관 표준화, 컨테이너 배포, 전환 프로젝트는 별도 페이지에서 확인하실 수 있습니다.</p>
        </div>
        <a class="button" href="/portfolio/handycore-ps/">PS팀 이력 보기 ↗</a>
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
