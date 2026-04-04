---
title: 박덕기 / PORTFOLIO
layout: collection
collection: portfolio
permalink: /portfolio/
entries_layout: grid
classes: wide
sidebar:
  - title: "개인 정보"
    image: /assets/images/profile/myReal.jpg
    image_alt: "박덕기"
    text: |
      <hr />
      <p>이름 박덕기</p>
      <hr />
      <p>프론트 및 풀스택 개발자</p>
      <hr />
      <ul class="author__urls social-icons" style="margin-top: 10px;">
      <li itemprop="homeLocation" itemscope="" itemtype="https://schema.org/Place">
      <i class="fas fa-fw fa-location-dot" aria-hidden="true"></i> <span itemprop="name" class="p-locality">경기도 용인시 수지구</span>
      </li>
      <li><a href="mailto:ejrrl6931@gmail.com" rel="nofollow noopener noreferrer me"><i class="fas fa-fw fa-envelope-square" aria-hidden="true"></i><span class="label">Email</span></a></li>
      <li><a href="https://github.com/Deokgi-Park" rel="nofollow noopener noreferrer me" itemprop="sameAs"><i class="fab fa-fw fa-github" aria-hidden="true"></i><span class="label">GitHub</span></a></li>
      </ul>
author_profile: false
date: 2026-03-31
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500;700&display=swap');

.sidebar .author__avatar img,
.sidebar img {
  display: block;
  margin: 0 auto;
  width : 80%;
}

// 260331_PDG_사이드바 작은 화면 스타일 수정
.sidebar {
  @media (max-width: #{$large}) {
    text-align: center;
    img {
      width: 20%;
    }
  }
}


@media print {
  *{
    font-family: 'Noto Sans KR', sans-serif !important;
  }
  .masthead,
  .page__footer,
  .page__share,
  .page__related,
  .page__comments,
  #print-btn {
    display: none !important;
  }
  body {
    font-size: 12pt;
    /* font-family: 'Noto Sans KR', sans-serif !important; */
    color: #000 !important;
    background: #fff !important;
  }
  a {
    color: #000 !important;
    text-decoration: none;
  }
  table {
    border-collapse: collapse;
    width: 100%;
  }
  th, td {
    border: 1px solid #ccc;
    padding: 4px 8px;
  }
  div[style*="linear-gradient"],
  .br-line,
  #print-btn {
    display: none !important;
  }
  #main {
    display: flex !important;
    align-items: flex-start;
  }
  .sidebar {
    display: block !important;
    width: 150px !important;
    min-width: 150px !important;
    flex-shrink: 0;
    opacity: 1 !important;
    margin-right: 2em;
    text-align: center;
  }
  .sidebar img {
    display: block;
    margin: 0 auto;
  }
  article.page {
    flex: 1 !important;
    width: auto !important;
    min-width: 0;
    overflow: hidden;
  }
  table {
    table-layout: fixed;
    word-break: break-all;
    outline : none;
    border : none;
  }
  .br-line {
    display: none !important;
  }
}
</style>

<div  class='br-line' id="print-btn" style="float: right;">
  <button onclick="window.print()" style="padding:0.5em 1.4em; background:linear-gradient(135deg,#7b2fff,#00bfff); color:#fff; border:none; border-radius:6px; cursor:pointer; font-size:0.95em; font-weight:bold; letter-spacing:0.03em; position: relative; top: -70px;">
    📄 PDF로 저장
  </button>
</div>

## 소개

안녕하세요, **새로운 것을 개발하는데 기쁨을 느끼는 '박덕기'** 입니다.

- 재미있는 애니메이션이나 효과를 만들고 이를 통해 사용자들의 사이트 이용 경험에 좋은 영향을 주는 것을 목표로 하고 이를 즐기는 개발자입니다.
- 문제 상황에 알맞은 대처에 대해 생각하고 주변과 소통하여 최적의 해결안을 찾으려 노력합니다.
- 맡은 일의 해결을 위해 집중하고 이를 해결하기까지 책임감을 갖고 업무를 수행합니다.

<div  class='br-line' style="height:3px;background:linear-gradient(to right,transparent,#7b2fff,#00bfff,transparent);margin:2em 0;border-radius:2px;"></div>

## 기술

### Front End

