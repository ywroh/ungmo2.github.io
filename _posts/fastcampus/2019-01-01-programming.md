---
layout: fs-post
title: <strong>프로그래밍</strong>
categories: fastcampus
section: fastcampus
seq: 1
permalink: /:categories/:title
description:
---

* TOC
{:toc}

# 1. 프로그래밍이란?

<!-- 프로그래밍은 수행되기 원하는 명령을 컴퓨터에 전달하는 일종의 **커뮤니케이션**이다. 이때 "수행되기 원하는 명령"을 정의하기 위해서는 해결 과제(문제/요구사항)를 명확히 이해한 후, 복잡함을 단순하게 분해(Decomposition)하고 자료를 정리하고 구분(Modeling)해야하며 순서에 맞게 행위를 배열해야 한다.

다시 말해, 프로그래밍에 앞서 해결 과제를 명확히 이해한 후 적절한 문제 해결 방안의 정의가 필요하다. 이때 요구되는 것이 **문제 해결 능력**이다. 혹자는 문제 해결 능력을 알고리즘과 동일시하려는 경향이 있지만 반드시 그런 것은 아니다. 물론 문제 해결 능력의 함양에 있어 알고리즘 학습은 큰 도움이 되지만 문제 해결 능력은 더 큰 차원의 능력이다.

나는 직감과 직관, 사고 내부에서 본질이라고 할 수 있는 심상이 먼저 나타난다. 말과 숫자는 이것의 표현 수단에 불과하다. <br>- 아인슈타인
{: .info}

아인슈타인의 말처럼 프로그래밍은 문제 해결의 최종 결과물을 작성하는 표현 수단에 불과하다.결코 프로그래밍 자체가 문제를 해결하지는 않는다. 문제 해결 능력은 직감과 직관의 영역이라고 볼 수 있는데 이는 문제를 바라보는 우리의 사고와 경험에 영향을 받는다.

우리는 해결 과제를 명확히 이해한 이후 그 문제의 해결 방안을 고려할 때 컴퓨터의 관점에서 문제를 바라보아야 한다. 이때 필요한 것이 **Computational thinking**이다. 사람의 일반적인 사고 방식은 매우 포괄적이며 실생활에서 경험하고 있는 익숙한 사항에 대해 당연시하는 안이한 인식이 있다.

예를 들어 "듣다(Listen)"라는 행위를 사람은 하나의 간단하고 당연한 기능으로 생각한다. 하지만 컴퓨터에게 이 행위를 설명하는 것은 단순하지 않다. 그리고 사람은 소리의 크기를 "크다" 또는 "작다"고 표현한다. 하지만 크다 또는 작다는 의미는 상대적인 개념으로 기준이 불명확하다. 컴퓨터에게는 양적 개념인 숫자를 사용하여 "현재 볼륨보다 1단계 크게 조정하라" 또는 "볼륨을 60으로 조정하라"고 명령해야 한다. 또한 "좋다", "붉다", "사랑"과 같은 관념적 개념은 컴퓨터에게 매우 난해한 개념이다. 사람은 지인의 얼굴을 보고 누구인지 바로 인지하지만 컴퓨터에게 이것은 매우 어려운 일이다. 3479의 계산은 사람에게는 쉽지 않지만 컴퓨터에게는 매우 쉬운 작업이다. -->

프로그래밍이란 컴퓨터에게 실행을 요구하는 일종의 **커뮤니케이션**이다. 이를 위해 먼저 무엇을 실행하기 원하는지에 대한 정의가 필요하다. 다시 말해, 프로그래밍에 앞서 문제(요구사항)를 명확히 이해한 후 적절한 문제 해결 방안의 정의가 필요하다.

이때 요구되는 것이 **문제 해결 능력**이다. 혹자는 문제 해결 능력을 알고리즘과 동일시하려는 경향이 있지만 반드시 그런 것은 아니다. 물론 문제 해결 능력의 함양에 있어 알고리즘 학습은 큰 도움이 되지만 문제 해결 능력은 더 큰 차원의 능력이다.

대부분의 문제(요구사항)는 복잡하며 명확하지 않을 수도 있다. 따라서 문제(요구사항)를 명확히 이해하는 것이 우선되어야 하며 복잡함을 단순하게 분해(Decomposition)하고 자료를 정리하고 구분(Modeling)해야 하며 순서에 맞게 행위를 배열해야 한다.

즉, 프로그래밍이란 0과 1밖에 알지 못하는 기계가 실행할 수 있는 정도로 **정확하고 상세하게 요구사항을 설명**하는 작업이며 그 결과물이 바로 코드이다. 모호하고 대략적인 요구사항을 전달해도 우리의 머리 속에 있는 의도를 정확히 꿰뚫어 완벽히 이해하는 컴퓨터는 절대 존재할 수 없다.

