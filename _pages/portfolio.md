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
      <p>이름 : 박덕기</p>
      <hr />
      <p>프론트/풀스택 개발자</p>
      <hr />
      <p>개발경력 : 3년</p>
      <hr />
      <ul class="author__urls social-icons" style="margin-top: 10px; text-align:left;">
      <li><a href="mailto:ejrrl6931@gmail.com" rel="nofollow noopener noreferrer me"><i class="fas fa-fw fa-envelope-square" aria-hidden="true"></i><span class="label"> ejrrl6931@gmail.com</span></a></li>
      <li><a href="https://github.com/Deokgi-Park" rel="nofollow noopener noreferrer me" itemprop="sameAs"><i class="fab fa-fw fa-github" aria-hidden="true"></i><span class="label"> github.com/Deokgi-Park</span></a></li>
      </ul>
author_profile: false
date: 2026-03-31
feature_row1:
  - image_path: /assets/images/stack1.png
    alt: "stack1"
    title: "기본적인 웹페이지 작성 기술"
    excerpt: '웹 퍼블리싱, 미디어 쿼리를 활용한 반응형 웹 디자인 및<br/> jQuery를 활용한 DOM 조작 및 이벤트 핸들링 가능'
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/stack2.png
    alt: "stack2"
    title: "프론트엔드 라이브러리/프레임워크 기술"
    excerpt: 'React 기반 프론트엔드 개발, Next.js SSR 경험, 상태관리 라이브러리 경험'
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/stack3.png
    alt: "stack3"
    title: "생산성 & 품질을 위한 기술"
    excerpt: '빠른 UI 개발과 안정적인 코드 작성을 위한 도구 경험'
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/stack4.png
    alt: "stack4"
    title: "JAVA 프레임워크를 통한 백엔드 개발 기술"
    excerpt: 'Spring Framework를 사용한 MVC 패턴 기반 백엔드 개발'
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
feature_row5:
  - image_path: /assets/images/stack5.png
    alt: "stack5"
    title: "다양한 형태의 DBMS 기술"
    excerpt: 'DDL·DML을 활용한 관계형 DB 관리, NoSQL 사용 경험'
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
feature_row6:
  - image_path: /assets/images/stack6.png
    alt: "stack6"
    title: "Python 라이브러리를 통한 API 서버 및 툴 제작"
    excerpt: 'Flask 웹 서버 구축, BeautifulSoup 크롤링, selenium을 통한 원격 조작 등 파이썬 라이브러리를 통해 자동화 툴이나 특수한 서버 개발 가능'
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
feature_row7:
  - image_path: /assets/images/stack7.png
    alt: "stack7"
    title: "컨테이너 및 오케스트레이션 기능 경험"
    excerpt: 'K-PAAS 교육 수료 및 미니쿠버네티스 구축 경험, 컨테이너 기술 학습'
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
feature_row8:
  - image_path: /assets/images/stack8.png
    alt: "stack8"
    title: "리눅스 및 웹 서버 관련 기술"
    excerpt: '리눅스 서버 내 Apache 기반 WEB/WAS 설치 및 유지보수 경험'
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
feature_row9:
  - image_path: /assets/images/stack9.png
    alt: "stack9"
    title: "C언어를 통한 CS 지식 경험"
    excerpt: '메모리 할당, 웹 서버 개선, OS에서 스레드/프로세스 스케줄링 학습'
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500;700&display=swap');
.sidebar {
  text-align: center;
}

.sidebar .author__avatar img,
.sidebar img {
  display: block;
  margin: 0 auto 0.6em;
  width: 75%;
  border-radius: 50%;
}

/* 사이드바 섹션 타이틀 숨김 (개인 정보 텍스트) */
.sidebar .sidebar__section-title {
  display: none;
}

/* 사이드바 전체 간격 축소 */
.sidebar .section__title {
  font-size: 0.85em;
  margin-bottom: 0.4em;
}

.sidebar p {
  margin: 0 0 0.15em;
  font-size: 0.85em;
  line-height: 1.4;
}

.sidebar hr {
  margin: 0.4em 0;
  border: none;
  border-top: 1px solid rgba(255,255,255,0.15);
}

.sidebar ul.author__urls {
  margin-top: 0.5em !important;
}

.sidebar ul.author__urls li {
  font-size: 0.82em;
  padding: 0.15em 0;
}

