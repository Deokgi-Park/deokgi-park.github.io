# Minimal Mistakes 유틸리티 클래스 & 헬퍼 정리

## 1. 버튼 (Button)

### 스타일
| 클래스 | 설명 |
|--------|------|
| `btn btn--primary` | 기본 강조 |
| `btn btn--success` | 성공 (초록) |
| `btn btn--warning` | 경고 (노랑) |
| `btn btn--danger` | 위험 (빨강) |
| `btn btn--info` | 정보 (파랑) |
| `btn btn--inverse` | 반전 (어두운) |
| `btn btn--light-outline` | 아웃라인 |

### 크기
| 클래스 | 설명 |
|--------|------|
| `btn--x-large` | 특대 |
| `btn--large` | 대 |
| `btn--small` | 소 |

### 사용 예시
```html
<a href="/" class="btn btn--primary btn--large">홈으로</a>
<a href="/" class="btn btn--danger btn--small">삭제</a>
```

---

## 2. 노티스 박스 (Notice)

| 클래스 | 설명 |
|--------|------|
| `notice` | 기본 |
| `notice--primary` | 강조 |
| `notice--info` | 정보 |
| `notice--warning` | 경고 |
| `notice--success` | 성공 |
| `notice--danger` | 위험/오류 |

### 사용 예시
```markdown
일반 안내 내용입니다.
{: .notice}

**주의!** 경고 내용입니다.
{: .notice--warning}

**완료!** 성공했습니다.
{: .notice--success}

**오류!** 실패했습니다.
{: .notice--danger}
```

---

## 3. 텍스트 정렬 (Text Alignment)

| 클래스 | 설명 |
|--------|------|
| `text-left` | 왼쪽 정렬 |
| `text-center` | 가운데 정렬 |
| `text-right` | 오른쪽 정렬 |
| `text-justify` | 양쪽 정렬 |
| `text-nowrap` | 줄바꿈 방지 |

### 사용 예시
```markdown
가운데 정렬 텍스트입니다.
{: .text-center}

오른쪽 정렬 텍스트입니다.
{: .text-right}
```

---

## 4. 이미지 정렬 (Image Alignment)

| 클래스 | 설명 |
|--------|------|
| `align-left` | 왼쪽 플로팅 |
| `align-center` | 가운데 |
| `align-right` | 오른쪽 플로팅 |
| `full` | 컨테이너 밖으로 확장 |

### 사용 예시
```markdown
![이미지](/assets/images/example.jpg){: .align-center}
![이미지](/assets/images/example.jpg){: .align-left}
![이미지](/assets/images/example.jpg){: .align-right}
```

---

## 5. include 헬퍼

### figure (캡션 이미지)
```liquid
{% include figure image_path="/assets/images/example.jpg" caption="이미지 설명" %}
```

### gallery (이미지 갤러리)
front matter에 gallery 정의 후 사용:
```yaml
gallery:
  - url: /assets/images/example1.jpg
    image_path: /assets/images/example1.jpg
    alt: "이미지1"
  - url: /assets/images/example2.jpg
    image_path: /assets/images/example2.jpg
    alt: "이미지2"
```
```liquid
{% include gallery caption="갤러리 설명" %}
{% include gallery layout="half" %}   <!-- 2열 -->
{% include gallery layout="third" %}  <!-- 3열 -->
```

### video (반응형 영상 삽입)
```liquid
{% include video id="유튜브영상ID" provider="youtube" %}
{% include video id="비메오영상ID" provider="vimeo" %}
```

### feature_row (스플래시 페이지용 카드)
front matter에 feature_row 정의 후 사용:
```yaml
feature_row:
  - image_path: /assets/images/example.jpg
    title: "제목"
    excerpt: "설명"
    url: "/link/"
    btn_label: "더보기"
    btn_class: "btn--primary"
```
```liquid
{% include feature_row %}
{% include feature_row type="left" %}   <!-- 이미지 왼쪽 -->
{% include feature_row type="right" %}  <!-- 이미지 오른쪽 -->
{% include feature_row type="center" %} <!-- 가운데 -->
```
