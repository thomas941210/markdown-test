<!-- README를 대문자로 입력하는 이유?
  git에서 README라는 대문자를 읽어오기 때문에 -->

  # 제목 (Header)
  
  <!-- #갯수에 따라 h1 ~ h6태그 처럼 제목에 사용 -->

  # 제목 1
  ## 제목 2
  ### 제목 3
  #### 제목 4
  ##### 제목 5
  ###### 제목 6

  # 문장 (Paragraph)

  동해물과 백두산이 마르고 닳도록
  하느님이 보우하사 우리나라 만세



  # 줄바꿈 (line Breaks)
  
  <!-- 줄바꿈 할 곳에서 띄어쓰기 두번 or <br/> 사용 -->

  동해물과 백두산이 마르고 닳도록  
  하느님이 보우하사 우리나라 만세  
  무궁화 삼천리 화려강사 <br/>
  대한 사람 대한으로 길이 보전하세



  # 강조(Emphasis)

  <!--  이텔릭체 원하는 문장 앞,뒤에 (underbar) _ 넣기 -->
  _이텔릭_

  <!-- 두꺼운 글씨체 사용시 문장 앞,뒤에 (**) 두개씩으로 묶어주기 -->
  **두껍게**

  <!-- 이텔릭과 두껍게를 동시에 사용시 문장 앞,뒤에 **_ 문장 _**으로 묶어주기 -->
  **_이텔릭 + 두껍게_**

  <!-- 취소선 사용시 문장 앞뒤에 (~~) 두개씩으로 묶어주기 -->
  ~~취소선~~

  <!-- 밑줄 사용시 문장사용시 <u></u>태그로 묶어주기  **하지만 그다지 권장하진 않음 -->
  <u>밑줄</u>


  # 목록(list)
  
  <!-- 순서가 필요한 목록 사용시 ul li처럼 앞에 1.사용 후 한 칸 띄워서 사요하면 li처럼 숫자가 증가하면서 사용되어짐 -->
  <!-- 순서가 필요한 목록에서 서브 리스트 생성시 필요한곳에서 들여쓰기(tab키) 2번 사용하고 작성해야함 -->
  1. 순서가 필요한 목록
  1. 순서가 필요한 목록
  1. 순서가 필요한 목록
      1. 순서가 필요한 목록
      1. 순서가 필요한 목록
  2. 순서가 필요한 목록

  <!-- 순서가 필요하지 않은 목록에서는 -(dash) 사용후 한칸 띄워서 글자 작성, sub 목록에서는 들여쓰기(tab키) 두번 사용하고 작성 -->

  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
      - 순서가 필요하지 않은 목록
      - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록


  # 링크(Links)
  <!-- a태그로 사용 or [글자](주소) -->
  <a href="https://google.com">GOOGLE</a>
  
  [GOOGLE](https://google.com)

  <!-- [글자](주소 "title 넣기") -->
  <a href="https://naver.com" title="NAVER로 이동!">NAVER<a>

  [NAVER](https://naver.com "NAVER로 이동!")

  <a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER<a>

  
  # 이미지(Images)
  <!-- 이미지 생성시 [대체텍스트](이미지 주소) 이러면 이미지 대체텍스트만 나옴 -->
  [HEROPY](https://heropy.blog/css/images/logo.png)
  <!-- 이미지 생성시 ![대체텍스트](이미지 주소) !를 붙히면 이미지가 나옴 -->
  ![HEROPY](https://heropy.blog/css/images/logo.png)

  <!-- 만약 이미지에 링를 넣고싶다면? -->
  [![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)


  # 인용문(BlockQuote)
  <!-- 인용문 사용시 >(꺽쇠를 사용) -->
  > 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
  > (네이버 국어 사전)

  <!-- 중첩된 인용문 사용시 꺽쇠를 1개 2개 3개 증가하면서 사용 -->
  > 인용문을 작성하세요!
  >> 중첩된 인용문
  >>> 중중첩된 인용문 1  
  >>> 중중첩된 인용문 2  
  >>> 중중첩된 인용문 3



  # 인라인(inline) 코드 강조

  <!-- 사용하고자 하는 문장 앞뒤에 `` backtick으로 묶어주기 -->
  CSS에서 `background` 혹은
  `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.



  # 블록(block) 코드 강조

  <!-- 코드 개념으로 사용하고자 하는 경우 ```backtick 기호 3개 입력하고자 하는 속성 작성 후 ```backtick으로 묶어주기 -->
  ```html
  <a href="https://www.google.co.kr" target="_blank">GOOGLE</a>
  ```

  <!-- css 입력속성 -->
  ```CSS
  .list > li {
    position: absolute;
    top: 40px;
  }
  ```

  <!-- 자바스크립트 입력속성 -->
  ```javascript
  function func() {
    var a = 'AAA';
    return a;
  }
  ```

  <!-- 터미널 입력속성 -->
  ```bash
  $ git commit -m 'Study Markdown' 
  ```

  ```plaintext
  동해물과 백두산이 마르고 닳도록
  하느님이 보우하사 우리나라 만세
  ```


  # 표(Table)
  <!-- 아래 해당방식으로 사용 -->
  position 속성
  <!-- 의미 부분은 가운데 정렬 --두개 있는곳에 앞,뒤로 ::묶어주기 -->
  <!-- 기본값 부분은 오른쪽 정렬 -- 두개 있은곳 뒤에 :작성 -->
  값 | 의미 | 기본값
  -- | :--: | --:
  static | 기준 없음 | O(알파벳)
  relative | 요소자신 | X
  absolute | 위치 상 부모 요소 | X
  fixed | 뷰포트 | X



  # 원시 HTML(Raw HTML)
  <!-- u태그는 underline or span에 style 주기 -->
  동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
  하느님이 보우하사 우리나라 만세

  <a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER<a>

  ___

  <img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />

  
  # 수평선(Horizontal Rule)
  <!-- 수평선은 ---,***,___세번 작성 -->
  ---

  ***

  ___