img{
  transition: none;
}

@media (max-width: 1024px) {
  .sidebar img {
    width: 20% !important;
  }
  .archive {
    margin-top :2.5em;
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
  .archive__item-teaser,
  .feature__wrapper .archive__item-teaser {
    background: #000 !important;
    -webkit-print-color-adjust: exact;
    print-color-adjust: exact;
  }
  .archive__item-teaser img,
  .feature__wrapper .archive__item-teaser img {
    background: #000 !important;
    -webkit-print-color-adjust: exact;
    print-color-adjust: exact;
  }
  table {
    border-collapse: collapse;
    width: 100%;
  }
  th, td {
    border: 1px solid #ccc;
    padding: 4px 8px;
  }
  #print-btn {
    display: none !important;
  }
  div[style*="linear-gradient"] {
    background: #999 !important;
    height: 1px !important;
    margin: 2em 0 3em !important;
    border-radius: 0 !important;
    -webkit-print-color-adjust: exact;
    print-color-adjust: exact;
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
    width: 100% !important;
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
}

/* 커스텀 커서 */
body.portfolio-page {
  cursor: none;
}
body.portfolio-page a,
body.portfolio-page button {
  cursor: none;
}
.sidebar *{
  cursor: none;
}
#cursor-dot {
  position: fixed;
  top: 0;
  left: 0;
  width: 8px;
  height: 8px;
  background: #00bfff;
  border-radius: 50%;
  pointer-events: none;
  z-index: 99999;
  will-change: transform;
  box-shadow: 0 0 8px #00bfff, 0 0 16px #00bfff;
  transition: background 0.2s, box-shadow 0.2s;
}
#cursor-ring {
  position: fixed;
  top: 0;
  left: 0;
  width: 36px;
  height: 36px;
  border: 2px solid rgba(123, 47, 255, 0.7);
  border-radius: 50%;
  pointer-events: none;
  z-index: 99998;
  will-change: transform;
  box-shadow: 0 0 10px rgba(123, 47, 255, 0.5), inset 0 0 10px rgba(123, 47, 255, 0.1);
  transition: width 0.2s, height 0.2s, border-color 0.2s, box-shadow 0.2s;
}
body.portfolio-page a:hover ~ #cursor-dot,
body.portfolio-page button:hover ~ #cursor-dot {
  background: #7b2fff;
  box-shadow: 0 0 12px #7b2fff, 0 0 24px #7b2fff;
}
@media print {
  #cursor-dot, #cursor-ring { display: none !important; }
}
</style>

<script>
(function() {
  document.body.classList.add('portfolio-page');

  // cursor 요소를 body 최상위에 직접 추가
  const dot = document.createElement('div');
  dot.id = 'cursor-dot';
  document.body.appendChild(dot);

  const ring = document.createElement('div');
  ring.id = 'cursor-ring';
  document.body.appendChild(ring);
  let mouseX = 0, mouseY = 0;
  let ringX  = 0, ringY  = 0;

  document.addEventListener('mousemove', function(e) {
    mouseX = e.clientX;
    mouseY = e.clientY;
    dot.style.transform = 'translate(' + (mouseX - 4) + 'px, ' + (mouseY - 4) + 'px)';
  });

  // 링은 부드럽게 따라오게
  function animateRing() {
    ringX += (mouseX - ringX) * 0.12;
    ringY += (mouseY - ringY) * 0.12;
    ring.style.transform = 'translate(' + (ringX - 18) + 'px, ' + (ringY - 18) + 'px)';
    requestAnimationFrame(animateRing);
  }
  animateRing();

  // 클릭 시 링 확대 효과
  document.addEventListener('mousedown', function() {
    ring.style.width  = '50px';
    ring.style.height = '50px';
    ring.style.borderColor = 'rgba(0,191,255,0.9)';
    ring.style.boxShadow = '0 0 20px rgba(0,191,255,0.7), inset 0 0 20px rgba(0,191,255,0.2)';
  });
  document.addEventListener('mouseup', function() {
    ring.style.width  = '36px';
    ring.style.height = '36px';
    ring.style.borderColor = 'rgba(123,47,255,0.7)';
    ring.style.boxShadow = '0 0 10px rgba(123,47,255,0.5), inset 0 0 10px rgba(123,47,255,0.1)';
  });

  // 링크/버튼 호버 시 링 색상 변경
  document.querySelectorAll('a, button').forEach(function(el) {
    el.addEventListener('mouseenter', function() {
      dot.style.background  = '#7b2fff';
      dot.style.boxShadow   = '0 0 12px #7b2fff, 0 0 24px #7b2fff';
      ring.style.width      = '48px';
      ring.style.height     = '48px';
      ring.style.borderColor = 'rgba(0,191,255,0.9)';
    });
    el.addEventListener('mouseleave', function() {
      dot.style.background  = '#00bfff';
      dot.style.boxShadow   = '0 0 8px #00bfff, 0 0 16px #00bfff';
      ring.style.width      = '36px';
      ring.style.height     = '36px';
      ring.style.borderColor = 'rgba(123,47,255,0.7)';
    });
  });
})();
</script>

