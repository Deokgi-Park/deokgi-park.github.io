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
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/image_duck.png
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/image_duck.png
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
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
  <button onclick="window.print()" style="padding:0.5em 1.4em; background:linear-gradient(135deg,#7b2fff,#00bfff); color:#fff; border:none; border-radius:6px; cursor:pointer; font-size:0.95em; font-weight:bold; letter-spacing:0.03em; position: relative; top: -70px; cursor: none;">
    📄 PDF로 저장
  </button>
</div>

## 소개

안녕하세요, **새로운 것을 개발하는데 기쁨을 느끼는 '박덕기'** 입니다.

- 재미있는 애니메이션이나 효과를 만들고 이를 통해 사용자들의 사이트 이용 경험에 좋은 영향을 주는 것을 목표로 하고 이를 즐기는 개발자입니다.
- 문제 상황에 알맞은 대처에 대해 생각하고 주변과 소통하여 최적의 해결안을 찾으려 노력합니다.
- 맡은 일의 해결을 위해 여러 방법으로 접근하며 이를 해결하기까지 책임감을 갖고 업무를 수행합니다.
- AI를 통한 빠른 개발을 학습하고 있습니다.

<div  class='br-line' style="height:3px;background:linear-gradient(to right,transparent,#7b2fff,#00bfff,transparent);margin:2em 0;border-radius:2px;"></div>

## 기술

### 프론트엔드

| 기술                          | 설명                                                                             |
| ----------------------------- | -------------------------------------------------------------------------------- |
| `HTML` / `CSS` / `JS`         | 미디어 쿼리를 활용한 반응형 웹 디자인, jQuery를 활용한 DOM 조작 및 이벤트 핸들링 |
| `React` / `Next.js` / `Redux` | React 기반 프론트엔드 개발, Next.js SSR 경험, Redux를 통한 상태 관리             |
| `TypeScript`                  | 타입 기반 개발 경험, 변수 타입 지정의 필요성 이해                                |
| `TailwindCSS`                 | 유틸리티 기반의 효율적인 스타일링                                                |

### 백엔드

| 기술                           | 설명                                                            |
| ------------------------------ | --------------------------------------------------------------- |
| `Spring Framework`             | MVC 패턴 기반 웹 개발, JSP / JSTL을 활용한 동적 페이지 작성     |
| `Oracle` / `MySQL` / `MongoDB` | DDL·DML을 활용한 관계형 DB 관리, NoSQL 사용 경험                |
| `Python` / `Flask` / `Jinja`   | Flask 웹 서버 구축, BeautifulSoup 크롤링, Jinja SSR 페이지 제작 |

### 기타

| 기술                          | 설명                                                                   |
| ----------------------------- | ---------------------------------------------------------------------- |
| `Kubernetes` / `Docker`       | 개인적인 쿠버네티스 구축 경험, 컨테이너 기술 학습                      |
| `Apache` / `Tomcat` / `Linux` | 리눅스 기반 서버에 WEB/WAS 구성, 서버 유지보수                         |
| `C`                           | 자료구조·알고리즘 학습, 웹 서버 구현, 스레드·프로세스·OS 스케줄링 학습 |

<div  class='br-line' style="height:3px;background:linear-gradient(to right,transparent,#7b2fff,#00bfff,transparent);margin:2em 0;border-radius:2px;"></div>

## 경력

| 기간              | 회사/교육                    | 역할                                                           |
| ----------------- | ---------------------------- | -------------------------------------------------------------- |
| 2024.11 ~ 2025.12 | 핸디코어<br>(재입사, 12개월) | [그룹웨어 솔루션 업체] PS팀 프로젝트                           |
| 2024.03 ~ 2024.08 | 크래프톤 정글<br>(5개월)     | [교육과정] 부트캠프 (CS, 알고리즘, 자료구조, Python, React 등) |
| 2022.03 ~ 2024.03 | 핸디코어<br>(24개월)         | [그룹웨어 솔루션 업체] CS팀 유지보수                           |
| 2021.09 ~ 2022.03 | 삼두정보기술<br>(6개월)      | [ERP 솔루션 업체] 연구원 및 PM보조                             |

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

<div  class='br-line' style="height:3px;background:linear-gradient(to right,transparent,#7b2fff,#00bfff,transparent);margin:2em 0;border-radius:2px;"></div>

{% include feature_row id="feature_row1" type="left" %}

<!-- {% include feature_row id="feature_row2" type="left" %} -->
<!-- {% include feature_row id="feature_row3" type="left" %} -->

<div  class='br-line' style="height:3px;background:linear-gradient(to right,transparent,#7b2fff,#00bfff,transparent);margin:2em 0;border-radius:2px;"></div>

## 프로젝트

| 프로젝트              | 기간              | 기술 스택                                     |
| --------------------- | ----------------- | --------------------------------------------- |
| 포켓몬 게시판(리뉴얼) | 2026.03           | Next.js, Firebase                             |
| 일일 미로 게임        | 2025.09           | Next.js, cloud flare d1                       |
| POKE-CODE             | 2024.06 ~ 2024.07 | React, Redux, TypeScript, Node.js, MySQL      |
| 포켓몬 게시판         | 2024.06           | Next.js, Firebase                             |
| Tarzan                | 2024.03           | Python, Flask, Jinja, JWT, BeautifulSoup, SSR |
| 하베스토리            | 2021.03 ~ 2021.10 | Spring Framework, JSP, JSTL, MySQL, jQuery    |
| 게임예약사이트        | 2020.10 ~ 2020.12 | Spring Framework, JSP, JSTL, MySQL, jQuery    |

<div  class='br-line' style="height:3px;background:linear-gradient(to right,transparent,#7b2fff,#00bfff,transparent);margin:2em 0;border-radius:2px;"></div>

## 프로젝트 종류(링크)
