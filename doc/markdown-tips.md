# Jekyll 마크다운 작성 팁 (Minimal Mistakes)

## Front Matter

```yaml
---
title: "제목"
date: 2026-04-06
categories: daily          # 카테고리 (단일)
categories: [dev, study]   # 카테고리 (복수)
tags: [tag1, tag2]
excerpt: "블로그 목록에 표시될 미리보기 텍스트"
toc: true                  # 목차 표시
toc_sticky: true           # 스크롤해도 목차 고정
toc_label: "목차"          # 목차 제목 커스텀
---
```

---

## 이미지

### 기본
```markdown
![이미지 설명](이미지경로)
```

### 크기 조정
```markdown
![설명](image.png){: style="height: 300px;"}
![설명](image.png){: style="width: 400px;"}
![설명](image.png){: style="width: 400px; height: 300px;"}
```

> `height: auto` 는 Minimal Mistakes CSS에 의해 무시됨 — 반드시 `style=""` 인라인 방식 사용

### 정렬
```markdown
![설명](image.png){: .align-center}   # 중앙
![설명](image.png){: .align-left}     # 좌측
![설명](image.png){: .align-right}    # 우측
```

### 크기 + 정렬 동시 적용
```markdown
![설명](image.png){: .align-center style="height: 300px;"}
```

---

## 코드 블록

````markdown
```언어명
코드
```
````

| 언어명 | 용도 |
|--------|------|
| `bash` | 터미널 명령어 |
| `text` | 에러 로그, 일반 텍스트 출력 |
| `javascript` / `js` | JavaScript |
| `typescript` / `ts` | TypeScript |
| `python` | Python |
| `yaml` | 설정 파일 |
| `json` | JSON |
| `html` | HTML |
| `css` | CSS |
| `sql` | SQL |
| `markdown` | 마크다운 예시 |

### 인라인 코드
```markdown
`파일명`, `변수명`, `명령어` 등에 사용
```

---

## 텍스트 강조

```markdown
**굵게** — 핵심 키워드, 중요 개념
*기울임* — 용어, 약한 강조
~~취소선~~
```

---

## 인용구

```markdown
> 한 줄 인용

> 여러 줄 인용
>
> 두 번째 줄
```

---

## 목록

```markdown
# 순서 없음
- 항목
  - 중첩 항목

# 순서 있음
1. 첫 번째
2. 두 번째
```

---

## 표

```markdown
| 헤더1 | 헤더2 | 헤더3 |
|-------|:-----:|------:|
| 좌측  | 중앙  |  우측 |
```

---

## 링크

```markdown
[표시 텍스트](URL)
[표시 텍스트](URL){: target="_blank"}  # 새 탭에서 열기
```

---

## 줄바꿈

| 방법 | 문법 | 용도 |
|------|------|------|
| 단락 나누기 | 빈 줄 | 문단 구분 |
| 강제 줄바꿈 | `<br>` | 같은 단락 내 줄바꿈 |
| 섹션 구분 | `---` | 제목 앞 시각적 구분선 |

```markdown
첫 번째 단락

두 번째 단락 (빈 줄로 구분)

한 줄<br>
바로 다음 줄

---

# 다음 섹션
```

> 스페이스 2개 + 엔터 방식은 에디터가 자동 제거하는 경우가 많아 `<br>` 권장

---

## 수평선

```markdown
---
```

---

## 목차용 제목 구조

```markdown
# H1 — 페이지 최상위 (포스트 제목과 겹치므로 1개만)
## H2 — 주요 섹션 (toc에 표시됨)
### H3 — 소섹션
```

---

## 링크 포스트카드 (썸네일형)

마크다운 파일에 HTML 블록으로 직접 삽입해서 사용.

```html
<a href="URL" target="_blank" style="display:flex; border:1px solid #e1e4e8; border-radius:8px; overflow:hidden; text-decoration:none; color:inherit; margin:16px 0; background:#fff; box-shadow:0 1px 3px rgba(0,0,0,0.08);">
  <img src="썸네일_URL" alt="썸네일" style="width:120px; height:120px; object-fit:cover; flex-shrink:0;">
  <div style="padding:12px 16px; display:flex; flex-direction:column; justify-content:center; gap:6px; overflow:hidden;">
    <div style="font-weight:bold; font-size:0.95em; white-space:nowrap; overflow:hidden; text-overflow:ellipsis;">링크 제목</div>
    <div style="font-size:0.82em; color:#555; line-height:1.4; display:-webkit-box; -webkit-line-clamp:2; -webkit-box-orient:vertical; overflow:hidden;">링크 설명</div>
    <div style="font-size:0.75em; color:#888;">🔗 example.com</div>
  </div>
</a>
```

| 자리표시자 | 내용 |
|-----------|------|
| `URL` | 이동할 링크 |
| `썸네일_URL` | 이미지 경로 또는 외부 URL |
| `링크 제목` | 카드 제목 |
| `링크 설명` | 2줄로 자동 말줄임 |
| `example.com` | 출처 도메인 |
