# adidas
# 아디다스 - 웹 페이지 프로젝트


## 프로젝트 소개

아디다스는 JavaScript와 CSS를 사용하여 개발한 웹 페이지 프로젝트입니다. 이 프로젝트는 사용자가 헤더를 마우스로 가리킬 때 서브 메뉴를 표시하고, 페이지를 스크롤하면서 헤더의 스타일 및 로고 이미지를 변경하며, 서비스 섹션에서 애니메이션 효과를 제공합니다.

## 기능 소개

- **:bookmark: 반응형으로 제작 되었습니다.**: 
- **:art: 메인슬라이드**: 메인비주얼 영역 이미지가 슬라이드 됩니다.
- **:sparkles: json파일사용**: 제품의 정보가 화면에 표시되도록 설정 했습니다.

## 프로젝트 구조

프로젝트의 구조는 다음과 같습니다:

- `styles/`: CSS 파일들이 위치한 디렉토리
- `pages/`: 각 페이지 컴포넌트들이 위치한 디렉토리
- `component/`: 재사용 가능한 컴포넌트들이 위치한 디렉토리

## 컴포넌트 설명

### App 컴포넌트

App 컴포넌트는 웹 애플리케이션의 최상위 컴포넌트로, 라우팅과 페이지 구성을 담당합니다. React Router의 BrowserRouter를 사용하여 라우팅을 설정하고, `/` 경로로 접속할 경우 `<ProductAll/>` 컴포넌트를 렌더링하고, `/login` 경로로 접속할 경우 `<Login/>` 컴포넌트를 렌더링합니다.

### ProductAll 컴포넌트

ProductAll 컴포넌트는 모든 상품을 표시하는 역할을 합니다. useState를 사용하여 productList 상태를 관리하고, 상품 목록 데이터를 저장하며, useEffect를 사용하여 컴포넌트가 마운트될 때 한 번만 상품 목록을 불러옵니다. 받아온 상품 목록 데이터를 ProductCard 컴포넌트로 각 상품을 렌더링합니다.

### Login 컴포넌트

Login 컴포넌트는 로그인 화면을 표시합니다. 간단한 로그인 UI를 구성하고, 필요한 인증 기능을 구현할 수 있습니다.

## 프로젝트 실행 방법

1. 레포지토리를 클론합니다.
2. 프로젝트 폴더로 이동합니다.
3. `npm install` 명령어를 실행하여 필요한 패키지들을 설치합니다.
4. `npm start` 명령어를 실행하여 프로젝트를 실행합니다.

## 기여 방법

이 프로젝트에 기여하고 싶다면 다음과 같은 단계를 따라주세요:

1. 이 레포지토리를 포크합니다.
2. 새로운 기능이나 버그 수정을 위한 브랜치를 만듭니다: `git checkout -b feature/새로운기능` 또는 `git checkout -b bugfix/버그수정`
3. 수정사항을 커밋합니다: `git commit -m '새로운 기능 추가'` 또는 `git commit -m '버그 수정'`
4. 변경사항을 원본 레포지토리에 푸시합니다: `git push origin feature/새로운기능` 또는 `git push origin bugfix/버그수정`
5. Pull Request를 생성합니다.

## 데모

프로젝트를 더 자세히 살펴보려면 [여기](https://dlrud7113.github.io/adidas/)를 클릭하세요.
