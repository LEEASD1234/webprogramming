## 계산 및 결과 출력:
* onclick 이벤트, eval() 함수 : HTML <span class="answer-button"> 태그에 onclick 이벤트를 설정. 클릭 시 JavaScript의 위험할 수 있지만 간단한 수식 계산에 사용되는 eval('수식') 함수를 호출.

##겹침 순서 제어	
* z-index 스타일 속성	 : position: absolute로 겹쳐 배치된 여러 개의 카드(<img>) 중, 클릭된 카드를 가장 위로 올리는 기능을 구현.

## 동적 스타일 변경	
*  element.style.zIndex : 모든 카드 요소에 onclick 리스너를 설정하고, 클릭 시 해당 카드의 style.zIndex 값을 현재 페이지에서 가장 높은 값으로 동적으로 설정하여 맨 앞으로 가져옴.

## 요소 내용 변경	
* this.innerHTML : eval()로 얻은 계산 결과를 클릭된 요소(this)의 innerHTML 속성에 할당하여 버튼 텍스트를 결과 값으로 즉시 변경.

## 사용자 입력	
* prompt() 함수 : 특정 요소 클릭 시(또는 최종적으로는 페이지 로드 시) prompt() 함수를 실행하여 사용자로부터 텍스트(여행지)를 입력받음.
* HTML 삽입 및 스타일 적용 (심화)	: innerHTML, <span> 태그	입력받은 텍스트를 <p> 태그에 출력할 때, 텍스트 자체를 <span style="background-color:skyblue">...</span> 태그로 감싸서 **innerHTML**에 삽입했습니다. 이로써 단순 텍스트뿐 아니라 HTML 구조와 CSS 스타일까지 동적으로 적용했습니다.
* 즉시 실행	: <script> 태그의 위치	마지막 요청에 따라, changeContentOnLoad() 함수를 정의 후 <script> 블록 내에서 바로 호출하여 웹 페이지 로드와 동시에 prompt() 창이 뜨도록 구현했습니다.