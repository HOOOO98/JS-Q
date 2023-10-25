# 💁‍♂️자바스크립트 100문 100답
자바스크립트를 공부하면서 생기는 궁금증과 난해한 개념을 질문하고<br>
이를 해결함으로써 온전한 개념을 습득하는 것이 이 페이지의 목표입니다.

- 두괄식으로 답변하기
- 질문의 의도를 파악하고 답변과 연관된 주제 서사적으로 풀어내기
- 정의+문제점+해결책
- 정의+연관된주제

# 목차
| 번호 | 질문 |
| --- |---|
|  1  | [호이스팅에 대해서 설명해주세요.](#호이스팅에-대해서-설명해주세요) |
|  2  | [프로토타입 체인에 대해서 설명해주세요.](#프로토타입-체인에-대해서-설명해주세요) |
|  4  | [순수 함수에 대해 설명해주세요.]() |
|  5  | [클로저에 대해서 설명해주세요.]() |
|  6  | [this와 그 우선순위에 대해서 설명해주세요.]() |
|  7  | [스코프의 개념에 대해서 설명해주세요.]() |
|  8  | [주소창에서 url을 입력하는 순간부터 화면에 렌더링 되는 순간까지의 과정을 설명해주세요.]() |
|  9  | [웹 저장소에 대해서 설명해주세요.]() |
|  10  | [콜백함수에 대해서 설명해주세요.]() |
|  11  | [프로미스에 대해서 설명해주세요.]() |
|  12  | [스트릭트 모드가 뭔지 설명해주세요.]() |
|  13  | [eval에 대해서 설명해주세요.]() |
|  14  | [window와 document의 차이점에 대해 설명해주세요.]() |
|  15  | [DOM과 BOM에 대해서 설명해주세요.]() |
|  16  | [events에 대해서 설명해주세요.]() |
|  17  | []() |
|  18  | []() |
|  19  | []() |
|  20  | []() |
|  21  | []() |
|  22  | []() |
|  23  | []() |
|  24  | []() |
|  25  | []() |
|  26  | []() |
|  27  | []() |
|  28  | []() |
|  29  | []() |
|  30  | []() |
|  31  | []() |
|  32  | []() |
|  33  | []() |
|  34  | []() |
|  35  | []() |
|  36  | []() |
|  37  | []() |
|  38  | []() |
|  39  | []() |
|  40  | []() |
|  41  | []() |
|  42  | []() |
|  43  | []() |
|  44  | []() |
|  45  | []() |
|  46  | []() |
|  47  | []() |
|  48  | []() |
|  49  | []() |
|  50  | []() |
|  51  | []() |
|  52  | []() |
|  53  | []() |
|  54  | []() |
|  55  | []() |
|  56  | []() |
|  57  | []() |
|  58  | []() |
|  59  | []() |
|  60  | []() |
|  61  | []() |
|  62  | []() |
|  63  | []() |
|  64  | []() |
|  65  | []() |
|  66  | []() |
|  67  | []() |
|  68  | []() |
|  69  | []() |
|  70  | []() |
|  71  | []() |
|  72  | []() |
|  73  | []() |
|  74  | []() |
|  75  | []() |
|  76  | []() |
|  77  | []() |
|  78  | []() |
|  79  | []() |
|  80  | []() |
|  81  | []() |
|  82  | []() |
|  83  | []() |
|  84  | []() |
|  85  | []() |
|  86  | []() |
|  87  | []() |
|  88  | []() |
|  89  | []() |
|  90  | []() |
|  91  | []() |
|  92  | []() |
|  93  | []() |
|  94  | []() |
|  95  | []() |
|  96  | []() |
|  97  | []() |
|  98  | []() |
|  99  | []() |
|  100  | []() |


### 호이스팅에 대해서 설명해주세요
호이스팅은 프로그래밍에서 주로 JavaScript와 같은 언어에서 발생하는 현상으로, 변수나 함수 선언이 스코프의 상단으로 끌어올려지는 것을 의미합니다.
이러한 현상은 코드 실행 순서와 변수의 유효 범위에 영향을 미치며, 주로 함수 스코프와 블록 스코프에서 발생합니다.

이러한 현상의 문제점 중 하나는 변수의 초기화와 할당이 동시에 이루어지지 않을 수 있다는 점입니다.
이로 인해 예상치 못한 동작이 발생할 수 있으며, 코드의 가독성을 저해할 수 있습니다.
또한, 호이스팅은 코드 이해를 어렵게 만들 수 있으며 디버깅 과정에서 오류를 찾는데 어려움을 초래할 수 있습니다.

이러한 문제를 해결하기 위해서는 변수와 함수를 정의한 위치에서 초기화하고 사용하는 것이 중요합니다.
또한, ES6에서 도입된 let과 const 키워드를 사용하면 호이스팅을 억제하고 스코프를 좀 더 명확하게 정의할 수 있습니다.

### 프로토타입 체인에 대해서 설명해주세요
