﻿# SliderEffect
<img src="https://github.com/Fitalux/SliderEffect/blob/main/img/display.png" />

# VIEW SITE
https://fitalux.github.io/web2023/javascript/slider/sliderEffect01.html

# DESC
jquery, GSAP Library, JAVASCRIP를 사용하여 세 가지 방법으로 구현한 Slider Effect 웹 페이지입니다.
슬라이드가 활성화 되면 이전 이미지는 페이드 아웃 되어 서서히 사라지고 다음 이미지는 페이즈 인 되어 서서히 나타납니다.
위에서 아래로 슬라이드 되거나, 왼쪽에서 오른쪽으로 슬라이드 되거나, 연속적으로 슬라이드 되거나, 섬네일 클릭 시 해당 이미지로 이동하거나, dot 메뉴 클릭 시 해당 이미지로 이동하는 등의 기능을 구현하였습니다.


# SCRIPT METHOD

setInterval<br>
: JAVASCRIPT의 타이머 함수 중 하나로, 일정한 간격으로 함수를 반복적으로 실행하는 역할을 합니다.<br>
지정된 시간 간격(ms, 밀리초) 마다 함수를 호출하여 반복적으로 작업을 수행합니다.<br><br>

firstElementChild<br>
: JAVASCRIPT DOM 요소 프로퍼티로, 해당 요소의 첫 번째 자식 요소를 가져옵니다.<br><br>

cloneNode(true)<br>
: DOM 요소를 복사하여 복제하는 메서드입니다.<br><br>

=> firstElementChild와 cloneNode를 함께 사용하면 해당 요소의 첫번째 자식 요소를 복사하여 복제할 수 있습니다.<br><br>

offsetWidth<br>
: JAVASCRIPT DOM 요소의 프로퍼티로 해당 요소의 너비를 픽셀 단위로 반환합니다.<br>
요소의 너비에는 boder, padding, 스크롤바 등을 포함한 전체 너비가 포함되어 반환됩니다.<br><br>

 classList<br>
 : JAVSCRIPT DOM 요소의 프로퍼티로 해당 요소의 클래스 이름들을 조작하는데 사용됩니다.<br><br>

 contains<br>
 : class에 특정 class가 존재하는지에 대한 여부를 확인하는 메서드입니다.<br><br>

 join<br>
 : JAVASCRIPT의 배열 메서드로, 배열의 모든 요소를 하나의 문자열로 결합하는 역할을 합니다.<br>
 인자로 전달된 문자열을 배열의 요소들 사이에 삽입하여 문자열로 반환합니다.<br><br>
