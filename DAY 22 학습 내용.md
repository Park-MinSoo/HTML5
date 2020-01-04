# [ DAY 22 ]



## [ HTML에서의 공백과 개행 ]

```html
오늘은 화&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;요일입니다.
<!-- &nbsp;는 하나의 공백 처리를 나타낸다 -->
<h1>HTML에서의 공백과 &lt;개행&gt;</h1>
<!--&lt;는 less than 이라는 < 꺽쇄 가로 모양이다.-->
<!--&gt;는 greater than 이라는 > 꺽쇄 가로 모양이다.-->

<button>Submit</button>
<!-- form 태그안에서 쓰는 button은 submit 타입의 Input과 같다. -->
<!-- 이미지도 버튼으로 사용 할 수 있다. -->
```



## [ CSS ]

-  Cascading Style Sheets
  - 구조적으로 짜여진 문서(HTML,XML)에 Style(글자,여백,레이아웃)을 적용하기 위해 사용 하는 언어(Language)이다.
  - CSS 스타일시트는 HTML 문서의 요소에 적용되는 CSS 스타일 정의를 포함하며 CSS 스타일은 요소 표시 방법 및 페이지에서의 요소 위치를 지정한다.
  - W3C의 표준이며 HTML구조는 그대로 두고 CSS 파일만 변경해도 전혀 다른 웹사이트처럼 꾸밀 수 있다.



- CSS(Cascading Style Sheets) 사용한 웹 페이지 개발

  - 웹 표준에 기반한 웹 사이트를 개발할 수 있다. (페이지의 내용과 디자인을 분리)

  - 클라이언트 기기에 알맞는 반응형 웹 페이지를 개발 할 수 있다.

  - 이미지의 사용을 최소화시켜 가벼운 웹 페이지 개발을 가능하게 한다.

    

- CSS 의 작성 방법

  - 인라인 방법 - HTML 엘리먼트에 style 이라는 속성으로 정의하는 방법

    ```html
    <tag style="property: value">
    ```

    

  - 전역적 방법 - <style> 이라는 태그에 웹 페이지의 태그들에 대한 스타일을 정의하는 방법

    ```html
    <style type="text/css">
    selector {property: value;}
    </style>
    ```
    

  - 외부 파일 연결 방법 - 독립된 파일(확장자 .css)을 만들어서 HTML 문서에 연결하는 방법

    ```html
    <link rel="stylesheet" type="text/css" href="style.css" />
    ```



## [ 전역적인 스타일 설정 ]

- <head> 태그안에 <style> 태그를 사용한다.

- CSS 정의 방법

  - ```html
    CSS선택자 {
    	CSS속성명 : 속성값;
    	CSS속성명 : 속성값;
    	CSS속성명 : 속성값;
    	CSS속성명 : 속성값;
    }
    ```



## [ CSS 선택자 ]

- 전체 선택자

- 태그 선택자

- Class 선택자 

  -  여러클래스에 나누어 사용 할 수 있을때 사용

- Id 선택자 

  -  유니크한 경우에 사용

- 자식 선택자

- 자손 선택자

- 첫번째 동생 선택자

- 동생들 선택자

- 속성 선택자

  

- CSS를 다르게 적용하려는 태그(들) 또는 태그의 컨텐트에 정의하는 용도의 태그들

```html
<div> - 여러 태그들을 묶거나 또는 태그에 의하여 CSS 속성을 적용할 때 사용
      - 대표적인 블럭 스타일 태그(자동으로 줄을 바꾸는 것)
    
<span> - 컨텐트의 일부분에 대하여 CSS 속성을 적용할 때
       - 대표적인 인라인 스타일 태그(줄을 바꾸지 않는 것)
```









