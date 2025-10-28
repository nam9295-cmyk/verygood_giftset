# VERY GOUT · B2B Giftset Landing

이 리포지토리는 바이어용 단일 랜딩 페이지입니다.  
`index.html`, `css/styles.css`, `images/` 폴더만으로 구성된 정적 페이지이며 GitHub Pages로 호스팅합니다.

## 수정 방법
- `index.html` 안의 `{{ ... }}` 부분을 실제 값으로 바꿉니다.
  - 패키지 한줄 타이틀
  - 브랜드 핵심 메시지
  - 박스 사이즈 (가로/세로/높이 cm)
  - MOQ (최소 주문 수량)
  - 리드타임 (며칠 전 주문 시 출고 가능)
  - 연락처(전화/카카오/이메일)

- `images/` 폴더 안에 실제 제품 사진을 넣고:
  - `main-set.jpg`
  - `detail-1.jpg`
  - `detail-2.jpg`
  - `detail-3.jpg`
  파일 이름을 맞추거나, `index.html` 안 `<img src="images/...">` 경로를 수정합니다.

## 배포 (GitHub Pages)
1. GitHub 리포지토리 Settings → Pages 이동
2. Source: `main` branch / root (`/`) 선택 후 저장
3. 표시되는 URL이 바이어용 링크입니다.
   예시: `https://사용자아이디.github.io/verygout-buyer-kit/`

그 URL을 그대로 바이어에게 전달하면 됩니다.
