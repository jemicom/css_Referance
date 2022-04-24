# 학습목표1

1. HTML vs CSS를 차이점을 구분하여 설명할 수 있다. ?
1. External , Internal , Inline CSS 를 지정할 수 있다.
1. CSS Ruleset을 지정할 수 있다.
1. Validating을 이용하여 Errors를 확인할 수 있다.

🔗[MDN:css referance](https://developer.mozilla.org/ko/docs/Web/CSS)

🔗[MDN:css referance](https://developer.mozilla.org/ko/docs/Learn/Getting_started_with_the_web/CSS_basics)

🔗[css 배우기](https://web.dev/learn/css/)

🔗[Validating](https://jigsaw.w3.org/css-validator/)

# 학습목표2

🔗[MDN:CSS_Selectors](https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Selectors)

🔗[MDN:CSS_Selectors](https://developer.mozilla.org/ko/docs/Learn/CSS/Building_blocks/Selectors)

1. 다양한 slectors(선택자)를 지정할 수 있다.
   Element, Class , ID , Group , Nested , Universal{\*} selector
   (09:04) The Cascade
1. 여러개 중 특별한 selector 디자인 : dev tools에서 취소선 확인
1. 상속(Inheritance)
   - 상속 되지 않은 요소
   - 선택자별 상속 html > body > \*
   - 속성을 이용한 상속 font:inherit;
   - 상속을 제외시킴
     p{ color:purple!important; } 클래스와 아이디, 태그를 모두 이기는 최강
     ! 는 가능한 사용하지 않는다.
1. 선택자 우선순위 계산기

   🔗[우선순위계산기](https://specificity.keegan.st/)

   🔗[우선순위계산기](https://polypane.app/css-specificity-calculator/#selector=)

   🔗[우선순위계산기](https://www.codecaptain.io/tools/css-specificity-calculator)

# 학습목표 3

🔗[MDN:color](https://developer.mozilla.org/en-US/docs/Web/CSS/color)

- CSS Colors 사용법에 대해 이해하고 사용할 수 있다.
- 고유색상명을 사용할 수 있다.
- rgb color 사용할 수 있다.
- Alpha channel - rgba 사용할 수 있다.
- hex color 사용할 수 있다.
- VS Code Color Picker 사용할 수 있다.
- hsl color 사용할 수 있다.
- VS Code Color Picker 를 사용할 수 있다.
- 다양한 color 파렛트

  🔗[칼라파렛트](https://coolors.co/contrast-checker/112a46-acc8e5)

  🔗[칼라레퍼런스](https://tutorial.techaltum.com/css-colors.html)

  🔗[mycolor.space/](https://mycolor.space/)

  🔗[ colourlovers ](https://www.colourlovers.com/)

  🔗[ 그라디언트 ](https://cssgradient.io/)

  🔗[ 그라디언트 ](http://ourownthing.co.uk/gradpad.html)

  🔗[칼라파렛트](https://htmlcolorcodes.com/)

# 학습목표 4

🔗[다양한 css 단위](https://developer.mozilla.org/ko/docs/Learn/CSS/Building_blocks/Values_and_units)

- 다양한 CSS 단위를 선택하여 사용할 수 있다.
- Many CSS units to choose from
- Absolute units - pixels
- Where NOT to use an absolute value
- Where you can use an absolute value
- Relative units - percent
- rem units
- rem vs em units
- When to use em units
- 기본 폰트 사이즈는 rem을 사용하고 그 내부에서 여백은 em을 사용
- ch units
- Default browser styles
- CSS Reset
- Viewport units - vw and vh
- When vw units can cause a problem
- A good use case for vh units

# 학습목표 5

🔗[The_box_model](https://developer.mozilla.org/ko/docs/Learn/CSS/Building_blocks/The_box_model)

CSS Box Model 을 이해하고 Default Style을 적용할 수 있다.
적용된 CSS Box Model을 inspacter을 이용하여 확인 하고 수정할 수 있다.

- Exploring the CSS Box Model
- Default Browser Styles
- CSS Reset

```
*{
    box-sizing:content-box; border-box;
    // inspacter : Computed 확인
}
```

- box-sizing
- Styling elements with the box model
- Margin properties and shorthand
- Padding properties and shorthand
- Border properties and shorthand
- Outline and outline-offset

```
.container{
    border:10px duble red;
    padding:1.5em;
    margin:1.5em;
    outline:5px solid purple;
    outline-offset:-10px;
}
```

Turn a box into a circle

# 학습목표 6

🔗[Styling_text](https://developer.mozilla.org/ko/docs/Learn/CSS/Styling_text/Fundamentals)

🔗[cssfontstack](https://www.cssfontstack.com/)

- font-size를 지정하고 사용할 수 있다.
- Typography 를 상속을 이용하여 지정 할 수 있다.
- text color를 수정 할 수 있다.
- Typography inheritance
- Changing text color
- Commenting out code in HTML and CSS
- text-decoration
- text-transform
- text-align
- text-indent
- Other text properties to style
- line-height
  줄 높이(en-US) 속성은 텍스트의 각 줄의 높이를 설정합니다. 대부분의 길이와 크기 단위가 필요할 수 있지만 단위 없는 값을 사용할 수도 있습니다. 이 값은 승수로 작용하며 일반적으로 최상의 옵션으로 간주됩니다. 글꼴 크기는 줄 높이를 얻기 위해 곱합니다. 본문 텍스트는 일반적으로 선이 떨어져 있을 때 더 보기 좋고 읽기 쉽습니다. 권장되는 선 높이는 약 1.5–2(이중 간격)입니다. 텍스트 줄을 글꼴 높이의 1.5배로 설정하려면 다음을 사용합니다.
- letter-spacing
- word-spacing
- font-weight
- font-style
- generic font families : serif | sans-serif|monospace|cursive|fantasy;
- font stacks and fallbacks : serif, sans-serif, monospace, cursive, fantasy ;
- Websafe fonts : link
- External fonts : 영문 Roboto , html에 link 또는 css에 @import

# 학습목표 7

-visited, hover, active, focus 유사 클래스를 사용하여 CSS에서 HTML 하이퍼텍스트 링크를 스타일링할 수 있다.

🔗[MDN:Styling_text](https://developer.mozilla.org/ko/docs/Learn/CSS/Styling_text/Fundamentals)

🔗[MDN:Styling_text](https://developer.mozilla.org/ko/docs/Learn/CSS/Styling_text/Fundamentals)

- Typography styles also apply to links
- Default link styles
- Removing the underline
- Cursor options
- Link color
- visited pseudo-class
- hover pseudo-class
- active pseudo-class
- pseudo-class specificity
- Cascade order for the pseudo-classes
- focus pseudo-class
- A different link style approach
- Using hsl for a complimentary hover color
- Using transparency for hover
- Pseudo-classes can change other properties, too

# 학습목표 8

1. 목록 스타일 유형 및 기타 유용한 속성을 사용하여 목록을 스타일링할 수 있다.
1. CSS를 사용하여 HTML 목록을 스타일링하여 HTML 컨텐츠의 변화를 확인 할 수 있다.

🔗[MDN:Styling_lists](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_lists)

- list-style-type
- Useful HTML attributes
- Removing list item styles
- The unordered list
- list-style-position
- List items inherit typography
- list-style-image
- list-style shorthand
- List item styles
- nth-child pseudo-class
- ::marker pseudo-element
- One more helpful HTML attribute

# 학습목표 9

1. block | inline | inline-block 디스플레이 유형의 차이점을 확인하고 설명할 수 있다.
1. block | inline | inline-block 디스플레이 유형을 사용하여 간단한 네비게이션 바를 구축할 수 있다.

- CSS Display Property
- display: block | inline | inline-block
- When is inline-block useful?
- Styling a simple nav menu
- Display types flex and grid
- Display type none

# 학습목표 10

CSS 플로팅과 클리어에 대해 설명할 수 있다.
플로트 및 클리어를 이용하여 기본 페이지 레이아웃을 스타일링할 수 있다.

- Create starting elements
- Styling the block class
- Normal page flow
- Floating the div
- Creating separation between float and text
- Adding a 2nd float element
- Clearing floats
- Floats inside container elements
- Float columns in legacy code

# 학습목표 11

선택기 및 색상별 기존 레슨에서 배운 모든 것을 링크와 리스트 스타일이 적용된 박스 모델에 적용해 미니프로젝트를 구축할 수 있다.

- Start with a CSS Reset
- body element styles
- nav element styles
- heading styles
- list styles
- hypertext link styles
- display: block vs inline
- last-child pseudo-class
