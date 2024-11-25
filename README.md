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
|  오버사이즈 이미지 조정  |  LCP 개선  |  이미지 사이즈 줄임  |  LCP: 14.63s →  12.46s  |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
|   |   |   |   |
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