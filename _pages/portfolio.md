---
title: Portfolio
layout: collection
permalink: /portfolio/
entries_layout: grid
classes: wide
header:
  show_title: false
sidebar:
  - text: |
      <aside data-dc-tpl="7" style="border: 1px solid rgba(255, 255, 255, 0.08); border-radius: 16px; background: rgb(15, 16, 19); overflow: hidden; z-index: 2; margin-top: 50px;">
        <img data-dc-tpl="8" src="/assets/images/profile/myReal.jpg" alt="박덕기 프로필 사진" style="width: 100%; height: auto; display: block; border-bottom: 1px solid rgba(255, 255, 255, 0.08);">
        <div data-dc-tpl="9" style="padding: 22px 22px 26px;">
          <div data-dc-tpl="10" style="font-family: &quot;JetBrains Mono&quot;, monospace; font-size: 12px; letter-spacing: 0.2em; color: rgb(255, 0, 132); margin-bottom: 18px;">PROFILE</div>
          <div data-dc-tpl="11" style="display: flex; flex-direction: column; gap: 14px;">
            <div data-dc-tpl="12" style="display: flex; justify-content: space-between; font-size: 13.5px; padding-bottom: 14px; border-bottom: 1px solid rgba(255, 255, 255, 0.08);">
              <span data-dc-tpl="13" style="color: rgb(74, 81, 88);">이름</span><span data-dc-tpl="14" style="color: rgb(223, 227, 230); font-weight: 600;">박덕기</span>
            </div>
            <div data-dc-tpl="15" style="display: flex; justify-content: space-between; font-size: 13.5px; padding-bottom: 14px; border-bottom: 1px solid rgba(255, 255, 255, 0.08);">
              <span data-dc-tpl="16" style="color: rgb(74, 81, 88);">희망 직무</span><span data-dc-tpl="17" style="color: rgb(223, 227, 230); font-weight: 600;">프론트/풀스택</span>
            </div>
            <div data-dc-tpl="18" style="display: flex; justify-content: space-between; font-size: 13.5px; padding-bottom: 16px; border-bottom: 1px solid rgba(255, 255, 255, 0.08);">
              <span data-dc-tpl="19" style="color: rgb(74, 81, 88);">개발경력</span><span data-dc-tpl="20" style="color: rgb(223, 227, 230); font-weight: 600;">3년+</span>
            </div>
            <a data-dc-tpl="21" href="mailto:ejrrl6931@gmail.com" style="display: flex; align-items: center; gap: 10px; font-family: &quot;JetBrains Mono&quot;, monospace; font-size: 13px; color: rgb(154, 160, 166);">
              <svg data-dc-tpl="22" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect data-dc-tpl="23" x="2" y="4" width="20" height="16" rx="2"></rect><path data-dc-tpl="24" d="M2 6l10 7 10-7"></path></svg>
              ejrrl6931@gmail.com
            </a>
            <a data-dc-tpl="25" href="https://github.com/Deokgi-Park" style="display: flex; align-items: center; gap: 10px; font-family: &quot;JetBrains Mono&quot;, monospace; font-size: 13px; color: rgb(154, 160, 166);">
              <svg data-dc-tpl="26" width="15" height="15" viewBox="0 0 24 24" fill="currentColor"><path data-dc-tpl="27" d="M12 2C6.48 2 2 6.58 2 12.26c0 4.52 2.87 8.35 6.84 9.71.5.1.68-.22.68-.49 0-.24-.01-.87-.01-1.71-2.78.62-3.37-1.37-3.37-1.37-.45-1.18-1.11-1.5-1.11-1.5-.91-.64.07-.63.07-.63 1 .07 1.53 1.05 1.53 1.05.89 1.56 2.34 1.11 2.91.85.09-.66.35-1.11.63-1.37-2.22-.26-4.56-1.14-4.56-5.06 0-1.12.39-2.03 1.03-2.75-.1-.26-.45-1.31.1-2.73 0 0 .84-.28 2.75 1.05a9.3 9.3 0 0 1 5 0c1.91-1.33 2.75-1.05 2.75-1.05.55 1.42.2 2.47.1 2.73.64.72 1.03 1.63 1.03 2.75 0 3.93-2.34 4.8-4.57 5.05.36.32.68.94.68 1.9 0 1.37-.01 2.47-.01 2.81 0 .27.18.6.69.49A10.02 10.02 0 0 0 22 12.26C22 6.58 17.52 2 12 2z"></path></svg>
              github.com/Deokgi-Park
            </a>
          </div>
        </div>
      </aside>
