# 🎬 YouTube 트렌드 분석기 Pro V6.18 Final

> 전문가급 YouTube 영상 분석 & 트렌드 검색 올인원 솔루션

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-6.18-blue.svg)](https://github.com/pumping365/youtube-search)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)

---

## 📖 소개

**YouTube 트렌드 분석기 Pro**는 YouTube Data API v3 기반의 전문적인 영상/채널 분석 도구입니다.

11개 전문 지표와 4종 차트를 활용하여 채널 성장성, 수익성, 참여율을 심층 분석하고, 11개국의 실시간 트렌드를 검색할 수 있습니다.

**단일 HTML 파일**로 구성되어 별도 설치 없이 브라우저에서 바로 실행 가능합니다.

---

## ✨ 주요 기능

### 🌍 **글로벌 검색**
- **11개국 지원**: 한국🇰🇷, 미국🇺🇸, 일본🇯🇵, 중국🇨🇳, 영국🇬🇧, 프랑스🇫🇷, 독일🇩🇪, 태국🇹🇭, 베트남🇻🇳, 싱가포르🇸🇬, 호주🇦🇺
- **실시간 트렌드**: 글로벌 핫 영상 & 급상승 영상
- **원클릭 카테고리**: 정치, 경제, 부동산, 드론, PET, 사회, IT 기술, 트렌드, 사건사고

### 📊 **11가지 전문 지표**
1. **구독자 점수** (최대 30점) - 채널 규모 평가
2. **조회수 점수** (최대 30점) - 콘텐츠 인기도
3. **참여율 점수** (최대 20점) - 좋아요/댓글 비율
4. **일관성 점수** (최대 20점) - 업로드 주기
5. **성장률 분석** - 구독자 증가 추세
6. **수익성 평가** - CPM 기반 예상 수익
7. **콘텐츠 품질** - 평균 조회수 대비 최근 성과
8. **채널 건강도** - 종합 채널 상태
9. **트렌드 적합도** - 인기 키워드 매칭
10. **시청 지속률** - 평균 시청 시간
11. **커뮤니티 활성도** - 댓글/공유 활동

### 📈 **4종 차트 시각화**
- **도넛 차트**: 채널 종합 점수 (S/A/B/C/D 등급)
- **레이더 차트**: 5개 핵심 지표 비교
- **바 차트**: 구독자 성장 추세
- **게이지 차트**: 참여율 실시간 표시

### 💰 **수익 예측 시스템**
- AI 기반 예상 수익 계산
- CPM 기반 수익성 분석
- 월간/연간 예상 수익 산출

### 🔍 **고급 검색 기능**
- **키워드 검색**: 영상 제목/설명 검색
- **필터링**: 최소 조회수/구독자 설정
- **정렬 옵션**: 관련성, 날짜, 조회수, 평점
- **기간 설정**: 최근 7/30/60/90일, 전체 기간
- **자동 번역**: 다국어 제목 자동 번역

### 💾 **데이터 관리**
- **즐겨찾기**: 로컬 저장소에 채널 저장
- **CSV 내보내기**: 분석 결과 다운로드
- **API 키 관리**: 로컬 저장소에 안전 보관

---

## 🚀 빠른 시작

### 1️⃣ **다운로드**

최신 버전 다운로드:
- [📥 V6.18 Final (최신)](youtube_search_ultimate_final_v6.18_final.html)
- [📥 V4R3 (안정 버전)](v4r3-index.html)

### 2️⃣ **브라우저 실행**

HTML 파일을 브라우저로 열기:
- **Windows**: 파일 더블클릭 또는 우클릭 → 연결 프로그램 → Chrome/Edge
- **Mac**: 파일 더블클릭 또는 우클릭 → 연결 프로그램 → Safari/Chrome

**지원 브라우저:**
- ✅ Chrome 90+ (권장)
- ✅ Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+

### 3️⃣ **API 키 설정**

1. [Google Cloud Console](https://console.cloud.google.com/) 접속
2. 새 프로젝트 생성
3. **YouTube Data API v3** 활성화
4. **API 키 생성** (사용자 인증 정보 → API 키)
5. 분석기에서 **[설정]** 버튼 클릭 → API 키 입력

**API 키 무료 할당량:**
- 일일 10,000 쿼터
- 검색 1회 = 100 쿼터
- 약 100회 검색/일

### 4️⃣ **검색 시작**

1. **국가 선택**: 상단 국가 버튼 클릭 (예: 🇰🇷 KR)
2. **키워드 입력**: 검색 바에 원하는 키워드 입력
3. **검색 버튼 클릭**: 🔍 검색 버튼 클릭
4. **결과 확인**: 영상 카드 및 채널 분석 확인

---

## 📸 스크린샷

### 메인 화면
![메인 화면](docs/screenshots/main-screen.png)

### 채널 분석 패널
![채널 분석](docs/screenshots/channel-analysis.png)

### 차트 시각화
![차트](docs/screenshots/charts.png)

---

## 📥 다운로드

### **HTML 파일**
| 버전 | 파일명 | 크기 | 설명 |
|------|--------|------|------|
| **V6.18 Final** | [youtube_search_ultimate_final_v6.18_final.html](youtube_search_ultimate_final_v6.18_final.html) | 86KB | ✅ 최신 버전 (권장) |
| V4R3 | [v4r3-index.html](v4r3-index.html) | 80KB | 안정 버전 |
| V4R3 (중복) | [V4R3youtube_search index.HTML](V4R3youtube_search%20index.HTML) | 80KB | 백업 파일 |

### **문서**
- [📄 README PDF 다운로드](YouTube_Trend_Analyzer_V6.18_README.pdf) (247KB, 20페이지)

---

## 🛠️ 기술 스택

| 기술 | 버전 | 용도 |
|------|------|------|
| **HTML5** | - | 구조 및 레이아웃 |
| **CSS3** | - | 스타일링 & 애니메이션 |
| **JavaScript (ES6+)** | - | 로직 & API 연동 |
| **Chart.js** | 4.4.0 | 차트 시각화 |
| **YouTube Data API v3** | v3 | 영상/채널 데이터 |
| **LocalStorage API** | - | 데이터 저장 |

---

## 📚 사용 방법

### 🔍 **기본 검색**

```
1. 국가 선택: 🇰🇷 KR 클릭
2. 키워드 입력: "드론"
3. 검색 버튼 클릭
4. 결과 확인
```

### 🎯 **고급 검색**

```
1. 최소 조회수 설정: 10000
2. 최소 구독자 설정: 1000
3. 정렬: viewCount (조회수 순)
4. 최대 결과: 24개
5. 검색 버튼 클릭
```

### 📊 **채널 분석**

```
1. 영상 카드에서 [채널 분석] 버튼 클릭
2. 오른쪽 분석 패널 확인
3. 4종 차트 확인:
   - 도넛 차트: 종합 점수
   - 레이더 차트: 5개 지표
   - 바 차트: 성장 추세
   - 게이지 차트: 참여율
4. 전문가 분석 리포트 확인
```

### 💾 **즐겨찾기 & 내보내기**

```
1. 영상 카드에서 ⭐ 버튼 클릭 (즐겨찾기 추가)
2. 상단 [CSV 내보내기] 버튼 클릭
3. 파일명 입력 (예: youtube_favorites.csv)
4. 다운로드 완료
```

---

## ⚙️ 고급 설정

### **API 쿼터 관리**

**일일 할당량**: 10,000 쿼터

| 작업 | 소모 쿼터 | 가능 횟수 |
|------|----------|----------|
| 검색 | 100 | 100회/일 |
| 영상 정보 | 1 | 10,000회/일 |
| 채널 정보 | 1 | 10,000회/일 |

**절약 팁:**
- ✅ 최대 결과 수를 12개로 제한
- ✅ 즐겨찾기 활용 (재검색 불필요)
- ✅ CSV 내보내기로 데이터 보관

### **로컬 저장소 키**

| 키 | 저장 내용 | 위치 |
|-----|----------|------|
| `yt_api_key` | YouTube API 키 | LocalStorage |
| `yt_favorites` | 즐겨찾기 목록 | LocalStorage |
| `yt_auto_translate` | 자동 번역 설정 | LocalStorage |

---

## 🎓 활용 사례

### 1️⃣ **콘텐츠 크리에이터**
- 경쟁 채널 분석
- 트렌드 키워드 발굴
- 수익성 평가

### 2️⃣ **마케터**
- 인플루언서 발굴
- 캠페인 성과 분석
- 타겟 채널 선정

### 3️⃣ **연구자**
- YouTube 트렌드 연구
- 데이터 수집 및 분석
- 시장 조사

### 4️⃣ **투자자**
- 채널 가치 평가
- 성장 가능성 분석
- 수익성 예측

---

## 🌟 버전 히스토리

| 버전 | 날짜 | 주요 변경사항 |
|------|------|---------------|
| **V6.18 Final** | 2026-01-26 | ✅ 최신 버전 (권장)<br>- 11개 지표 완성<br>- 하단 카드 간격 최적화<br>- 최소화 버튼 제거<br>- 반응형 레이아웃 개선 |
| V6.17 | 2026-01-26 | - 버튼 기능 복구<br>- V6.14 기반 안정화 |
| V6.16 | 2026-01-25 | - 카드 디자인 개선<br>- 하단 여백 추가 |
| V6.14 | 2026-01-24 | - 백업 버전 (100% 작동 보장)<br>- 모든 버튼 정상 작동 |
| V4R3 | 2026-01-20 | - 안정 버전<br>- 기본 검색 기능 |

---

## ❓ FAQ (자주 묻는 질문)

### Q1. **API 키 없이 사용 가능한가요?**
❌ 아니요. YouTube Data API v3 키가 필수입니다.  
✅ [무료로 발급받기](https://console.cloud.google.com/)

### Q2. **오프라인에서 작동하나요?**
❌ 아니요. 인터넷 연결이 필요합니다.  
✅ YouTube API 및 Chart.js CDN 연결 필요

### Q3. **모바일에서도 사용 가능한가요?**
✅ 예! 반응형 디자인으로 모바일 브라우저 지원  
⚠️ 큰 화면(태블릿/PC)에서 최적화됨

### Q4. **데이터가 어디에 저장되나요?**
✅ 로컬 저장소(LocalStorage)에만 저장  
✅ 외부 서버에 전송되지 않음 (보안)

### Q5. **API 쿼터 초과 시 어떻게 하나요?**
⏰ 다음날 자정(UTC)에 자동 초기화  
💡 여러 API 키 사용 (프로젝트별 키 발급)

### Q6. **차트가 표시되지 않아요**
1. ✅ 인터넷 연결 확인 (Chart.js CDN)
2. ✅ 브라우저 캐시 삭제
3. ✅ F12 → Console 에러 확인

---

## 🔒 보안 & 개인정보

### **데이터 보안**
- ✅ **로컬 저장소만 사용** (외부 서버 전송 없음)
- ✅ **API 키 암호화** 없음 (로컬 저장소에 평문 저장)
- ⚠️ **API 키 공유 금지** (개인 키는 절대 공개하지 마세요)

### **개인정보 처리**
- ❌ 사용자 정보 수집 안 함
- ❌ 쿠키 사용 안 함
- ❌ 외부 추적 코드 없음

### **권장 사항**
1. ✅ API 키를 GitHub에 커밋하지 마세요
2. ✅ API 키에 사용 제한 설정 (IP/도메인)
3. ✅ 정기적으로 API 키 갱신

---

## 📜 라이선스

MIT License

Copyright (c) 2026 pumping365

이 소프트웨어는 MIT 라이선스에 따라 배포됩니다.  
자유롭게 사용, 수정, 배포 가능하며, 상업적 사용도 허용됩니다.

**조건:**
- 원저작자 표시 필수
- 라이선스 전문 포함 필수

**면책:**
- 소프트웨어는 "있는 그대로" 제공됨
- 어떠한 보증도 제공하지 않음

[전문 보기](LICENSE)

---

## 🤝 기여하기

프로젝트 개선에 참여하고 싶으시다면:

1. 🍴 Fork this repository
2. 🔀 Create a new branch (`git checkout -b feature/amazing-feature`)
3. ✅ Commit your changes (`git commit -m 'Add amazing feature'`)
4. 📤 Push to the branch (`git push origin feature/amazing-feature`)
5. 🎉 Open a Pull Request

**기여 가이드라인:**
- ✅ 코드 스타일 유지 (들여쓰기 2칸)
- ✅ 주석 작성 (한글 또는 영어)
- ✅ 테스트 완료 후 PR 제출
- ✅ 변경사항 상세 설명

---

## 💬 문의 & 지원

**개발자**: pumping365  
**저장소**: [github.com/pumping365/youtube-search](https://github.com/pumping365/youtube-search)

**문의 방법:**
- 🐛 버그 신고: [Issues](https://github.com/pumping365/youtube-search/issues)
- 💡 기능 제안: [Issues](https://github.com/pumping365/youtube-search/issues)
- 📧 이메일: (추가 예정)

---

## 🙏 감사의 말

이 프로젝트는 다음 오픈소스 프로젝트를 사용합니다:

- [Chart.js](https://www.chartjs.org/) - 차트 시각화 라이브러리
- [YouTube Data API v3](https://developers.google.com/youtube/v3) - Google의 YouTube API
- [Font Awesome](https://fontawesome.com/) - 아이콘 라이브러리 (일부 버전)

---

## 📊 프로젝트 통계

![GitHub stars](https://img.shields.io/github/stars/pumping365/youtube-search?style=social)
![GitHub forks](https://img.shields.io/github/forks/pumping365/youtube-search?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/pumping365/youtube-search?style=social)

---

## 🚀 로드맵

### **현재 버전 (V6.18)**
- ✅ 11개 지표 완성
- ✅ 11개국 지원
- ✅ 4종 차트 시각화
- ✅ CSV 내보내기

### **향후 계획 (V7.0)**
- 🔜 다크 모드 지원
- 🔜 더 많은 국가 추가 (20개국)
- 🔜 영상 비교 기능
- 🔜 자동 리포트 생성
- 🔜 모바일 앱 버전

---

<div align="center">

### ⭐ 이 프로젝트가 도움이 되셨다면 Star를 눌러주세요!

**Made with ❤️ by pumping365**

[⬆️ 맨 위로 돌아가기](#-youtube-트렌드-분석기-pro-v618-final)

</div>
