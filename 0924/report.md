# CSS3 고급활용

## 배치 (Layout)
* display : block, inline, inline-block, none
* position : static(기본), relative(상대), absolute(절대), fixed(고정)
* float : 왼쪽/오른쪽 배치
* z-index : 요소의 쌓임 순서 제어
* visibility : 보이기/숨기기
* overflow : hidden, visible, scroll

## 리스트 꾸미기
*list-style-position : 마커 위치 (inside / outside)
*list-style-type : 마커 모양 (circle, square, decimal, roman, alpha 등)
*list-style-image : 사용자 지정 이미지 마커
*리스트를 이용해 메뉴바(nav) 만들 수 있음

## 표 꾸미기
*border : 표 테두리
*border-collapse : 중복된 테두리 합치기
*width, height : 셀 크기 제어
*padding, text-align : 셀 내부 여백과 정렬
*thead, tfoot, tbody 활용 → 배경색, 줄무늬(짝수 행), 마우스 hover 효과 적용 가능

## 폼 꾸미기
*input[type=text] 등으로 색상, 테두리, radius 지정
*:hover, :focus → 마우스 올림/포커스 효과 적용
*label, span을 이용해 폼 레이아웃 정리

## 동적 효과 (CSS3 고급 기능)
*애니메이션(animation) HTML 태그의 모양 변화를 시간단위로 설정, :@keyframes 로 시간에 따른 스타일 변화
*animation-name, animation-duration, animation-iteration-count 등 사용
*전환(transition) : HTML 태그에 적용된 css3 프로퍼티 값의 변하를 서서히 진해시켜 에니메이션 효과 생성
*변환(transform) : 회전(rotate), 기울임(skew), 이동(translate), 확대/축소(scale)
*마우스 hover, active 등과 조합해 다양한 효과 가능