author_profile: false
date: 2026-03-31
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
    .sidebar p{
      text-align: left;
    }
    body {
      margin: 0;
      font-family: Pretendard, "Noto Sans KR", -apple-system, BlinkMacSystemFont,
        "Segoe UI", sans-serif;
      /* color: var(--ink); */
      /* background:
        radial-gradient(circle at 8% 5%, rgba(255, 0, 132, 0.08), transparent 22rem),
        linear-gradient(#fff, #fbfbfd); */
      line-height: 1.65;
    }

    a {
      text-decoration: none;
    }

    img, svg {
      display: block;
      max-width: 100%;
    }

    section#about strong{
      color: black;
    }
    section#skills h3, section#projects h3{
      color: black;
    }
    section#certificates strong{
      color: black;
      font-size: 20px;
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
      min-height: calc(100vh - 72px);
      display: grid;
      align-items: center;
      padding: 84px 0;
    }

    .hero-grid {
      display: grid;
      grid-template-columns: 1.25fr 0.2fr;
      gap: 72px;
      align-items: center;
    }

    .print-only-profile {
      display: none;
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
      font-size: clamp(44px, 7vw, 88px);
      line-height: 1.02;
      letter-spacing: -0.065em;
    }

    .hero-title-accent {
      color: var(--accent);
    }

    .hero-copy {
      margin: 0;
      max-width: 720px;
      font-size: clamp(18px, 2vw, 24px);
      color: rgba(255, 245, 251, 0.62);
      letter-spacing: -0.025em;
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
    }

    .button-secondary:hover {
      border-color: var(--accent);
      color: var(--accent);
    }

    .profile-card {
      position: relative;
      padding: 26px;
      border: 1px solid rgba(232, 232, 238, 0.9);
      border-radius: 34px;
      background: rgba(255, 255, 255, 0.88);
      box-shadow: var(--shadow);
      overflow: hidden;
    }

    .profile-card::after {
      content: "";
      position: absolute;
      right: -60px;
      bottom: -80px;
      width: 220px;
      height: 220px;
      border-radius: 50%;
      background: rgba(255, 0, 132, 0.1);
      filter: blur(6px);
    }

    .profile-photo {
      width: 100%;
      aspect-ratio: 4 / 5;
      object-fit: cover;
      object-position: center top;
      border-radius: 24px;
      background: #ececf2;
    }

    .profile-meta {
      position: relative;
      z-index: 2;
      margin-top: 22px;
    }

    .profile-name {
      margin: 0;
      font-size: 28px;
      letter-spacing: -0.04em;
    }

    .profile-role {
      margin: 4px 0 18px;
      color: var(--accent);
      font-weight: 800;
    }

    .profile-facts {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 10px;
    }

    .fact {
      padding: 14px;
      border-radius: 14px;
      background: var(--surface-alt);
    }

    .fact strong {
      display: block;
      font-size: 18px;
    }

    .fact span {
      font-size: 13px;
      color: var(--muted);
    }

    section {
      padding: 110px 0;
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
      font-size: clamp(34px, 5vw, 58px);
      line-height: 1.1;
      letter-spacing: -0.05em;
    }

    .section-description {
      margin: 0;
      color: var(--muted);
      font-size: 18px;
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
      font-size: clamp(22px, 3vw, 34px);
      line-height: 1.45;
      font-weight: 800;
      letter-spacing: -0.035em;
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
      padding: 24px 28px;
      background: white;
    }

    .principle strong {
      display: block;
      margin-bottom: 6px;
      font-size: 18px;
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
      min-height: 190px;
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
      font-size: 23px;
      letter-spacing: -0.035em;
    }

    .skill-card p {
      margin: 0 0 18px;
      color: var(--muted);
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 7px;
    }

    .tag {
      padding: 6px 9px;
      border-radius: 999px;
      background: var(--surface-alt);
      font-size: 12px;
      font-weight: 800;
      color: #4d4d58;
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
      font-size: 14px;
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
      font-size: 25px;
    }

    .timeline-role {
      margin: 5px 0 18px;
      color: var(--accent);
      font-weight: 800;
    }

    .timeline-card ul {
      margin: 0;
      padding-left: 18px;
      color: #cacad2;
    }

    .timeline-card li + li {
      margin-top: 7px;
    }

    .projects-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 22px;
    }

    .project-card {
      position: relative;
      min-height: 390px;
      padding: 30px;
      border: 1px solid var(--line);
      border-radius: var(--radius-lg);
      background: white;
      overflow: hidden;
      transition: 0.25s ease;
    }

    .project-card:hover {
      transform: translateY(-5px);
      box-shadow: var(--shadow);
    }

    .project-card::before {
      content: "";
      position: absolute;
      right: -35px;
      top: -35px;
      width: 190px;
      height: 190px;
      border-radius: 50%;
      background: linear-gradient(135deg, rgba(255, 0, 132, 0.14), rgba(255, 0, 132, 0.02));
    }

    .project-index {
      position: relative;
      color: var(--accent);
      font-weight: 900;
      letter-spacing: 0.12em;
      font-size: 12px;
    }

    .project-card h3 {
      position: relative;
      margin: 52px 0 12px;
      font-size: 32px;
      letter-spacing: -0.045em;
    }

    .project-card p {
      position: relative;
      margin: 0;
      max-width: 88%;
      color: var(--muted);
    }

    .project-footer {
      position: absolute;
      left: 30px;
      right: 30px;
      bottom: 28px;
      display: flex;
      justify-content: space-between;
      align-items: end;
      gap: 10px;
    }

    .project-link {
      color: var(--accent);
      font-weight: 900;
    }

    .cert-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 14px;
    }

    .cert {
      padding: 22px;
      border: 1px solid var(--line);
      border-radius: 16px;
      background: white;
    }

    .cert strong {
      display: block;
      margin-bottom: 8px;
    }

    .cert span {
      color: var(--muted);
      font-size: 14px;
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
      font-size: clamp(34px, 5vw, 58px);
      letter-spacing: -0.055em;
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
@media (min-width: 1280px) {
  .site-header.is-solid {
    transition: 1s;
    width: calc(100% + 300px);
    transform: translateX(-300px);
  }
}
@media (max-width: 1024px) {
  .sidebar aside{
    width: 50% !important;
    margin: auto;
  }
  .archive {
    margin-top :2.5em;
  }
}
@media (max-width: 900px) {
      .hero {
        padding-top: 54px;
      }

      .hero-grid,
      .about-grid,
      .section-heading,
      .contact-box {
        grid-template-columns: 1fr;
        gap:24px
      }

      .hero-grid {
        gap: 42px;
      }

      .nav-links {
        gap: 12px;
      }

      .nav-download-btn {
        min-height: 34px;
        width: 34px;
        height: 34px;
        padding: 0;
      }

      .profile-card {
        max-width: 520px;
      }

      .skill-card,
      .skill-card:nth-child(1),
      .skill-card:nth-child(2),
      .skill-card:nth-child(n+3) {
        grid-column: span 6;
      }

      .projects-grid {
        grid-template-columns: 1fr;
      }

      .cert-grid {
        grid-template-columns: repeat(2, 1fr);
      }
    }

    @media (max-width: 640px) {
      .container {
        width: min(calc(100% - 24px), var(--max-width));
      }

      section {
        padding: 78px 0;
      }

      .hero {
        min-height: auto;
      }

      .hero-actions {
        flex-direction: column;
      }

      .nav-download-btn {
        min-height: 32px;
        width: 32px;
        height: 32px;
        padding: 0;
      }

      .nav-download-btn svg {
        width: 14px;
        height: 14px;
      }

      .button {
        width: 100%;
      }

      .profile-facts {
        grid-template-columns: 1fr;
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

      .cert-grid {
        grid-template-columns: 1fr;
      }

      .contact-box {
        padding: 34px 24px;
      }
    }

    @media print {
      .site-header,
      .hero-actions {
        display: none;
      }

      .sidebar {
        display: none !important;
      }

      .print-only-profile {
        display: block;
      }

      .hero-grid {
        grid-template-columns: 1fr 250px;
        gap: 22px;
        align-items: start;
      }

      .print-only-profile aside {
        width: 100%;
        margin: 0;
      }

      .print-only-profile [data-dc-tpl="9"] {
        padding: 14px 14px 16px !important;
      }

      .print-only-profile [data-dc-tpl="11"] {
        gap: 10px !important;
      }

      .print-only-profile [data-dc-tpl="10"] {
        margin-bottom: 10px !important;
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

      * {
        text-shadow: none !important;
      }

      .hero-copy,
      .section-description,
      .timeline-date,
      .timeline-role,
      .project-card p,
      .cert span,
      .principle p,
      .skill-card p,
      .tag,
      .print-only-profile,
      .print-only-profile *,
      .sidebar,
      .sidebar * {
        color: #222 !important;
      }

      .hero-title-accent,
      .section-kicker,
      .project-index,
      .button-secondary,
      .project-link {
        color: #000 !important;
      }

      .experience,
      .timeline-card,
      .profile-card,
      .project-card,
      .skill-card,
      .panel,
      .cert,
      .fact,
      .print-only-profile aside,
      .print-only-profile [data-dc-tpl="7"],
      .sidebar aside,
      .sidebar [data-dc-tpl="7"] {
        background: #fff !important;
        border-color: #cfcfd8 !important;
      }

      .profile-card::after,
      .project-card::before,
      .site-header::before,
      .timeline::before,
      .timeline-item::before {
        display: none !important;
      }

      .print-only-profile img,
      .sidebar img,
      .profile-photo {
        filter: none !important;
      }

      .hero {
        min-height: auto;
      }

      section {
        padding: 45px 0;
        break-inside: avoid;
        break-after: page;
        page-break-inside: avoid;
        page-break-after: always;
      }

      section:first-of-type {
        break-before: auto;
        page-break-before: auto;
      }

      section:last-of-type {
        break-after: auto;
        page-break-after: auto;
      }

      #skills {
        break-after: auto;
        page-break-after: auto;
        padding-bottom: 20px;
      }

      #experience {
        break-before: avoid-page;
        page-break-before: auto;
        padding-top: 20px;
      }

      #skills .section-heading,
      #experience .section-heading {
        margin-bottom: 22px;
      }

      #skills .skills-layout {
        gap: 10px;
      }

      #skills .skill-card {
        min-height: auto;
        padding: 16px;
      }

      #skills .skill-number {
        font-size: 11px;
      }

      #skills .skill-card h3 {
        margin: 10px 0 6px;
        font-size: 18px;
      }

      #skills .skill-card p {
        margin: 0 0 10px;
        font-size: 13px;
        line-height: 1.45;
      }

      #skills .skill-card img {
        display: none;
      }

      #experience .timeline {
        gap: 12px;
      }

      #experience .timeline-item {
        gap: 20px;
      }

      #experience .timeline-date {
        font-size: 12px;
        padding-top: 10px;
      }

      #experience .timeline-card {
        padding: 16px 18px;
      }

      #experience .timeline-card h3 {
        font-size: 19px;
      }

      #experience .timeline-role {
        margin: 2px 0 8px;
        font-size: 13px;
      }

      #experience .timeline-card ul {
        font-size: 13px;
        line-height: 1.4;
        color: #111 !important;
      }

      #experience .timeline-card li {
        color: #111 !important;
      }

      #projects {
        padding-top: 28px;
        padding-bottom: 28px;
      }

      #projects .section-heading {
        margin-bottom: 18px;
      }

      #projects .projects-grid {
        grid-template-columns: 1fr;
        gap: 10px;
      }

      #projects .project-card {
        min-height: auto;
        padding: 18px;
      }

      #projects .project-card h3 {
        margin: 18px 0 6px;
        font-size: 22px;
      }

      #projects .project-card p {
        max-width: 100%;
        margin-bottom: 10px;
        font-size: 13px;
        line-height: 1.45;
        color: #111 !important;
      }

      #projects .project-footer {
        position: static;
        margin-top: 8px;
        align-items: center;
      }

      #projects .project-link,
      #projects .tag,
      #projects .project-index {
        color: #111 !important;
      }

      .panel,
      .skill-card,
      .project-card,
      .timeline-card,
      .cert {
        break-inside: avoid;
        box-shadow: none;
      }

      a {
        color: #111 !important;
      }
    }
    .reveal { opacity: 1 !important; transform: none !important; }

