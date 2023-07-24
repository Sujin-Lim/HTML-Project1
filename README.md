# HTML-Project1
HTML/CSS/JavaScript를 사용해 웹페이지 레이아웃 제작 

<br>

## 제작후기 - 개인

<b>✔헤더, 푸터, 옆 배너(홈,가장위로,가장아래로)</b>

![2](https://github.com/Sujin-Lim/HTML-Project1/assets/121391614/62b88e6e-b54c-4727-8a2e-caebac98d6b5)

-헤더: 다른 홈페이지에서 많이 봤던 세 줄 메뉴 표시(햄버거 메뉴)를 사용
세 줄은 선을 먼저 구현하고 transform 속성으로 45도로 돌리는 식으로 구현
아래 메뉴가 나타나는 것, 서치, 언어변경은 도현님이 구현

-푸터: 링크 버튼은 색깔이 바뀌는 부분을 숨겨두고 호버했을 때 나타내도록 함

-배너: 매우 간단했는데 위,아래로 가는 것은 자바스크립트 한 줄만 사용해 스크롤을 어디로 옮길지 좌표만 줌

매우 간단했는데 위,아래로 가는 것은 자바스크립트 한 줄만 사용해 스크롤을 어디로 옮길지 좌표만 줌

<br><br>

<b>✔공통부분연결</b>

수업시간에 배운 DOM이 다 불러와진 후에 불러오는 제이쿼리를 사용.
공통부분인 헤더,푸터,옆 배너를 따로 파일로 만든 후에 
불러오고자 하는 페이지에 div로 영역만 주면 되어서 매우 편했음.
<br><br>

<b>✔contact page-네이버 지도 api 활용</b>

![4](https://github.com/Sujin-Lim/HTML-Project1/assets/121391614/77412ac4-7856-4a5e-868a-39fcfe647ca3)

여러 api를 사용하면 더 쉽게 풍부한 내용을 화면에 넣을 수 있다. 
내가 맡은 페이지에 어울릴 지도api를 사용해보기로 했다.
script로 지도 api를 가져오고
지도에 나타낼 부분의 위도 경도만 넣으면 바로 화면에 구현이 되었다.
사용법이 너무 간단해서 다음번에는 더 많은 api를 사용해 보고 싶다는 생각이 들었다.
<br><br>

<b>✔contact page-별점</b>

![3](https://github.com/Sujin-Lim/HTML-Project1/assets/121391614/df338648-9e66-47aa-88c0-59d764136816)

기존에 만들어진 코드를 가져왔는데 최대한 코드를 이해하고자 노력했다.
svg tag=벡터 기반 그래픽을 xml 형식으로 정의하는 것. svg그래픽을 담기 위한 요소.
별 모양은 svg 태그 안에 g태그로 그룹으로 묶은 후 polygon 태그를 사용해 만들었다.
별 클릭했을 때 채워지는 것은 animation 효과로 구현했는데 
animation에 너무 많은 속성이 있어 내가 원하는 것을 만들고자 하면 많은 공부가 필요할 것 같다.
<br><br>
<b>✔inquiry</b>
![1](https://github.com/Sujin-Lim/HTML-Project1/assets/121391614/83a56eb7-34c9-4c82-a038-bb81542d9053)

다른 홈페이지에서 본 형식과 비슷하게 하려고 함.
입력하는 곳은 수업시간에 배운 table,input으로 구현
input 속성에 number나 email도 들어갈 수 있다는 것이 신기했다.
특히 input number를 하면 자동으로 유효성 검사가 되어 숫자만 들어갈 수 있던게 편함
다른 홈페이지에서 본 개인정보 수집하는 부분에서 전문보기부분 같은 팝업을 구현하고 싶었다.
팝업은 js로 함수를 사용했다.
클릭하면 보이고 닫기창을 하면 디스플레이 none으로 설정해 사라지는 것으로..
그럴싸해보일려고 파일 첨부하는 것도 하고 싶었다.
input type file로 하고 js 함수를 사용하는 것이었다. 
위에서 말한 input 타입에 여러 속성이 있어서 정말 편리하다고 생각했다.

<br><br>
<b>✔느낀점</b>

처음으로 하는 프로젝트여서 기존 홈페이지들 코드를 f12로 많이 살펴봤다.
코드를 보니 style을 주는 것은 다 외부 css파일을 만들어서 가져왔고,
모든 division과 태그들에 클래스명을 부여했더라.
나는 처음에 왜 저렇게 했지?라는 생각을 했고
우리 팀은 각자 페이지를 혼자 맡아서 나중에 디자인 통일성을 주기로 했는데 말도 안되는 일이었다.
다들 처음이라 자기 페이지만 생각해 클래스명을 부여하지 않고 스타일을 주다보니
합치게 되었을 때 코드가 꼬여버리고 제대로 적용되지 않았다.
이 부분 때문에 생각했던 것보다 시간이 조금 더 걸리게 됨.
역시 다들 하는것에는 이유가 있다고 느낌.
나는 html 기초만 배워서 제대로 만들어내지 못할 것 같아서
최대한 기존의 홈페이지에 있는 요소들을 구현하고자 노력했는데
기초를 기반으로 응용하다 보니 그럴싸하게 된 것 같아 뿌듯하다.
기초만으로 만들 수 있나?했는데 중요한 부분은 모두 책 안에 있었다.
특히 margin padding이 정말 중요하다고 느꼈다. 
물론 이미 만들어진 코드를 가져오기도 했는데 최대한 내용을 이해하고자 노력했다.
아쉬운 점은 position 부분이 이해가 어렵다. 
이번 프로젝트로 자신감이 붙어서
다음에 프론트엔드 프로젝트를 하게 된다면 더 빠르게 할 수 있을 것 같다

