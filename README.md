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
|  4  | [순수 함수에 대해 설명해주세요.](#순수-함수에-대해-설명해주세요) |
|  5  | [클로저에 대해서 설명해주세요.](#클로저에-대해서-설명해주세요) |
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

[맨 위로 올라가기](#목차)

---

### 프로토타입 체인에 대해서 설명해주세요
프로토타입 체인은 자바스크립트에서 객체 간 상속 및 프로퍼티 접근을 관리하는 메커니즘입니다.<br>
모든 객체는 프로토타입(Prototype)을 가지며, 이 프로토타입은 다른 객체로부터 상속된 프로퍼티와 메서드를 포함하고 있습니다. <br>
객체에서 어떤 프로퍼티나 메서드를 찾을 때, 먼저 해당 객체 자체에서 찾고, 없으면 프로토타입 체인을 따라 상위 객체에서 해당 항목을 찾습니다. <br>

프로토타입 체인을 짧게 유지하고, 필요한 경우 캐싱을 활용하여 중복된 프로퍼티 검색을 최소화해야 합니다.<br>
또한 ES6부터는 클래스 및 상속 문법을 도입하여 프로토타입 기반 상속을 더 명확하게 다룰 수 있게 되었습니다.<br>

프로토타입 체인과 관련된 주제로는 프로토타입 상속, 프로토타입 객체, 객체 지향 프로그래밍, 자바스크립트의 객체 모델, ES6의 클래스 및 extends 키워드 등이 있습니다.

[맨 위로 올라가기](#목차)

---

### 순수 함수에 대해 설명해주세요
순수 함수는 입력값(인수)에만 의존하며, 외부 상태나 데이터에 의존하지 않으며, 동일한 입력에 대해 항상 동일한 출력을 반환합니다.<br>
또한, 함수 내부에서 어떠한 외부 데이터나 상태도 변경하지 않으며 부작용이 없습니다.<br>

따라서 코드의 예측 가능성과 테스트 용이성을 향상시키며 버그를 줄이고 코드를 더 읽기 쉽게 만듭니다. <br>
병렬 및 분산 환경에서 안정적으로 동작하며, 함수 조합과 함께 사용되어 강력한 함수형 프로그래밍을 구축하는 데 중요한 역할을 합니다.

[맨 위로 올라가기](#목차)

---

### 클로저에 대해서 설명해주세요
클로저(Closure)는 프로그래밍 언어에서 중요한 개념 중 하나로, 함수와 그 함수가 선언된 렉시컬 환경(Lexical Environment) 사이의 관계를 나타냅니다.<br>
클로저는 함수가 다른 함수 내부에서 정의되고, 외부 함수의 범위에 있는 변수에 접근할 수 있는 현상을 가리킵니다.<br>

클로저가 발생하려면 함수 내부에서 또 다른 함수가 정의되어야 합니다. 이 내부 함수를 클로저 함수라고 합니다.<br>
내부 함수가 정의된 함수를 외부 함수라고 합니다. 클로저 함수는 외부 함수의 변수 및 매개변수에 접근할 수 있습니다.<br>
클로저는 렉시컬 스코프 규칙을 따릅니다. 이는 클로저가 선언된 시점에 해당하는 외부 함수의 변수를 기억하고, 나중에 사용할 수 있음을 의미합니다.<br>
클로저 함수는 외부 함수의 변수를 캡처(Capture)하며, 외부 함수가 종료되더라도 해당 변수에 접근할 수 있습니다.<br>

클로저를 사용하여 변수를 보호하고 은닉화할 수 있으며, 정보 은닉과 관련된 디자인 패턴에 활용됩니다.<br>
비동기 작업에서 데이터 상태를 유지하거나 콜백 함수로 데이터를 전달할 수 있습니다.<br>
이벤트 핸들러, 타이머, HTTP 요청과 같은 비동기 작업에서 클로저를 사용하여 콜백 함수를 정의하고 외부 스코프의 데이터를 활용할 수 있습니다.<br>
모듈화된 코드를 구현할 수 있으며, 비공개 및 공개 API를 정의할 때 유용합니다.<br>

[맨 위로 올라가기](#목차)
