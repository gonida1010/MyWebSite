# GonHome : 박영곤 개인 홈페이지

안녕하세요! HTML과 CSS를 활용하여 제작한 박영곤의 개인 홈페이지 및 포트폴리오 프로젝트입니다.

메인 페이지는 자주 사용하는 개발 도구 및 학습 사이트로 바로 이동할 수 있는 링크 허브 역할을 하며, 온라인 이력서 페이지로 연결됩니다.



## 🚀 주요 기능

* **메인 허브 (`index.html`):**
    * 자주 방문하는 사이트(Slack, Kaggle, GitHub, Figma 등) 링크 포털
    * 이력서, 블로그, 취미 페이지로 연결되는 반응형 이미지 메뉴
    * Google, Naver 등 주요 검색 엔진 바로가기 링크

* **온라인 이력서 (`Resume.html`):**
    * Flexbox를 활용한 2단 레이아웃의 깔끔한 이력서 페이지
    * `<progress>` 태그를 활용한 기술 숙련도 시각화
    * 메인 페이지로 돌아갈 수 있는 '홈으로 이동' 플로팅 버튼

* **반응형 디자인:**
    * CSS 미디어 쿼리를 사용하여 모바일 환경(767px 이하)에서도 편하게 볼 수 있도록 레이아웃이 세로로 정렬됩니다.

## 🛠️ 사용 기술

* **HTML5**
* **CSS3**
    * Flexbox를 이용한 레이아웃 구성
    * `@font-face`를 이용한 커스텀 웹 폰트(조선굴림) 적용
    * `transform` 및 `transition`을 활용한 hover 이펙트
    * `background-attachment: fixed`를 이용한 패럴랙스 스크롤 효과
    * 미디어 쿼리 (Media Queries)를 통한 반응형 웹 디자인

## 🗂️ 파일 구조

```
.
├── CSS/
│   ├── GonHome.css   (메인 페이지 스타일)
│   └── Resume.css    (이력서 페이지 스타일)
├── images/
│   ├── dog_2.ico       (파비콘)
│   ├── cat-9813484.jpg (프로필 사진)
│   ├── canyon-9765223.jpg (배경 이미지)
│   └── ... (메뉴 및 로고 이미지)
├── index.html          (메인 홈페이지)
└── Resume.html         (이력서 페이지)
```

## 🖥️ 실행 방법

이 프로젝트는 별도의 서버 설정 없이 브라우저에서 바로 실행할 수 있습니다.

1.  이 저장소를 로컬 환경에 클론(Clone)합니다.
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git)
    ```
2.  `index.html` 파일을 더블 클릭하여 웹 브라우저에서 엽니다.
