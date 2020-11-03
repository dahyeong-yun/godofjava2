## 계산의 과정
- 컴퓨터는 기본적으로 계산기다.
- 컴퓨터 대신 우리가 계산을 할 때를 생각해보자.
  - 초등학교 1학년 수학 시험지에 `1+1 = [ ]`와 같은 문제가 나왔다면 우리는 2라는 답을 적을 것이고 이것을 정답이라고 한다.
    - 사실 2가 정답이 되려면 몇가지 전제가 필요하다.
      - 1이 의미하는 것이 아라비아 숫자 1로 십진법의 숫자임이 합의 되어야 하고,
      - `+`와 `=`이 의미하는 것이 각각 더하기와 등호 표시어야 한다.
    - 이러한 약속들을 통해서 우리는 수식을 계산할 수 있다.
      - 이때 `1`과 `2`는 상수라고 하고 `+`와 `=`는 연산자라고 부른다.
  - 여기서 초등학교 고학년으로 살짝 넘어가 보자. `1 +  [ ] = 2`라는 식이 참이 되는 자연수만 쓰라고 한다면 우리는 `1`을 적을 것이다.
    - 만약 실수 범위까지 늘려준다면 `-(-1)`도 있고, 복소수까지라면 `i`의 제곱이라고도 할 수 있다.
    - 이렇게 정해지지 않은 `[ ]`를 지칭하기를 변수라고 한다.
    - 중학교쯤 가면 우리는 보통 `x`, `y`로 변수를 표현한다.  
   
- 자바에게 계산을 시키는 것은 이러한 덧셈 방식과 매우 흡사하다.

## 자바의 변수와 연산자
### variable(변수)
- 변수의 구분 : 변수가 어떻게 구분되느냐에 따라 조작 방법이 달라진다. 따라서 구분법을 익히고 나서 사용법을 보는 것이 바람직 하다.
- type(타입)의 구분 : primitive(원시 타입) vs reference(참조 타입)
  - 원시타입은 정해져 있다.
  - 참조타입은 기본적으로 생성되있는 것이 있고, 사용자 정의의 가능성은 무궁무진 하다.
  - **[생각해보기]** __왜 `int`가 있고 `Integer`가 있는가?__
- Scope(영역)의 구분 : 변수가 영향을 미치는 영역으로 구분할 수도 있다.
  - 멤버 변수
  - static 변수
### operator(연산자)
- 자바 뿐만 아니고 다수의 프로그래밍 언어에서 사용하는 연산자는 흔히 볼 수 있는 가감승제의 방식과 약간 다르다. 어차피 기호일 뿐이니 익숙해 지면 된다.
- `+`, `-`는 같다.
- `=`는 등호지만 프로그래밍에서는 대입 연산자로 쓴다. 왼쪽에 있는 변수가 오른쪽에 있는 값으로 대입된다.
- `==`가 등호 역할을 한다. `!=`는 같지 않음을 의미한다. 이들의 결과는 불대수(쉽게 말해 `true`, `false`)로 표현된다.