# 이미지 슬라이드(좌우)
1. CSS로 구현하기
- @keyframes 를 이용함
- margin-left 로 좌측 좌표를 선언하여 좌우 슬라이드를 구현할 수 있음
2. JavaScript로 구현하기
- 지정 시간마다 반복되는 setInterval() 함수를 활용함
- animate 메소드를 통해 지정 시간 마다 요소의 left 속성을 할당하여 구현할 수 있음

# 이미지 슬라이드(상하)
1. CSS 로 구현하기
- @keyframes 를 이용함
- margin-top 으로 상단 좌표를 선언하여 상하 슬라이드를 구현할 수 있음
2. JavaScript로 구현하기
- 지정 시간마다 반복되는 setInterval()함수를 활용함
- animate 메소드를 통해 지정 시간 마다 요소의 top 속성을 할당하여 구현할 수 있음

# 페이드인-아웃 구현하기
1. CSS로 구현하기
- @keyframes 를 이용함
- opacity 로 투명도를 선언하여 페이드인-아웃을 구현할 수 있음
2. JavaScript로 구현하기
- 지정 시간마다 호출하는 setTimeout()함수를 활용함
- style.display 속성을 'none', 'block' 으로 할당하여 페이드인-아웃을 구현할 수 있음