# 🚀 프론트엔드 개발자 포트폴리오

React.js 전문 프론트엔드 개발자를 위한 모던하고 반응형인 포트폴리오 웹사이트입니다.

## ✨ 주요 기능

- **반응형 디자인**: 모든 기기에서 완벽하게 작동
- **모던한 UI/UX**: 그라디언트와 애니메이션 효과
- **다크 모드**: 테마 전환 기능
- **부드러운 애니메이션**: 스크롤 애니메이션과 호버 효과
- **경력 타임라인**: 시각적인 경력 사항 표시
- **실제 프로젝트 링크**: 실제 구현된 프로젝트들로 구성
- **인터랙티브 요소**: 3D 카드 효과, 타이핑 효과
- **연락처 폼**: 유효성 검사가 포함된 폼
- **SEO 최적화**: 검색 엔진 최적화
- **접근성**: 키보드 네비게이션 지원

## 🛠️ 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: 그리드, 플렉스박스, 애니메이션
- **JavaScript**: ES6+, 모던 JavaScript
- **Font Awesome**: 아이콘
- **Google Fonts**: 한국어 폰트 (Noto Sans KR)

## 📁 프로젝트 구조

```
포트폴리오/
├── index.html              # 메인 HTML 파일
├── static/
│   ├── css/
│   │   └── portfolio.css   # 메인 스타일시트
│   ├── js/
│   │   └── portfolio.js    # 메인 JavaScript
│   └── media/
│       ├── profile.jpg     # 프로필 이미지
│       ├── project1.jpg    # 프로젝트 이미지들
│       ├── project2.jpg
│       └── project3.jpg
├── favicon.ico             # 파비콘
└── README.md              # 이 파일
```

## 🎯 포트폴리오 특징

### 실제 경력 기반 구성
- **(주) 케이스랩** (2024.08 - 현재): 다양한 웹 애플리케이션 개발
- **(주) 피씨엔씨** (2023.02 - 2024.05): 에듀테크 플랫폼 개발

