# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 프로젝트 개요

GitHub Pages에 호스팅되는 Jekyll 블로그. **Minimal Mistakes** 테마(v4.26.2) 기반, 한국어 로케일(ko-KR) 설정.

- **사이트 URL:** https://deokgi-park.github.io
- **테마 스킨:** neon
- **댓글:** Disqus (shortname: deokgi-park)
- **검색:** Lunr (전체 콘텐츠 인덱싱)
- **애널리틱스:** Google Analytics (G-76LQFMWCJT)

## 개발 명령어

```bash
# 로컬 개발 서버 실행
bundle exec jekyll serve

# 또는 run.sh 사용
bash run.sh

# 빌트만 수행
bundle exec jekyll build

# 의존성 설치
bundle install
```

로컬 서버는 기본적으로 `http://localhost:4000`에서 실행됨.

## 아키텍처

### 콘텐츠 구조

| 디렉터리 | 용도 |
|---------|------|
| `_posts/` | 블로그 포스트 (날짜 기반 파일명: `YYYY-MM-DD-title.md`) |
| `_pages/` | 정적 페이지 (about, contact, 아카이브 등) |
| `_portfolio/` | 포트폴리오 컬렉션 |
| `_sample/` | 샘플 컬렉션 (테스트용) |

### 레이아웃 계층

```
single.html → default.html (header, footer, sidebar 포함)
archive-taxonomy.html → archive.html
collection.html → default.html
```

포스트와 페이지 대부분은 `layout: single` 사용.

### 주요 설정 파일

- **`_config.yml`** — 사이트 전체 설정 (테마, 플러그인, 컬렉션, 퍼머링크, 기본값)
- **`_data/navigation.yml`** — 상단 메뉴(`main`)와 사이드바 메뉴(`sidebar-category`) 정의
- **`_data/ui-text.yml`** — 테마 UI 텍스트 다국어 지원

### 포스트 기본값 (`_config.yml`의 defaults)

포스트는 자동으로 다음 설정 적용됨:
- `layout: single`
- `author_profile: true`
- `read_time: true`, `comments: true`, `share: true`, `related: true`

### 컬렉션

`_config.yml`에 정의된 컬렉션:
- `portfolio` — `output: true`, permalink: `/:collection/:path/`
- `sample` — `output: true`, permalink: `/:collection/:path/`

## 포스트 작성 시 Front Matter

```yaml
---
title: "제목"
excerpt: "미리보기 텍스트"
categories:
  - 카테고리명
tags:
  - 태그명
toc: true           # 목차 표시
toc_sticky: true    # 목차 고정
header:
  teaser: /assets/images/이미지.jpg
---
```

## CI/CD

`.github/workflows/build.yml` — master 브랜치 push 시 자동 빌드 (Ruby 3.2, Bundler 사용).