우리는 문제 해결 방안을 고려할 때 컴퓨터의 입장에서 문제를 바라보아야 한다. 이때 필요한 것이 **Computational thinking**이다. 사람의 일반적인 사고 방식은 매우 포괄적이며 실생활에서 경험하고 있는 익숙한 사항에 대해 당연시하는 안이한 인식이 있다.

문제 해결 능력은 직감과 직관의 영역이라고 볼 수 있는데 이는 문제를 바라보는 우리의 사고와 경험에 영향을 받는다. 예를 들어 "듣다(Listen)"라는 행위를 사람은 하나의 간단하고 당연한 기능으로 생각한다. 하지만 컴퓨터에게 이 행위를 설명하는 것은 단순하지 않다. 그리고 사람은 소리의 크기를 "크다" 또는 "작다"고 표현한다. 하지만 크다 또는 작다는 의미는 상대적인 개념으로 기준이 불명확하다. 컴퓨터에게는 양적 개념인 숫자를 사용하여 "현재 볼륨보다 1단계 크게 조정하라" 또는 "볼륨을 60으로 조정하라"고 명령해야 한다. 또한 "좋다", "붉다", "사랑"과 같은 관념적 개념은 컴퓨터에게 매우 난해한 개념이다. 사람은 지인의 얼굴을 보고 누구인지 바로 인지하지만 컴퓨터에게 이것은 매우 어려운 일이다. 347<sup>9</sup>의 계산은 사람에게는 쉽지 않지만 컴퓨터에게는 매우 쉬운 작업이다.

이처럼 컴퓨터와 사람은 사고, 인지의 방식이 다르다. 따라서 해결 과제를 컴퓨터의 관점으로 사고(Computational thinking)해야 한다. 이에는 논리적, 수학적 사고가 필요하게 되며 해결 과제를 작은 단위로 분해하고 패턴화하여 추출하며 프로그래밍 내에서 사용될 모든 개념은 평가 가능하도록 정의되어야 한다.

예를 들어 사람처럼 두발로 걷는 로봇을 위해 "걷다"라는 기능을 디자인해 보자.

![](/assets/fs-images/1-1.png)
{: .w-450}

2족 보행 로봇의 디자인
{: .desc-img}

"걷다"라는 기능을 디자인하려면 판단하여야 하는 상태와 그 상태를 판단하는 시기, 그리고 판단 기준을 정의하여야 하며 이를 바탕으로 분해한 처리(Process)의 실행 여부를 결정한다. 예를 들어 장애물이란 무엇(크기, 움직임...)인지 어떤 범위 내에 있는 것인지 명확히 수치화하여 정의해야 한다.

# 2.	프로그래밍 언어