### 실제 프로젝트 포함
- **아이큐 비타민**: 심리 검사 플랫폼 (https://iqvitamininside.com/)
- **오톡 쇼핑몰**: 천연 제품 쇼핑몰 (https://www.otok.co.kr/)
- **별별신당**: 점집 정보 플랫폼 (https://www.byuldang.com/)
- **데이페이**: 카메라 렌탈 플랫폼 (다국어 지원)
- **한국어 교육 플랫폼**: LMS 시스템
- **React Native 앱**: 독서 지원 모바일 앱

### 기술 전문성
- **React.js**: 메인 프레임워크
- **Vue.js**: 관리자 페이지 개발
- **React Native**: 모바일 앱 개발
- **상태 관리**: Zustand 활용
- **API 통합**: 결제, 지도, 소셜 로그인
- **다국어 지원**: i18n 시스템 구축

## 🎨 커스터마이징 가이드

### 1. 개인 정보 수정

`index.html` 파일에서 다음 내용들을 수정하세요:

```html
<!-- 페이지 제목 -->
<title>포트폴리오 | 프론트엔드 개발자</title>

<!-- 히어로 섹션 -->
<h1 class="hero-title">
    안녕하세요, 저는 <span class="highlight">React.js 전문</span> 프론트엔드 개발자입니다
</h1>

<!-- 연락처 정보 -->
<span>your.email@example.com</span>
<span>010-1234-5678</span>
```

### 2. 경력 정보 수정

경력 섹션에서 본인의 경력을 수정하세요:

```html
<div class="timeline-item">
    <div class="timeline-date">2024.08 - 현재</div>
    <div class="timeline-content">
        <h3>회사명</h3>
        <h4>직책</h4>
        <p>회사 설명</p>
        <ul>
            <li>주요 업무 1</li>
            <li>주요 업무 2</li>
        </ul>
    </div>
</div>
```

### 3. 프로젝트 정보 수정

프로젝트 섹션에서 각 프로젝트의 정보를 수정하세요:

```html
<div class="project-card">
    <div class="project-image">
        <img src="/static/media/project1.jpg" alt="프로젝트명">
        <div class="project-overlay">
            <a href="실제URL" class="project-link" target="_blank">
                <i class="fas fa-external-link-alt"></i>
            </a>
        </div>
    </div>
    <div class="project-content">
        <h3>프로젝트명</h3>
        <p>프로젝트 설명</p>
        <div class="project-tech">
            <span>React.js</span>
            <span>기술2</span>
        </div>
    </div>
</div>
```

### 4. 기술 스택 수정

기술 섹션에서 본인의 기술 스택을 수정하세요:

```html
<div class="skill-item">
    <i class="fab fa-react"></i>
    <span>React.js</span>
</div>
```

### 5. 색상 테마 변경

`static/css/portfolio.css` 파일의 CSS 변수를 수정하여 색상을 변경할 수 있습니다:

```css
:root {
    --primary-color: #2563eb;        /* 메인 색상 */
    --secondary-color: #64748b;      /* 보조 색상 */
    --accent-color: #f59e0b;         /* 강조 색상 */
    --gradient-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

## 🚀 GitHub Pages 배포

1. **저장소 생성**: `username.github.io` 이름으로 저장소 생성
2. **파일 업로드**: 모든 파일을 저장소에 업로드
3. **GitHub Pages 활성화**: 
   - Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
4. **배포 확인**: `https://username.github.io`에서 확인

## 💡 프론트엔드 개발자를 위한 팁

### 기술 스택 강조
- React.js 중심의 기술 스택 구성
- 실제 사용한 라이브러리 및 도구 명시
- API 통합 경험 강조

### 프로젝트 다양성 표현
- 다양한 도메인 경험 (에듀테크, 쇼핑몰, 플랫폼)
- 웹/모바일 모두 경험
- 프론트엔드부터 관리자 페이지까지

### 성과 중심 작성
- 구체적인 기능 구현 내용
- 사용자 경험 개선 사례
- 기술적 문제 해결 경험

## 🔧 추가 기능 구현 아이디어

### 기술 블로그 연동
```javascript
// 기술 블로그 RSS 피드 연동
fetch('https://api.rss2json.com/v1/api.json?rss_url=블로그RSS주소')
    .then(response => response.json())
    .then(data => {
        // 최신 글 표시
    });
```

### GitHub 활동 통계
```javascript
// GitHub API 활용
fetch('https://api.github.com/users/username/repos')
    .then(response => response.json())
    .then(repos => {
        // 프로젝트 통계 표시
    });
```

### 실시간 기술 트렌드
```javascript
// 기술 스택별 트렌드 표시
const techTrends = {
    'React.js': '95%',
    'Vue.js': '80%',
    'TypeScript': '90%'
};
```

## 📱 반응형 브레이크포인트

- **데스크톱**: 1200px 이상
- **태블릿**: 768px - 1199px
- **모바일**: 767px 이하

## 🎯 브라우저 지원

- Chrome (최신 버전)
- Firefox (최신 버전)
- Safari (최신 버전)
- Edge (최신 버전)

## 📈 SEO 최적화

### 메타 태그 설정
```html
<meta name="description" content="React.js 전문 프론트엔드 개발자 - 혁신적인 웹 솔루션을 제공합니다">
<meta name="keywords" content="React.js, 프론트엔드, 개발자, 웹개발, JavaScript">
```

### 구조화된 데이터
```json
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "프론트엔드 개발자",
  "jobTitle": "Front-End Developer",
  "description": "React.js 전문 프론트엔드 개발자"
}
```

## 📞 지원 및 문의

질문이나 문제가 있으시면 이슈를 생성해주세요.

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

---

**성공적인 프론트엔드 개발자 포트폴리오를 만들어보세요! 🎉**

### 🌟 포트폴리오 활용 팁

1. **실제 프로젝트 링크**: 모든 프로젝트에 실제 작동하는 링크를 포함
2. **기술적 깊이**: 단순 나열이 아닌 구체적인 구현 내용 설명
3. **성과 중심**: 사용자 경험 개선, 성능 최적화 등 구체적 성과 명시
4. **지속적 업데이트**: 새로운 프로젝트와 기술 학습 내용 지속 반영