| 기술                          | 설명                                                                             |
| ----------------------------- | -------------------------------------------------------------------------------- |
| `HTML` / `CSS` / `JS`         | 미디어 쿼리를 활용한 반응형 웹 디자인, jQuery를 활용한 DOM 조작 및 이벤트 핸들링 |
| `React` / `Next.js` / `Redux` | React 기반 프론트엔드 개발, Next.js SSR 경험, Redux를 통한 상태 관리             |
| `TypeScript`                  | 타입 기반 개발 경험, 변수 타입 지정의 필요성 이해                                |
| `TailwindCSS`                 | 유틸리티 기반의 효율적인 스타일링                                                |

### Back End

| 기술                           | 설명                                                            |
| ------------------------------ | --------------------------------------------------------------- |
| `Spring Framework`             | MVC 패턴 기반 웹 개발, JSP / JSTL을 활용한 동적 페이지 작성     |
| `Oracle` / `MySQL` / `MongoDB` | DDL·DML을 활용한 관계형 DB 관리, NoSQL 사용 경험                |
| `Python` / `Flask` / `Jinja`   | Flask 웹 서버 구축, BeautifulSoup 크롤링, Jinja SSR 페이지 제작 |

### ETC

| 기술                          | 설명                                                                   |
| ----------------------------- | ---------------------------------------------------------------------- |
| `Kubernetes` / `Docker`       | MSA 배포 경험, 컨테이너 기술 학습                                      |
| `Apache` / `Tomcat` / `Linux` | 리눅스 기반 서버에 WEB/WAS 구성, 서버 유지보수                         |
| `C 언어`                      | 자료구조·알고리즘 학습, 웹 서버 구현, 스레드·프로세스·OS 스케줄링 학습 |

<div  class='br-line' style="height:3px;background:linear-gradient(to right,transparent,#7b2fff,#00bfff,transparent);margin:2em 0;border-radius:2px;"></div>

## 경력

| 기간              | 회사/교육                    | 역할                                                           |
| ----------------- | ---------------------------- | -------------------------------------------------------------- |
| 2024.11 ~ 2025.12 | 핸디코어<br>(재입사, 12개월) | [그룹웨어 솔루션 업체] PS팀 프로젝트                           |
| 2024.03 ~ 2024.08 | 크래프톤 정글<br>(5개월)     | [교육과정] 부트캠프 (CS, 알고리즘, 자료구조, Python, React 등) |
| 2022.03 ~ 2024.03 | 핸디코어<br>(24개월)         | [그룹웨어 솔루션 업체] CS팀 유지보수                           |
| 2021.09 ~ 2022.03 | 삼두정보기술<br>(6개월)      | [ERP 솔루션 업체] 연구원 및 PM보조                             |

<div  class='br-line' style="height:3px;background:linear-gradient(to right,transparent,#7b2fff,#00bfff,transparent);margin:2em 0;border-radius:2px;"></div>

## 프로젝트

| 프로젝트              | 기간              | 기술 스택                                     |
| --------------------- | ----------------- | --------------------------------------------- |
| 포켓몬 게시판(리뉴얼) | 2026.03           | Next.js, React, Firebase                      |
| POKE-CODE             | 2024.06 ~ 2024.07 | React, Redux, TypeScript, Node.js, MySQL      |
| 포켓몬 게시판         | 2024.06           | Next.js, React, Firebase                      |
| Tarzan                | 2024.03           | Python, Flask, Jinja, JWT, BeautifulSoup, SSR |
| 하베스토리            | 2021.03 ~ 2021.10 | Spring Framework, JSP, JSTL, MySQL, jQuery    |
| 게임예약사이트        | 2020.10 ~ 2020.12 | Spring Framework, JSP, JSTL, MySQL, jQuery    |

<div  class='br-line' style="height:3px;background:linear-gradient(to right,transparent,#7b2fff,#00bfff,transparent);margin:2em 0;border-radius:2px;"></div>

## 자격증

| 자격증 / 수료증      | 구분           |
| -------------------- | -------------- |
| 정보처리기사         | 국가기술자격증 |
| SQLD                 | 공인자격증     |
| 크래프톤 정글 수료증 | 수료증         |
| K-PAAS 수료증        | 수료증         |
| 사무자동화산업기사   | 국가기술자격증 |
| GTQ 1급              | 국가기술자격증 |

## 프로젝트 링크
