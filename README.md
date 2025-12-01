# HRD KOREA 아카이브 페이지

## 📋 개요
HRD KOREA 아카이브 페이지는 대한민국 인적자원개발의 역사와 미래를 담은 온라인 플랫폼 소개 페이지입니다.

## 🎨 페이지 구성

### 1. 아카이브 헤더 섹션
- 그라데이션 배경 (빨강-파랑)
- 메인 타이틀 및 서브타이틀
- 주요 통계 정보 (운영 기간, 콘텐츠 수, 협력 기업)
- 애니메이션 효과

### 2. 왜 아카이브여야 하는지 섹션
6개의 핵심 가치를 카드 형식으로 제공:
- 📚 체계적인 지식 관리
- 🔍 트렌드 분석
- 🎯 맞춤형 솔루션
- 💡 지속적인 혁신
- 🌐 지식 공유 플랫폼
- 📈 성과 추적

### 3. 이벤트 섹션
3가지 이벤트 소개:
- 🎉 아카이브 오픈 기념 특별 할인 (진행 중)
- 🎁 신규 고객사 대상 패키지 제공 (예정)
- 🏆 우수 교육 담당자 시상 (상시 진행)

### 4. 신청 방법 섹션
- **3단계 신청 프로세스**:
  - 01: 신청서 작성
  - 02: 상담 예약
  - 03: 계약 및 교육 시작
  
- **연락 방법**:
  - 📞 전화 상담: 1588-0000
  - ✉️ 이메일: info@hrdkorea.or.kr
  - 💬 카카오톡: @HRD_KOREA

- **자주 묻는 질문 (FAQ)**: 3개 주요 질문 답변

## 🎯 주요 기능

### 반응형 디자인
- 데스크톱 (1024px 이상)
- 태블릿 (768px - 1024px)
- 모바일 (480px - 768px)
- 소형 모바일 (480px 이하)

### 인터랙티브 요소
- 스크롤 애니메이션 (Intersection Observer)
- 호버 효과
- FAQ 아코디언
- 하단 고정 신청 버튼

### 애니메이션
- Fade-in 효과
- 카드 호버 시 상승 효과
- 버튼 펄스 애니메이션
- 헤더 플로팅 효과

## 🚀 사용 방법

### 파일 구조
```
hrdkorea_archive/
├── archive.html          # 메인 HTML 파일
├── archive_style.css     # 스타일시트
└── README.md            # 문서
```

### 실행 방법
1. `archive.html` 파일을 웹 브라우저로 열기
2. 또는 로컬 서버에서 실행

### 이미지 경로 설정
현재 HRD Korea 로고는 다음 경로를 참조:
```html
<img src="../pocketedu/static/images/HRDKorea.png" alt="HRD Korea">
```

필요시 경로를 수정하세요.

### Google Form 연동
`openGoogleForm()` 함수에서 Google Form URL을 설정:
```javascript
function openGoogleForm() {
    window.open('https://forms.gle/your-google-form-link', '_blank');
}
```

## 🎨 디자인 특징

### 컬러 팔레트
- 주요 색상: `#ad272e` (빨강), `#0e2a6f` (파랑)
- 그라데이션: `linear-gradient(135deg, #ad272e, #0e2a6f)`
- 배경: `#f8f9fa` (연한 회색)
- 텍스트: `#333` (어두운 회색), `#666` (중간 회색)

### 타이포그래피
- 폰트: Noto Sans KR (Google Fonts)
- 제목: 700 weight
- 본문: 400 weight
- 설명: 300 weight

### 레이아웃
- 최대 너비: 1400px
- 패딩: 20px (모바일), 60px+ (데스크톱)
- 그리드: CSS Grid 사용 (auto-fit)

## 🔧 커스터마이징

### 색상 변경
`archive_style.css`에서 색상 변경:
```css
/* 주요 색상 */
#ad272e → 원하는 빨강 색상
#0e2a6f → 원하는 파랑 색상
```

### 콘텐츠 수정
`archive.html`에서 텍스트 내용 수정:
- 통계 숫자
- 이벤트 정보
- FAQ 내용
- 연락처 정보

### 섹션 추가/제거
HTML 구조를 유지하면서 `<section>` 태그 단위로 추가/제거 가능

## 📱 브라우저 지원
- Chrome (최신 버전)
- Firefox (최신 버전)
- Safari (최신 버전)
- Edge (최신 버전)

## 📝 TODO
- [ ] 실제 이미지 추가 (이벤트 섹션)
- [ ] Google Form URL 설정
- [ ] 로고 이미지 경로 확인
- [ ] 실제 연락처 정보 업데이트
- [ ] SEO 메타 태그 추가
- [ ] Open Graph 태그 추가

## 📞 문의
문의사항이 있으시면 HRD KOREA로 연락주세요.
- 전화: 1588-0000
- 이메일: info@hrdkorea.or.kr

## 📄 라이선스
© 2024 HRD KOREA. All rights reserved.

