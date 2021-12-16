# HTML_Start
<h1>2021.12.15</h1>
<h2>html 태그 공부</h2>

<strong>1. html 강조하기(Tag)</strong>

'나는 html를 꼭 마스터 하겠다!' 라는 문장이 있습니다. 여기서 '꼭 마스터 하겠다!' 라는 부분을 중요 표시로 강조하고 싶을 때, 'strong'이라는 코드를 이용하여 표시하도록 하겠습니다!

ex) 나는 html를 <strong>꼭 마스터 하겠다!</strong>

여기서 'strong'은 <strong>시작태그</strong>라고 하며, '/strong'은 <strong>닫히는 태그</strong> 라고 한다.

<strong>2. 제목 처럼 쓰기(Tag)</strong>

'나의 목표' 라는 제목을 쓰고 싶다면 어떻게 해야 할까.

바로 'h1를 활용'하여 작성하면 된다. 

ex) <h1>나의 목표</h1>

여기서도 1번 항목처럼 동일하게 'h1'은 <strong>시작 태그</strong>가 되었고, '/h1'은 <strong>닫히는 태그</strong>가 되었다.

또한, 'h1'은 <strong>'head'</strong>의 약자로 자동적으로 줄바꿈이 된다.

<strong>3. 소제목 쓰기(Tag)</strong>

소 제목을 쓰고 싶다면 어떻게 해야 할까?

간단하다. 'h2'라고만 수정해주면 된다.

ex) <h2>소제목 받아라!</h2>


<h1>2021.12.16</h1>
<h2>html의 속성 공부</h2>

가끔, 우리는 홈페이지를 보면 어떠한 단어를 클릭할 때, 다른 웹사이트로 연결하는 것을 볼 수 있다. 이것을 html에서는 속성을 활용하여 연결할 수 있는데

예를 들어, 나의 블로그를 여기다가 올릴려고 한다. 

그때, 'a href'를 활용하여 올리면 되는데, 검색창에 나의 블로그 주소를 복사하여 붙여넣기 하면 된다.

즉, 'a href=https://blog.naver.com/codinghell17나의 블로그 /a'이렇게 표현해주면 된다. 한번 해보겠다.

ex) <a href=https://blog.naver.com/codinghell17>나의 블로그</a>
이렇게 쓰면 된다!

근데 누르면 보이는 것처럼 새로운 탭에서 열리지 않고, 그저 전에 있던 홈페이지에서 열리는데 만약에 새로운 홈페이지에서 열리게 하고 싶으면

'a href="https://blog.naver.com/codinghell17" target="_blank" 나의블로그/a'이런식으로 적어주면 된다.

ex) <a href="https://blog.naver.com/codinghell17" target="_black">나의 블로그</a>
이렇게 쓰면 된다! 

+ 확인해보니 안된다..똑같이 썼는데 왜 안되는지 모르겠다..쪽팔리니 넘어가자!

순서는 바꿔도 상관없다. 'a target="_blank" href=' 이런식으로 시작해도 된다.

마우스만 갖다놓았는데 아무것도 누르지 않고, 부가적인 설명을 붙이고 싶을 때는 

'a target="_blank" href"https://blog.naver.com/codinghell17" title="CodingHell17"나의 블로그/a' 이런식으로 적어주면 된다.

ex) <a target="_blank" href="https://blog.naver.com/codinghell17" title="CodingHEll17">나의 블로그</a>
이렇게 쓰면 된다!