이와 같이 문제 해결 능력을 바탕으로 정의된 문제 해결 방안은 컴퓨터에게 전달되어야 한다. 이때 명령을 수행할 주체는 컴퓨터이다. 따라서 인간이 이해할 수 있는 자연어가 아니라 컴퓨터가 이해할 수 있는 언어, 즉 [기계어(Machine code)](https://ko.wikipedia.org/wiki/기계어)로 명령을 전달해야 한다.

인간이 기계어를 이해하여 직접 기계어로 명령을 전달하는 것은 매우 어려운 작업이다. 기계어는 우리가 사용하는 언어와는 너무나도 다른 체계를 가지기 때문이다. 심지어 비트 단위로 기술되어 있다.

아래는 x86 아키텍처 리눅스 환경에서 그 유명한 ["Hello world"](https://ko.wikipedia.org/wiki/"Hello,_World!"_프로그램)를 출력하는 기계어 코드이다.

```
7F 45 4C 46 01 01 01 00 00 00 00 00 00 00 00 00 02 00 03 00 01 00 00 00 35 40 B3 04 2C 00 00 00 00 00 00 00 00 00 00 00 34 00 20 00 01 00 00 00 00 00 00 00 00 40 B3 04 B2 0C EB 1C 62 00 00 00 62 00 00 00 05 00 00 00 00 10 00 00 48 65 6C 6C 6F 20 77 6F 72 6C 64 0A B9 4C 40 B3 04 93 CD 80 EB FB
```

직접 기계어로 명령을 전달하는 것을 대신할 가장 유용한 대안은 인간이 이해할 수 있는 약속된 **구문(Syntax, 문법)**으로 구성된 "프로그래밍 언어(Programming Language)"를 사용하여 프로그램을 작성한 후, 그것을 컴퓨터가 이해할 수 있는 기계어로 변환하여 주는 일종의 번역기를 이용하는 것이다. 이 일종의 번역기를 **컴파일러(compiler) 혹은 인터프리터(interpreter)**라고 한다.

![](/assets/fs-images/1-2.png)
{: .w-450}
컴파일러는 개발자의 언어와 컴퓨터의 언어를 모두 이해하는 번역가
{: .desc-img}

언어(Language)는 자신의 생각을 상대에게 전달하는 방법으로 언어 공동체 내에서 이해될 수 있는 말의 집합이다.

![Communication Model](/img/com-model.png)
{: .w-400}
Communication Model
{: .desc-img}

언어는 자연어와 [인공어](https://ko.wikipedia.org/wiki/인공어)로 구분할 수 있다. 프로그래밍 언어란 컴퓨터와의 대화(명령)에 사용되는 일종의 표현 수단으로 인간과 컴퓨터(컴파일러 또는 인터프리터) 모두가 이해할 수 있는 약속된 형태의 인공어이다.

아래는 "Hello world"를 출력하는 자바스크립트 코드이다. 위의 기계어 코드보다 인간이 이해하기 쉬운, 즉 읽기 쉬운 코드가 되었다.

```javascript
console.log('Hello world');
```

프로그래밍은 프로그래밍 언어를 사용하여 컴퓨터에게 실행을 요구하는 일종의 **커뮤니케이션**이다. 프로그래밍 언어는 **Syntax(구문)**와 **Semantics(의미)**의 조합으로 표현된다.

# 3. Syntax & Semantics

프로그래밍 학습은 일반적으로 프로그래밍 언어의 문법을 배우는 것부터 시작한다. 이는 외국어 학습과 유사하다고 할 수 있다. 그러나 이미 경험을 통해 알고 있겠지만 문법을 잘 안다고 해서 외국어를 잘한다고 말할 수는 없다.

외국어를 잘하려면 외국어 화자의 말이나 문장을 정확히 이해한 후, 문맥에 따른 적절한 어휘 선택, 그리고 순차적으로 결론을 향해 나아가는 문장 구성이 필요하다. 즉, 문법에 맞는 문장을 구성하는 것은 물론 **의미(Semantics)**를 가지고 있어야 언어의 역할을 충실히 수행할 수 있다.

Colorless green ideas sleep furiously.<br> – 노엄 촘스키(Noam Chomsky)
{: .info}

MIT의 저명한 언어학자인 [노엄 촘스키](https://ko.wikipedia.org/wiki/노엄_촘스키)는 위 문장을 통해서 언어의 의미는 문맥에 있는 것이지 문법에 있는 것이 아니란 것을 지적하고 있다. 위 문장은 문법(Syntax)적으로 전혀 문제가 없지만 의미(Semantics)는 없다. 프로그래밍도 마찬가지다. 아래 예제를 보자.

<!--
C 언어로 구현된 아래 예제를 보자.

```c
int x = "five";
// warning: incompatible pointer to integer conversion initializing 'int' with an expression of type 'char [5]' [-Wint-conversion]
```

위 예제는 문법적으로 전혀 문제가 없으나 의미적으로는 옳지 않다. 값 "five"는 정수가 아니라 문자열이다.
-->

```javascript
const number = 'string';

console.log(number * number); // NaN
```

자바스크립트의 변수에는 어떠한 타입의 값이라도 할당할 수 있다. 따라서 위 예제는 문법적으로 전혀 문제가 없다. 하지만 의미적으로는 옳지 않다. number라는 변수 이름에 문자열이 할당되어 있기 때문이다. number라는 변수 이름에는 숫자를 할당하는 것이 의미적으로 옳다.

결국 문제 해결 능력을 통해 만들어낸 해결 방안은 프로그래밍 언어의 문법을 통해 표현한다. 즉, 작성된 코드는 해결 방안의 구체적 구현물이다. 그리고 이것은 프로그래밍 언어의 문법에 부합하는 것은 물론이고 수행하고자 하는 바를 정확히 수행하는 것, 즉 **요구사항이 실현(문제가 해결)**되어야 의미가 있다.

![](/assets/fs-images/1-3.png)
{: .w-450}

프로그래밍의 목적은 문제 해결이다.
{: .desc-img}

대부분의 프로그래밍 언어는 "변수와 값", "키워드", "연산자", "표현식과 문", "조건문"과 "반복문"에 의한 "흐름제어(Control flow)", "함수" 그리고 "객체", "배열" 등의 "자료구조"와 같은 문법을 제공한다.

프로그래밍 언어가 제공하는 문법을 적절히 사용하여 변수를 통해 값을 저장하고 참조하며 연산자로 값을 연산, 평가하고 조건문과 반복문에 의한 흐름제어로 코드의 실행 순서를 제어하고 함수로 재사용이 가능한 문의 집합을 만들며 객체, 배열 등으로 자료를 구조화한다.

**결국 프로그래밍은 요구사항의 집합을 분석하여 적절한 자료구조와 함수의 집합으로 변환한 후, 그 흐름을 제어하는 것이다.**

# Reference

* [Why Learning to Code is So Damn Hard](https://www.vikingcodeschool.com/posts/why-learning-to-code-is-so-damn-hard)

* [Web development roadmap 2019](https://github.com/kamranahmedse/developer-roadmap)