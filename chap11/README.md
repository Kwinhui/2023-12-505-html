# CSS, W3.CSS 를 활용한 탭 메뉴
1. CSS를 활용한 탭 메뉴(tab menu)
- HTML 작성하기 : stylesheey 필요
- CSS 작성하기 : 스타일과 animation 효과로 탭 작동 구현하기
2. W3.CSS를 활용한 탭 메뉴(tab menu)
- HTML 작성하기 : CDN방식으로 W3.CSS 불러오기
- JavaScript 작성하기 : 각 탭을 클릭하면 선택된 컨테이너의 콘텐츠가 보이도록 구현

## JavaScript를 활용한 탭 메뉴
1. HTML 작성하기 : head에 stylesheey와 JavaScript 호출
2. CSS 작성하기 : maring : 0; 으로 reset하기
3. JavaScript 작성하기 : 함수를 사용해서 작동 구현
- document.getElementsBy를 사용해서 탭이 많아도 자동으로 JavaScript가 개수를 파악하고 구현

## jQuery를 활용한 탭 메뉴
1. HTML 작성하기 : head에 stylesheet, 사용자 작성 JavaScript
2. CSS 작성하기 : 최초 실행시 나타나는 탭을 제외하고 모두 나타나지 않게 display:none 으로 설정
3. jQuery 작성하기 : 선택된 탭이 click 을 통해 하나씩 표현 될 수 있도록 함수 작성

## BootStrap 을 활용한 탭 메뉴
1. Bootstrap : 반응형 웹의 모바일 우선 프론트 엔드 웹 개발을 위한 무료 오픈 소스 CSS 프레임 워크
2. HTML 작성하기 : head에 bootstrap에서 CSS, jQuery 에서 JavaScript, bootstrap 에서 JavaScript 호출