</style>
<div
  style="
    position: fixed;
    inset: 0;
    pointer-events: none;
    background:
      radial-gradient(circle at 18% 12%, rgba(255, 0, 183, 0.1), transparent 45%),
      radial-gradient(circle at 85% 75%, rgba(255, 46, 196, 0.07), transparent 40%);
    z-index: 0;
  "
></div>
<header class="site-header">
    <div class="container nav">
      <a class="brand" href="#top" aria-label="홈으로 이동">
        <svg class="brand-mark" viewBox="0 0 120 120" aria-hidden="true">
          <path d="M20 63c-9-3-14-11-12-17 2-5 7-6 14-2l8 4c2-24 18-40 40-42 22-2 42 13 46 35 3 17-3 31-15 43 18 3 31 1 39-8 5-6 9-10 12-9 6 2 9 15 7 27-5 31-31 48-71 48-31 0-58-12-68-31-8-15-5-29 10-45l-10-3Z"
            fill="none" stroke="currentColor" stroke-width="6" stroke-linecap="round" stroke-linejoin="round" />
          <circle cx="58" cy="38" r="5" fill="currentColor" />
          <path d="M31 48c9 6 18 7 29 2" fill="none" stroke="currentColor" stroke-width="5" stroke-linecap="round" />
        </svg>
        <span>Portfolio</span>
      </a>
      <nav class="nav-links" aria-label="주요 메뉴">
        <a href="#about">소개</a>
        <a href="#skills">기술</a>
        <a href="#experience">경력</a>
        <a href="#projects">프로젝트</a>
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
      <div class="container hero-grid">
        <div>
          <span class="eyebrow">Frontend · Full-stack Developer</span>
          <h1>
            문제를 끝까지 추적하고<br />
            <span class="hero-title-accent">해결하는 실전형 개발자입니다.</span>
          </h1>
          <p class="hero-copy">
            수만 명 규모의 서비스 운영 환경에서 유지보수와 장애 대응을 경험한
            프론트엔드 중심 풀스택 개발자 박덕기입니다.
          </p>
          <div class="hero-actions">
            <a class="button button-primary" style="color: white;" href="#projects">프로젝트 보기</a>
          </div>
        </div>
        <div class="print-only-profile">
          {{ page.sidebar[0].text }}
        </div>
      </div>
    </section>
    <section id="about">
      <div class="container">
        <div class="section-heading reveal">
          <div>
            <span class="section-kicker">About</span>
            <h2 class="section-title">자기소개</h2>
          </div>
          <p class="section-description"></p>
        </div>
        <div class="about-grid">
          <div class="panel statement reveal" style="display: flex; align-items: center; color: black;">
            <div>“다양한 운영 환경에서도 원인 분석부터 해결까지 빠르게 실행하는
            <em>실전형 개발자</em>입니다.”</div>
          </div>
          <div class="panel principles reveal">
            <div class="principle">
              <strong>사용자 중심 구현</strong>
              <p>React와 Next.js를 활용해 빠르고 명확한 사용자 경험을 만듭니다.</p>
            </div>
            <div class="principle">
              <strong>장애 원인 분석</strong>
              <p>서버, DB, 연동 구간을 함께 보며 문제의 실제 원인을 추적합니다.</p>
            </div>
            <div class="principle">
              <strong>AI 기반 생산성</strong>
              <p>Claude Code 등 AI 도구를 검토와 구현에 활용해 개발 속도를 높입니다.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="skills">
      <div class="container">
        <div class="section-heading reveal">
          <div>
            <span class="section-kicker">Skills</span>
            <h2 class="section-title">기술</h2>
          </div>
          <p class="section-description"></p>
        </div>
        <div class="skills-layout">
          <article class="skill-card reveal">
            <span class="skill-number">01 · FRONTEND</span>
            <h3>사용자 중심 인터페이스</h3>
            <p>React 기반 UI 개발, Next.js SSR, 반응형 웹과 상태 관리 경험을 갖추고 있습니다.</p>
            <img src="/assets/images/front.png">
          </article>
          <article class="skill-card reveal">
            <span class="skill-number">02 · BACKEND</span>
            <h3>서비스 로직과 API</h3>
            <p>Spring MVC와 Flask 기반 서버 구현, 인증 및 외부 시스템 연동 경험이 있습니다.</p>
            <img src="/assets/images/back.png">
          </article>
          <article class="skill-card reveal">
            <span class="skill-number">03 · DATABASE</span>
            <h3>데이터 모델과 운영</h3>
            <p>관계형 DB의 DDL·DML과 NoSQL 기반 데이터 저장소를 다뤄왔습니다.</p>
            <img src="/assets/images/db.png">
          </article>
          <article class="skill-card reveal">
            <span class="skill-number">04 · INFRA</span>
            <h3>서비스 운영 환경</h3>
            <p>Linux, Apache, Tomcat 및 컨테이너 환경에서 설치·배포·장애 대응을 수행했습니다.</p>
            <img src="/assets/images/server.png">
          </article>
          <article class="skill-card reveal">
            <span class="skill-number">05 · CS & AUTOMATION</span>
            <h3>기초와 자동화</h3>
            <p>C 기반 자료구조와 OS 학습, Python을 활용한 크롤링·자동화 도구 개발 경험이 있습니다.</p>
            <img src="/assets/images/auto.png">
          </article>
        </div>
      </div>
    </section>
    <section id="experience" class="experience">
      <div class="container">
        <div class="section-heading reveal">
          <div>
            <span class="section-kicker">Experience</span>
            <h2 class="section-title">경력 / 경험</h2>
          </div>
          <p class="section-description"></p>
        </div>
        <div class="timeline">
          <article class="timeline-item reveal">
            <div class="timeline-date">2024.11 — 2025.12<br/>(12개월)</div>
            <div class="timeline-card">
              <h3>핸디코어 · PS팀</h3>
              <div class="timeline-role">그룹웨어 구축 프로젝트</div>
              <ul>
                <li>제주 관공서 6개 기관 그룹웨어 차세대 구축 및 클라우드 환경 구성</li>
                <li>DB 커넥션 연결 장애 원인 분석, ERP 문서 결재 연동 설계</li>
                <li>부산 공사 프로젝트 테스트·패치·배포, WEB/WAS 운영 지원</li>
                <li>자사 솔루션의 Kubernetes 배포 환경 검증</li>
              </ul>
            </div>
          </article>
          <article class="timeline-item reveal">
            <div class="timeline-date">2024.03 — 2024.08<br/>(5개월)</div>
            <div class="timeline-card">
              <h3>크래프톤 정글</h3>
              <div class="timeline-role">CS 집중 교육과정</div>
              <ul>
                <li>Flask·JWT·Jinja2 기반 기숙사 민원 관리 서비스 Tarzan 개발</li>
                <li>React 기반 코딩테스트 보조 사이트 POKECODE 개발</li>
                <li>알고리즘, 자료구조 학습</li>
                <li>C언어 프로젝트 수행<br/>→ Malloc Lab을 통한 메모리 할당 및 R-B Tree, Linked List 등의 구현 </li>
                <li>KAIST 교육용 운영체제 분석 및 과제 수행<br/>→ 스케줄링, 스레드와 프로세스, 가상 메모리, 커널 등</li>
              </ul>
            </div>
          </article>
          <article class="timeline-item reveal">
            <div class="timeline-date">2022.03 — 2024.03<br/>(24개월)</div>
            <div class="timeline-card">
              <h3>핸디코어 · CS팀</h3>
              <div class="timeline-role">유지보수 및 연동 개발</div>
              <ul>
                <li>대형 의료원 그룹웨어 유지보수 및 모바일 SLO API 구현</li>
                <li>생체인증(FIDO), SAP, 조직도 시스템 연동 오류 분석 및 협의</li>
                <li>DB 비교로 문서를 타 서버로 전송하는 Java 툴 개발</li>
              </ul>
            </div>
          </article>
          <article class="timeline-item reveal">
            <div class="timeline-date">2021.09 — 2022.03<br/>(6개월)</div>
            <div class="timeline-card">
              <h3>삼두정보기술</h3>
              <div class="timeline-role">ERP 연구원 및 PM 보조</div>
              <ul>
                <li>ERP 차세대 프로젝트 투입 및 고객 CS 대응</li>
                <li>프로젝트 문서 관리, 오류 원인 분석 및 수정 배포</li>
              </ul>
            </div>
          </article>
        </div>
      </div>
    </section>
    <section id="projects">
      <div class="container">
        <div class="section-heading reveal">
          <div>
            <span class="section-kicker">Projects</span>
            <h2 class="section-title">프로젝트</h2>
          </div>
          <p class="section-description"></p>
        </div>
        <div class="projects-grid">
          <article class="project-card reveal">
            <span class="project-index">01 · 2026.03</span>
            <h3>포켓몬 게시판</h3>
            <p>Next.js와 Firebase를 활용한 실시간 데이터 기반 게시판 프로젝트입니다.</p>
            <div class="project-footer">
              <div class="tags"><span class="tag">Next.js</span><span class="tag">Firebase</span></div>
              <a class="project-link" href="#" aria-label="포켓몬 게시판 프로젝트 보기">View ↗</a>
            </div>
          </article>
          <article class="project-card reveal">
            <span class="project-index">02 · 2025.09</span>
            <h3>일일 미로 게임</h3>
            <p>하루 한 번 즐기는 짧은 플레이 경험과 기록을 제공하는 웹 게임입니다.</p>
            <div class="project-footer">
              <div class="tags"><span class="tag">Next.js</span><span class="tag">Cloudflare D1</span></div>
              <a class="project-link" href="#" aria-label="일일 미로 게임 프로젝트 보기">View ↗</a>
            </div>
          </article>
          <article class="project-card reveal">
            <span class="project-index">03 · 2024.06 — 07</span>
            <h3>POKE-CODE</h3>
            <p>React 기반 인터랙션과 Node.js 서버를 결합해 제작한 풀스택 프로젝트입니다.</p>
            <div class="project-footer">
              <div class="tags"><span class="tag">React</span><span class="tag">TypeScript</span><span class="tag">Node.js</span><span class="tag">MySQL</span></div>
              <a class="project-link" href="#" aria-label="POKE-CODE 프로젝트 보기">View ↗</a>
            </div>
          </article>
          <article class="project-card reveal">
            <span class="project-index">04 · 2024.03</span>
            <h3>Tarzan</h3>
            <p>기숙사 민원을 등록하고 관리하는 Flask·JWT 기반 웹 서비스입니다.</p>
            <div class="project-footer">
              <div class="tags"><span class="tag">Python</span><span class="tag">Flask</span><span class="tag">JWT</span><span class="tag">SSR</span></div>
              <a class="project-link" href="#" aria-label="Tarzan 프로젝트 보기">View ↗</a>
            </div>
          </article>
        </div>
      </div>
    </section>
    <section id="certificates">
      <div class="container">
        <div class="section-heading reveal">
          <div>
            <span class="section-kicker">Certificates</span>
            <h2 class="section-title">자격 / 수료</h2>
          </div>
          <p class="section-description"></p>
        </div>
        <div class="cert-grid">
          <div class="cert reveal"><strong>K-PAAS <span data-dc-tpl="78" style="font-size: 12px; color: rgb(255, 0, 132); background: rgba(255, 0, 132, 0.1); padding: 5px 12px; border-radius: 999px;"><span class="sc-interp">수료증</span></span></strong><div style="color: var(--muted); font-size: 14px;">쿠버네티스 기반 개방형 클라우드 플랫폼 교육</div><span>2025.04.03</span></div>
          <div class="cert reveal"><strong>크래프톤 정글 <span data-dc-tpl="78" style="font-size: 12px; color: rgb(255, 0, 132); background: rgba(255, 0, 132, 0.1); padding: 5px 12px; border-radius: 999px;"><span class="sc-interp">수료증</span></span></strong><div style="color: var(--muted); font-size: 14px;">CS 및 프로젝트 기반 교육 훈련 프로그램</div><span>2024.08.01</span></div>
          <div class="cert reveal"><strong>정보처리기사 <span data-dc-tpl="78" style="font-size: 12px; color: rgb(255, 0, 132); background: rgba(255, 0, 132, 0.1); padding: 5px 12px; border-radius: 999px;"><span class="sc-interp">자격증</span></span></strong><div style="color: var(--muted); font-size: 14px;">국가공인기술자격증</div><span>2022.11.25</span></div>
          <div class="cert reveal"><strong>SQLD <span data-dc-tpl="78" style="font-size: 12px; color: rgb(255, 0, 132); background: rgba(255, 0, 132, 0.1); padding: 5px 12px; border-radius: 999px;"><span class="sc-interp">자격증</span></span></strong><div style="color: var(--muted); font-size: 14px;">국가 공인 SQL 자격증</div><span>2021.06.25</span></div>
          <div class="cert reveal"><strong>사무자동화산업기사 <span data-dc-tpl="78" style="font-size: 12px; color: rgb(255, 0, 132); background: rgba(255, 0, 132, 0.1); padding: 5px 12px; border-radius: 999px;"><span class="sc-interp">자격증</span></span></strong><div style="color: var(--muted); font-size: 14px;">국가공인기술자격증</div><span>2021.06.02</span></div>
          <div class="cert reveal"><strong>GTQ 1급 <span data-dc-tpl="78" style="font-size: 12px; color: rgb(255, 0, 132); background: rgba(255, 0, 132, 0.1); padding: 5px 12px; border-radius: 999px;"><span class="sc-interp">자격증</span></span></strong><div style="color: var(--muted); font-size: 14px;">국가공인기술자격증</div><span>2020.08.14</span></div>
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
