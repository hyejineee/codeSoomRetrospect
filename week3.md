# 3주차 회고👀

이번주는 제대로 한게 없어 간단하게 회고 올립니다.😭😭😭😭😭😭😭

**한 일**

- Todo 에서 사용된 컴포넌트의 테스트 코드를 작성하는 과제를 수행했다. 

**배운 점**

- 리액트 컴포넌트를 테스트 하는 방법을 배웠다.

- Describe-context-it 패턴을 배웠다. 

  - https://www.betterspecs.org/
  - https://johngrib.github.io/wiki/junit5-nested

- 테스트 커버리지에 대해서 제대로 알게 되었다. 

  테스트 커버리지에 대한 내용은 정보처리기사를 공부하면서 알게 되었지만 이해가 잘 안갔는데 이번에 경험해보고 어떻게 테스트 커버리지를 상승시키는지에 대해 알게 되었다. 처음 과제를 시작할때 테스트 커버리지 100% 달성을 위해서 컴포넌트의 코드를 고쳤더랬는데ㅋ큐ㅠ 테스트 코드를 통해서 해당되는 부분(?)을 실행 시키면 커버리지가 올라간다는 것을 알게 되었다.   

  

**느낀 점 & 자기 선언** 

월요일 부터 토요일까지 알바하는 매장에서 미친듯이 일을 시켜서 이번주는 제대로 공부한게 없다...(💀~~죽을맛~~) 때문에 과제를 위해서 살짝 살짝 본 것 뿐이라 아쉽다ㅠㅠㅠ. 위의 종립님의 블로그를 찾아본 것도 너무 힘들어서 영어가 안읽힌다. 한글도 잘 안읽힘...

공부하는 것에 시간을 많이 할애하지 못했지만 그래도 과제를 수행하면서 몇 가지 궁금한 점(~~사실 오늘 생긴...~~)이 생겼다. 다음 궁금한 사항들은 화요일쯤 정리할 생각이다. (~~내일도 알바간다. 실화?~~)

* 인수 테스트와 컴포넌트 테스트의 다른 점은 무엇인가?

  정리되지는 않았지만 인수테스트는 ux-flow이고 컴포넌트 테스트는 화면에 원하는게 그려져 있냐 에 대한 차이가 아닐까....

* `each test` 의 범위(?)는 어디서 부터 어디까지? 

  > [`Cleanup`](https://testing-library.com/docs/react-testing-library/api#cleanup) is called after `each test` automatically by default if the testing framework you're using supports the `afterEach` global (like mocha, Jest, and Jasmine). 

  아직 제대로 보지는 못했지만 test, describe, context, it에 대해서 구분할 줄 알면 알게 되지 않을까.... 

* 상태변경에 대한 것을 컴포넌트에서 하는 것이 좋을까? 

  처음 App컴포넌트의 테스트 코드를 작성했을 때 안드로이드 단위 테스트처럼 app객체를 만들고 state를 변경하는 함수를 호출해서 테스트해야지 라고 생각했었는데 느낌이 싸하여 찾아봤더니 다음과 같이 권장하지 않는다고 한다.

  > If it relates to rendering components, it deals with DOM nodes rather than component instances, nor should it encourage dealing with component instances.

* 상태를 변경하는 코드에 대해서 이렇게 테스트 하는 것이 최선인가?