<div  class='br-line' id="print-btn" style="float: right;">
  <button onclick="window.print()" style="padding:0.5em 1.4em; background:linear-gradient(135deg,#7b2fff,#00bfff); color:#fff; border:none; border-radius:6px; cursor:pointer; font-size:0.95em; font-weight:bold; letter-spacing:0.03em; position: relative; top: -6em; cursor: none;">
    📄 PDF로 저장
  </button>
</div>

## 소개

>_안녕하세요, **현장 맞춤형으로 여러 환경에서도 개발 가능한 개발자 '박덕기'** 입니다._

▶️ 프론트엔드에 관심이 많고 빠른 개발 동향에 맞춰 발전해나가는 개발자를 목표로 하고 있습니다.<br>
▶️ 2년간의 여러 환경에서 유지보수하는 경험으로 여러 환경과 상황에 대처하는 능력을 길렀습니다.<br>
▶️ 최근 AI로 개발하는 것에 관심이 많고 빠르고 다재다능한 개발을 목표로 학습하였습니다.<br>

<div  class='br-line' style="height:3px;background:linear-gradient(to right,transparent,#7b2fff,#00bfff,transparent);margin:2em 0;border-radius:2px;"></div>

## 기술

### 프론트엔드
{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}


### 백엔드
{% include feature_row id="feature_row4" type="left" %}

{% include feature_row id="feature_row5" type="left" %}

{% include feature_row id="feature_row6" type="left" %}


### 기타
{% include feature_row id="feature_row7" type="left" %}

{% include feature_row id="feature_row8" type="left" %}

{% include feature_row id="feature_row9" type="left" %}

<div  class='br-line' style="height:3px;background:linear-gradient(to right,transparent,#7b2fff,#00bfff,transparent);margin:2em 0;border-radius:2px;"></div>

## 경력 및 경험

