# 학습목표 1

1. 개발 환경을 설정 할 수 있다.
1. HTML 언어에 대해 설명 할 수 있다.
1. HTML 기본 구조에 대해 설명할 수 있다.
1. HTML 언어를 이용하여 간단한 웹페이지를 제작할 수 있다.

# 학습내용

1. Visual Studio Code , Optional VS Code Extensions
1. What is HTML?
1. Google Chrome Browser
1. html 기본 구조
   body, head , meta, title, h1
1. Adding a heading and a paragraph
1. Line breaks <br />

📚 참고사이트

🔗[MDN:HTML](https://developer.mozilla.org/ko/docs/Web/HTML)

🔗[MDN:HTML Element](https://developer.mozilla.org/ko/docs/Web/HTML/Element)

```
<meta name="title" content="내일이 더욱 기대되는 기업 KT&G" />
<meta name="keywords" content="" />
<meta name="description" content="" />
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=Edge">
<meta name="viewport" id="viewport" content="width=device-width,initial-scale=1.0,maximum-scale=1.0, minimum-scale=1.0,user-scalable=no" />
<meta name="format-detection" content="telephone=no">
<meta name="google-site-verification" content="KL-BV9BPtAF01iPyQRFbB3eidwWucIaab6Sa-DxG84Q" />
<meta name="facebook-domain-verification" content="rwcimn8pgv39gch30ou5jraomtln0j" /> <!-- 2020-07-15 facebook -->
```

# 학습목표 2

1. vscode 의 option 설정과 extention을 설치할 수 있다.
1. Validation을 이용하여 HTML 언어의 에러를 확인할 수 있다.
1. display 속성중 block형 속성과 inline형 속성에 대해 설명할 수 있다.
1. html 언어의 주석을 처리할 수 있다.
1. display 속성을 이용한 간단한 웹페이지를 제작할 수 있다.

# 학습내용

📚 참고사이트

🔗[VSColde Extention :vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)

🔗[MDN: HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

🔗[MDN: HTML Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

🔗[Markup Validation Service ](https://validator.w3.org/)

1. 자동 저장, 단축키 설정
1. Validating : lang, doctype 추가
1. Block elements vs Inline elements
1. Abbreviation element <abbr>
1. hr, sub, sup, ruby, rt, abbr, i, b, strong, em, ins, del, mark, code
1. HTML Comments 주석처리
1. Live Server Extension

# 학습목표 3

1. 페이지를 이동하는 link를 사용할 수 있다.
1. img 를 이용한 페이지를 제작할 수 있다.
1. HTML의 HT에 대해 설명할 수 있다.
1. HTML Entities

### 학습내용 : link

1. 머리글은 텍스트 내용을 구성하고 의미를 제공합니다.
1. Whitespace Collapsing, Line breaks
1. 다른 페이지로 이동하는 링크
1. 상대주소와 절대주소(Absolute vs Relative references)
1. 한페이지 내에서 다른 위치로 이동하는 북마크
   <a href="#">Back to Top</a> 기본페이지 맨위로 가기
   <a href="#html">Learning HTML</a>

1. 링크 용도별 link colors 바꾸기
   :hover, :active, :link , :visited
1. Download links
   <a href="html5.png">download img</a>
1. Opening a link in a new tab
   <a href="https://www.google.com" target="_black">Google</a>
1. link text 규칙

   - 페이지에 전체 웹 주소를 나타내지 않도록 합니다.
   - 링크 대상 구문은 사용하지 마십시오.
   - 우리 모두는 그것이 link 라는 것임을 알고 있으므로 ( 손가락 표시가 나오거나 밑줄이 있다면)
   - 링크 텍스트를 짧게 유지합니다.바로 그거다. 문장이 아니라.
   - "여기 클릭"이라고 표시된 링크가 없습니다.아무 의미도 없어요.

전화<a href="tel:010-1234-5678">전화</a>

외국의 경우 <a href="tel:+국가번호 10-1234-5678">+82 010-1234-5678</a>

아이폰에서는 전화번호형식 010-1234-5678과 같은 형식이면 자동링크라 걸린다.

이를 막기위한 메타테그는 <meta name="format-detection" content="telephone=no">

문자 <a href="sms:010-1234-5678">문자</a>

메일 <a href="mailto:a@a.com">메일</a>

### 학습내용 : img

1. 무료 이미지 download
1. img element
1. width and height attributes
1. alt, title attributes
1. Loading attribute
1. figure and figcaption elements

# Loading attribute and "below the fold"

```
<img src="path" loading="eager">
abbreviation(브리비에이션)
https://web.dev/i18n/ko/browser-level-image-lazy-loading/

다음은 loading 속성에 대해 지원되는 값입니다.
auto: 속성을 포함하지 않는 것과 동일한 브라우저의 기본 지연 로딩 동작입니다.
lazy: 뷰포트로부터 계산된 거리에 도달할 때까지 리소스 로딩을 지연시킵니다.
eager: 페이지에서의 위치에 관계없이 리소스를 즉시 로드합니다.
```

📚 참고사이트

🔗[MDN:lazy](https://developer.mozilla.org/en-US/docs/Web/Performance/Lazy_loading)

🔗[extention : HTML5 Outliner](https://chrome.google.com/webstore/detail/html5-outliner/afoibpobokebhgfnknfndkgemglggomo)

🔗[MDN : Sementic HTML5 Viewer](https://chrome.google.com/webstore/detail/semantic-html-viewer/glapikbnefnagjolgppjefchjkjffhog?hl=ko)

🔗[Named character references](https://www.w3schools.com/charsets/ref_html_ansi.asp)

# 학습목표 4

- 3 가지 타입의 목록을 지정할 수 있다.
- 3 가지 타입의 목록의 차이점을 구분할 수 있고 구분하여 사용할 수 있다.

📚 참고사이트

🔗[MDN : references](https://developer.mozilla.org/en-US/docs/Web/HTML)

🔗[MDN : references](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

# 학습내용

- Ordered Lists
- Unordered Lists
- Description Lists

# 학습 목표 5

1. 테이블을 사용할 수 있는 곳을 확인 할 수 있다.
1. 기본 테이블을 삽입하여 디자인 할 수 있다.
1. 시멘틱 테이블을 제작 할 수 있다.

# 학습 내용

1. 기본 table
1. Adding table headings
1. colspan attribute & rowspan attribute
1. Table semantics
1. Caption element
1. thead, tbody, and tfoot elements
1. Adding row headings
1. scope attribute

📚 참고사이트

🔗[ MDN: Table Basics] (https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

🔗[ MDN: Advanced Tables 과 활용](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)

# 학습 목표 6

박스 모델링

# 학습 목표 7

1. 시멘틱 태그를 이용한 콘텐츠 위주의 페이지를 제작할 수 있다.

📚 참고사이트

🔗[MDN:semantic](https://www.w3schools.com/html/html5_semantic_elements.asp)

🔗[MDN:Glossary/Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

🔗[MDN:Semantics](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

<article> tag는 문서 혹은 요소가 독립적으로 존재할 수 있을 때 사용한다.

<section> tag는 논리적으로 관계 있는 문서 혹은 요소를 분리할 때 사용한다.

<div> 요소간 논리적 관계와는 상관없이 요소를 나눠야 할 필요가 있을 경우 사용한다.

# 학습 내용

1. Heading Hierarchy
1. nav and hr tags
1. The word: "semantic"
1. header , main, footer, Labeling multiple nav elements
1. article vs section elements
1. aside, details, and summary elements
1. time elements

## 웹스토어 시멘틱 툴

📚 참고사이트

🔗[Semantic HTML Viewer(]https://developer.mozilla.org/ko/docs/Web/HTML/Element/details)

<summary> 태그는 <details> 요소에 대한 가시적인 제목을 정의합니다. 제목을 클릭하면 세부 정보를 보거나 숨길 수 있습니다.

참고: <summary> 요소는 <details> 요소의 첫 번째 하위 요소가 되어야 합니다.

📚 밴치마킹 참고사이트

🔗[일본 웹사이트 모음]http://bm.straightline.jp/

# 학습목표

데이터 입력을 받을 수 있는 폼을 제작할 수 있다.

# 학습 내용

1. Forms make your pages interactive
1. Adding a new anchor link
1. Adding a new article element
1. Form element
1. Text input
1. Adding a 2nd text input
1. Wrapping inputs in block elements
1. Password input
1. tel input
1. Number input
1. Select, option and optgroup elements
1. Datalist
1. Adding semantics with fieldset and legend
1. Radio buttons
1. Checkboxes
1. Textarea
1. Email and other inputs
1. Button elements
1. Submitting the form
1. Last button, Post vs Get Requests

📚 참고사이트

🔗[MDN:Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

🔗[MDN:Forms](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)

🔗[개인용:input-pattern](http://www.tcpschool.com/html-tag-attrs/input-pattern)

<!--
아주 예전에는 입력 값의 유효성 검사를 하려면 자바스크립트를 사용하거나 서버 사이드 스크립트를 사용해 처리해야만 했다.

하지만 html5 이후 input 태그의 pattern 속성에 정규표현식을 넣으면서 유효성 검사를 위한 입력 값 제한을 비교적 간단하게 구현할 수 있다.

물론 이중, 삼중의 보안과 완전한 입력 값 컨트롤을 요한다면 서버 사이드 스크립트에서 처리하는 것과 병행해서 사용하는 것이 좋다고 생각한다. -->

input pattern 정규표현식 모음

1. 숫자만

<input type="text" name="patternValue" pattern="\d*">
<input type="text" name="patternValue" pattern="^[0-9]+$">

2. 영문 대소문자만

<input type="text" name="patternValue" pattern="^[a-zA-Z]+$">

3. 영문 대소문자만 (띄어쓰기 및 공백 가능)

<input type="text" name="patternValue" pattern="^[a-zA-Z\s]+$">

4. 숫자, 영문 대소문자만

<input type="text" name="patternValue" pattern="^[a-zA-Z0-9]+$">

5. 최소 8자리에서 최대 16자리까지 숫자, 영문, 특수문자 각 1개 이상 포함 (암호 유효성 검사에 유용)

<input type="text" name="patternValue" pattern="^(?=.*[A-Za-z])(?=.*\d)(?=.*[$@$!%*#?&])[A-Za-z\d$@$!%*#?&]{8,16}$">

pattern=”[a-zA-Z]{no}”: no개 만큼의 영문자를 입력
pattern=”[0-9]{no}”: no개 만큼의 숫자를 입력
pattern=”[A-Za-z0-9]{min, max}: 영문자와 숫자를 min ~ max 만큼의 글자 수 입력
pattern=”[0-9]+”: 숫자를 1개 이상 입력

이름
[a-zA-z]{4,10}
전화번호
0\d{1,2}\-\d{3,4}\-\d{4}
주민등록번호
\d{6}\-[1-4]\d{6}
이메일
^[a-zA-Z0-9]+@[a-zA-Z0-9]+$

 <!-- 
     https://httpbin.org/
     form 데이터를 확인할 수 있는 사이트 
     https://httpbin.org/get
  -->

  <!-- 
      http://uxuiz.cafe24.com/wp/
      자바스크립트 플러그인
   -->

https://developer.mozilla.org/ko/docs/Web/CSS

# project

html 구조만을 사용한 간단한 프로젝트
Nav menu : 현재 페이지에서 이동, 다른 사이트로 이동하는 메뉴를 배치
img : 파비콘과 각 페이지마다 필요한 이미지를 배치한다.
Completing the page structure
