# 바닐라 JS 프로젝트 성능 개선
- url: https://yujin-first-app.web.app/

## 성능 개선 사후 보고서

### 1. 프로젝트 개요
#### 1.1 개선 이유
- Core Web Vitals 개선을 통한 사용자 경험 향상

#### 1.2 초기 성능 상태
##### 🎯 Lighthouse 점수
| 카테고리 | 점수 | 상태 |
|----------|------|------|
| Performance | 72% | 🟠 |
| Accessibility | 82% | 🟠 |
| Best Practices | 75% | 🟠 |
| SEO | 82% | 🟠 |
| PWA | 0% | 🔴 |

##### 📊 Core Web Vitals (2024)
| 메트릭 | 설명 | 측정값 | 상태 |
|--------|------|--------|------|
| LCP | Largest Contentful Paint | 14.63s | 🔴 |
| INP | Interaction to Next Paint | N/A | 🟢 |
| CLS | Cumulative Layout Shift | 0.011 | 🟢 |

##### 🖥️ PageSpeed Insights (데스크탑)
이미지 첨부


### 2. 성능 개선 방법
|  개선 항목  |  개선 이유  |  개선 방법  |  향상된 지표  |
|---|---|---|---|
|  이미지 최적화  |  LCP 개선  |  오버사이즈 이미지 조정, 이미지 형식 변환, 이미지 압축  |  LCP: 14.63s → 3.75s  |
|  <picture> 태그 사용  |  반응형 이미지 최적화  |  화면 크기에 따라 다른 이미지 표시  |  LCP: 3.75s → 2.78s, FCP 2.7s → 2.2s |
|  명시적 이미지 크기 설정  |  CLS 개선, 레이아웃 안정화  |  이미지에 width와 height 속성 추가  |    |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |


### 3. 개선 후 향상된 지표

### 4. 결론