| 기간              | 회사/교육                    | 역할                                                           |
| ----------------- | ---------------------------- | -------------------------------------------------------------- |
| 2024.11 ~ 2025.12 | 핸디코어<br>(12개월) | **[그룹웨어 솔루션 업체] PS팀 프로젝트**<br> **1️⃣ 제주 관공서 6개 기관 그룹웨어 차세대 구축 프로젝트** <br>💠 클라우드 환경에서 그룹웨어 구축<br>💠 DB 커넥션 연결 장애 발생 원인 분석 <br> 💠 ERP 시스템과 문서 결재 연동 설계 <br><br> **2️⃣ 부산 공사 프로젝트**<br>💠 단위 및 통합테스트 지원<br>💠 프로젝트 중 지속적인 패치 및 배포 진행<br>💠 타 시스템과 그룹웨어간 연동 프로세스 협의 및 지원<br>💠 WEB/WAS 설정 및 재기동 관리                         |
| 2024.03 ~ 2024.08 | 크래프톤 정글<br>(5개월)     | **[교육과정] CS 지식 관련 부트캠프**<br>**1️⃣ 3박 4일 미니 프로젝트**<br>💠 기숙사 민원 관리 시스템 'Tarzan' 개발<br>💠 Python의 Flask 웹서버 사용<br>💠 JWT 토큰을 통한 로그인 구현<br>💠 SPA와 SSR의 장단점 이해 <br>💠 Jinja2 템플릿 엔진을 사용한 SSR 구현<br><br>2️⃣ **알고리즘 및 자료구조**<br>💠 재귀 함수, 정렬, 완전탐색 <br>💠 이분탐색, 분할정복, 스택, 큐, 우선순위 큐<br>💠 그래프(vertex, edge, node, arc), BFS, DFS, 위상정렬<br>💠 동적 프로그래밍, 그리디 알고리즘<br><br>3️⃣ **C언어 프로젝트**<br>💠 Linked List 와 같은 자료구조 구현<br>💠 R-B트리 구현<br>💠 Malloc 을 통한 메모리 할당 및 개선<br>💠 웹서버를 분석 및 개선하여 서버 기술 터득 <br><br>4️⃣ **운영체제 프로젝트**<br>💠 KAIST 교육과정인 PintOS 분석 및 개선 프로젝트<br>💠 Threads 에 대한 이해 및 개선<br>💠 OS 커널과 User Program에 대한 이해<br>💠 가상메모리에 대한 이해 및 동작 구현|
| 2022.03 ~ 2024.03 | 핸디코어<br>(24개월)         | **[그룹웨어 솔루션 업체] CS팀 유지보수 및 사이드 프로젝트**<br>1️⃣ **대형 의료원 유지보수**<br>💠 모바일 SLO API 구현<br>💠 생체인증 로그인 화면 협의 및 작성<br>💠 SAP 연동 관련 발생 오류 분석 및 협의를 통한 문제 해결<br>💠 조직도 연동 관련 오류 원인 분석 및 협의<br>💠 IOS 앱 라이선스 갱신<br><br>2️⃣ **생체인증(FIDO) 도입 관련 연동 프로젝트**<br>💠 생체인증 업체와 API를 통한 연동 협의 및 개발<br>💠 조직도 연동 관련 오류 원인 분석 및 협의<br>💠 IOS 앱 라이선스 갱신<br><br>3️⃣ **문서이관용 JAVA 툴 작성**<br>💠 DB를 조회하여 특정 서버의 위치에 해당 파일을 전송하는 툴 작성|
| 2021.09 ~ 2022.03 | 삼두정보기술<br>(6개월)      | **[ERP 솔루션 업체] 연구원 및 PM보조**<br>1️⃣ 대전 내 관공서 관련  ERP 차세대 프로젝트<br>💠 고객 문의 직접 대응 및 프로젝트 문서 관리<br>💠 문제 원인 분석 및 수정 배포 진행 |

<div  class='br-line' style="height:3px;background:linear-gradient(to right,transparent,#7b2fff,#00bfff,transparent);margin:2em 0;border-radius:2px;"></div>

## 자격증 및 수료증

| 자격증 / 수료증      | 구분           |취득일|
| -------------------- | -------------- |
| K-PAAS 수료증        | 수료증         |2025.04.03|
| 크래프톤 정글 수료증 | 수료증         |2024.08.01|
| 정보처리기사         | 국가기술자격증 |2022.11.25|
| SQLD                 | 공인자격증     |2021.06.25|
| 사무자동화산업기사   | 국가기술자격증 |2021.06.02|
| GTQ 1급              | 국가기술자격증 |2020.08.14|

<div  class='br-line' style="height:3px;background:linear-gradient(to right,transparent,#7b2fff,#00bfff,transparent);margin:2em 0;border-radius:2px;"></div>

## 사이드 프로젝트

| 프로젝트              | 기간              | 기술 스택                                     |
| --------------------- | ----------------- | --------------------------------------------- |
| 포켓몬 게시판 | 2026.03           | Next.js, Firebase                             |
| 일일 미로 게임        | 2025.09           | Next.js, cloud flare d1                       |
| POKE-CODE             | 2024.06 ~ 2024.07 | React, Redux, TypeScript, Node.js, MySQL      |
| Tarzan                | 2024.03           | Python, Flask, Jinja, JWT, BeautifulSoup, SSR |
| 하베스토리            | 2021.03 ~ 2021.10 | Spring Framework, JSP, JSTL, MySQL, jQuery    |
| 게임예약사이트        | 2020.10 ~ 2020.12 | Spring Framework, JSP, JSTL, MySQL, jQuery    |

<div  class='br-line' style="height:3px;background:linear-gradient(to right,transparent,#7b2fff,#00bfff,transparent);margin:2em 0;border-radius:2px;"></div>

## 프로젝트 종류(링크_수정중)
