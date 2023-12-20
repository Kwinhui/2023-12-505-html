# CSS Box 모델의 개념과 관련요소
1. CSS BOX 모델 : HTML의 요소는 박스 모양으로 구성되며 마진(Margin), 보더(Border), 패딩(Padding), 콘텐츠(Content)로 구분
2. CSS Padding, Borders, Margins Properties(속성)
- Padding : 콘텐츠(Content)와 보더(Border)와의 간격
- Border : 전체 요소의 테두리
- Margin : 보더(Border)로 부터 실제 콘텐츠(Content)가 표시될 수 있는 간격
3. CSS Outline : 요소를 두드러지게 보이게하는 선을 지정
- Outline의 종류 : dotted, dashed, solid, double, groove, ridge, inset, outset
- 색상의 지정도 가능
4. CSS Display
- block : 박스형태(div, h1 ~ h6, p, form, header, footer, section)
- inline : 한 라인에 보여 줄 수 있는 형태(Span, a, img)
- display : 화면에 콘텐츠가 표현되는 방식(none, block, inline, inline-bloc)
- visibility : 화면에 콘텐츠가 표현되는 방식(visible, hidden, collapse)

# CSS 아이콘과 링크
1. CSS Icons(아이콘) 
- Font awesome : script에 fontawsome JavaScript 불러온후 아이콘의 이름을 명시하여 적용
- Bootstrap : <head>안에 Bootstrap사이트 링크 삽입 후 아이콘의 이름을 명시하여 적용
- google : <head>안에 google의 아이콘 사이트링크 삽입 후 아이콘의 이름을 명시하여 적용
2. CSS Link(링크)
- default : 파란색과밑줄
- CSS로 스타일변경 가능

# CSS 리스트, 주석, 이미지 갤러리
1. Lists item Markers(표시자)
- 다양한 표시자의 예 : circle, square, upper-roman, lower-alpha, url로 직접 이미지 삽입 가능
2. CSS Commentes (주석) : 코드의 혼동 방지, 편리한 유지 보수, 실제 코드에 영향을 주지 않음
- CSS : //(한 줄), /* */(여러 줄)
- HTML : <!-- -->
- JavaScript : //(한 줄), /* */(여러 줄)
3. Image Gallery
- CSS로 이미지갤러리를 선언하면 각 이미지를 클릭했을 때 특정 이미지를 확대해서 나타나게 하는 것이 특징