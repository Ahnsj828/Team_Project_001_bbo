# 💄에뛰드하우스 클론코딩

<img src="./etude.gif" alt="etude"/><br />

- 기간 : 2024.2.16 ~ 3.29
- 배포 URL : [에뛰드하우스](https://etude-boo-0329.web.app/)

<br /><br />

## 😃프로젝트 소개

화장품에 대한 관심을 바탕으로 에뛰드하우스 웹 페이지를 클론 코딩하는 프로젝트를 수행했습니다. 에뛰드하우스의 웹 페이지는 다양한 시각적 효과와 인터랙션을 통해 우수한 사용자 경험을 제공하고 있습니다. 본 프로젝트의 목표는 이러한 복잡한 기능들을 정확하게 재현하고, 사용자 친화적인 UI/UX를 구현함으로써 실질적인 기술적 도전을 해결하는 것이었습니다. 이를 통해 최신 웹 디자인 트렌드와 기술을 체계적으로 학습하고 적용하였습니다.

<br /><br />

## 😎 개발 환경

#### UI/UX 설계

- **Figma** : UI/UX 설계 및 프로토타입 제작을 위한 도구입니다. 사용자 인터페이스와 사용자 경험을 시각적으로 설계하고 문서화했습니다.

#### 정보 구조 및 기능 정의

- **Figma** : 정보 구조(IA), 작업 분해 구조(WBS), 기능 정의서 작성을 위한 도구입니다. 프로젝트의 요구 사항과 기능을 명확히 정의하고 계획했습니다.

#### 버전 관리 및 이슈 추적

- **GitHub** : 코드 버전 관리 및 협업을 위한 플랫폼입니다. 리포지토리의 소스 코드를 관리하고, 팀원 간의 협업을 지원합니다.
- **GitHub Issues** : 버그, 기능 요청, 작업 항목 등을 추적하고 관리하는 도구입니다. 프로젝트의 진행 상황을 효율적으로 관리합니다.

#### 프론트엔드 기술

- **HTML5** : 웹 페이지의 구조와 콘텐츠를 작성하는 데 사용되었습니다.
- **CSS3** : 페이지 스타일링과 시각적 효과 구현을 위해 사용되었습니다.
- **JavaScript** : 사용자 인터랙션과 동적 기능을 구현하는 데 사용되었습니다.

#### 배포 환경

- **Firebase** : 웹 애플리케이션의 배포와 호스팅을 위한 플랫폼입니다. 안정적이고 효율적인 웹 사이트 배포와 관리를 지원합니다.

<br /><br />

## 🧐 사용 기술과 브랜치 전략

#### 사용 기술

- **HTML5** : 웹 콘텐츠의 구조와 레이아웃을 구성했습니다. 페이지의 골격을 정의하고 콘텐츠를 배치합니다.
- **CSS3** : 웹 콘텐츠의 디자인과 스타일링을 담당했습니다. 시각적 효과와 페이지 레이아웃을 구현합니다.
- **JavaScript** : 동적 기능과 사용자 인터랙션을 구현했습니다. 슬라이드, 스크롤 이벤트 등 다양한 기능을 추가했습니다.

#### 브랜치 전략

- **main** : 최종적으로 배포 가능한 안정된 버전의 코드를 유지했습니다.
- **development** : 새로운 기능 추가와 버그 수정을 위한 브랜치로, 작업이 완료된 후 `main` 브랜치에 병합 했습니다.
- **feature/[기능명]** : 팀원별 개인 브랜치로, 개발이 완료된 후 `development` 브랜치에 병합하여 전체 프로젝트에 통합했습니다.
  <!-- - **hotfix/[수정명]** : 긴급한 버그 수정 작업을 위한 브랜치입니다. 수정 완료 후 `main`과 `development` 브랜치에 병합됩니다. -->
  <!-- - **release/[버전명]** : 배포 준비가 완료된 기능을 포함한 브랜치입니다. 최종 테스트 후 `main`과 `development` 브랜치에 병합됩니다. -->

<br /><br />

## 📁 프로젝트 구조

/about # 'about' 페이지 관련 파일<br />
│<br />
├── about.html # 'about' 페이지 HTML 파일<br />
└── about.css # 'about' 페이지 스타일 파일<br />
<br />
/foundation # 'foundation' 페이지 관련 파일<br />
│<br />
├── foundation.html # 'foundation' 페이지 HTML 파일<br />
└── foundation.css # 'foundation' 페이지 스타일 파일<br />
<br />
/Header_image # 헤더 이미지 파일<br />
│<br />
├── header-image1.png # 헤더 이미지 파일<br />
└── header-image2.png # 헤더 이미지 파일<br />
<br />
/main-images # 메인 페이지 전용 이미지 파일<br />
│<br />
├── main-image1.png # 메인 이미지 파일<br />
└── main-image2.png # 메인 이미지 파일<br />
<br />
/makeup # 'makeup' 페이지 관련 파일<br />
│<br />
├── makeup.html # 'makeup' 페이지 HTML 파일<br />
└── makeup.css # 'makeup' 페이지 스타일 파일<br />
<br />
/product_inner # 'product_inner' 페이지 관련 파일<br />
│<br />
├── product_inner.html # 'product_inner' 페이지 HTML 파일<br />
└── product_inner.css # 'product_inner' 페이지 스타일 파일<br />
<br />
/productAll # 'productAll' 페이지 관련 파일<br />
│<br />
├── productAll.html # 'productAll' 페이지 HTML 파일<br />
└── productAll.css # 'productAll' 페이지 스타일 파일<br />
<br />
/store # 'store' 페이지 관련 파일<br />
│<br />
├── store.html # 'store' 페이지 HTML 파일<br />
└── store.css # 'store' 페이지 스타일 파일<br />
<br />
/Sofiafont # 폰트 파일<br />
│<br />
├── Sofia-Regular.ttf # Sofia Regular 폰트 파일<br />
└── Sofia-Bold.ttf # Sofia Bold 폰트 파일<br />
<br />
etude.gif # 프로젝트 설명용 GIF 파일<br />
etude2023-180x180-1.png # 파비콘<br />
<br />
index.html # 메인 페이지 HTML 파일<br />
README.md # 프로젝트 설명 및 문서<br />
script.js # 메인 페이지 자바스크립트 파일<br />
style.css # 메인 페이지 스타일 파일<br />

<br /><br />

## 💡 주요 기능

- **슬라이드쇼** : 다양한 화장품 제품을 시각적으로 매력적으로 보여주는 슬라이드쇼 기능을 구현하였습니다.

- **마우스오버 효과** : 제품 이미지나 정보에 마우스를 올리면 추가적인 정보나 시각적 효과가 표시됩니다.

- **상세 페이지** : 각 제품의 상세 정보를 제공하는 페이지를 구현하여 사용자 경험을 향상시킵니다.

- **검색 및 필터링** : 사용자가 원하는 제품을 쉽게 찾을 수 있도록 검색 및 필터링 기능을 제공합니다.

- **반응형 디자인** : 다양한 화면 크기와 디바이스에서 최적화된 사용자 경험을 제공하기 위한 반응형 디자인을 적용하였습니다.
