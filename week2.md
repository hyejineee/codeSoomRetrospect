## Fact (한 것) & Findings(배운 것)

### 강의를 통해서

강의에 첨부된 글을 통해 탄생배경과 핵심개념에 대해서 학습했다. 더불어 어떻게 리액트를 활용하여 개발해야 하는지에 대한 이정표를 얻을 수 있었다. 추가적으로 궁금한 내용에 대해서 naver d2에 있는 글과 리액트 공식문서에 있는 글을 참고하면서 학습했다. 

- VirtualDOM
    - 리액트는 ReactDOM의 render()함수를 통해 리액트에서 사용하는 컴포넌트들을 만들고 VirtualDOM을 생성한다. Virtual DOM과 DOM을 비교하여 변경이 발생한 경우 DOM을 업데이트 한다.

        [React 적용 가이드 - React 작동 방법](https://d2.naver.com/helloworld/9297403)

    - Reconciliation

        [Reconciliation - React](https://reactjs.org/docs/reconciliation.html)

        문서를 읽으면서 key를 사용해야 하는 이유, 키 값을 정할 때 고려할 사항도 추가적으로 알게 되었다.   
        Diffing Algorithm을 통해 state가 어떻게 유지 되는지에 대해서 알게 되었다. 

- Component
    - UI를 재사용 가능한 개별적인 여러 조각으로 나눔.
    - All React components must act like pure functions with respect to their props.

        [React.Component - React](https://ko.reactjs.org/docs/react-component.html)

- useState hook
    - state에 대한 문서를 보면서 어떻게 state변수를 선언할지에 대한 가이드를 얻었다.  

    [Hooks FAQ - React](https://ko.reactjs.org/docs/hooks-faq.html#how-does-react-associate-hook-calls-with-components)
    
    [Using the State Hook - React](https://reactjs.org/docs/hooks-state.html#tip-using-multiple-state-variables)
    
- 관심사의 분리  
    잘 와닿지 않아....😫😫😫😫😫😫😫

### 과제를 통해서
- 변수가 살아있는 기간이 길수록 더 구체적인 변수명이어야 하고 짧을수록 단순한 이름이 좋다.
- 하지말라는 거 다 하고 있었다. [닌자 코드](https://ko.javascript.info/ninja-code#ref-872)
- [리액트 조건 렌더링](https://reactjs.org/docs/conditional-rendering.html#inline-if-with-logical--operator) 과 자바스크립트 && 연산자
- input에 대해서 state 업데이트에 대한 핸들러를 작성하는 대신 비제어 컴포넌트를 만들어 Ref를 사용하여 DOM의 폼 값을 가져올 수 있다. (좀 더 공부가 필요하다!)  
https://reactjs.org/docs/uncontrolled-components.html
https://reactjs.org/docs/refs-and-the-dom.html


## Feelings(느낀 것) & Affirmation(자기 선언)

### 변수의 이름 짓기에 대해 공부한 적이 없다.  
 변수 네이밍은 항상 어렵다. 네이밍 하는 게 너무 어려워서 어떻게 변수를 짓는지에 대해서 검색해 보았다. 생각해보니 변수나 메소드명을 짓는 것에 대해서 공부한 적이 없는 것 같다. 😎구직 지원금 flex😎로 개발자의 글쓰기라는 책을 샀었는데 아직 읽지는 않았다. 변수 네이밍에 대한 내용이 있는데 읽고 나름의 가이드를 세워야 할 것 같다. 

### 역쉬 이해했다는 착각.
관심사의 분리, 책임의 할당 같은 말은 오브젝트나 객체지향의 사실과 오해에서 많이 보았던 단어이다. 그러나 잘 모르겠다. 눈알 운동만 열심히 했다. 어떻게 공부할 것인가?라는 책에서 읽은 대로 질문을 만들고 나름대로 시험을 만들어서 공부했는데 뭔가 글자 암기력 테스트 같은 느낌이다. 이해하고 있다는 느낌이 들지 않는다. 어떻게 하면 암기력 테스트가 아닌 이해에 대한 시험을 만들 수 있을까?? 🤔🤔🤔 

### 📕 사지만 말고 읽자!
윤석 님과 코드 리뷰를 통해서 자바스크립트에서 객체 복사 시 객체의 프로퍼티는 재활용된다는 사실을 알았다. 추가로 코어 자바스크립트 책도 알려주셨는데 집에 있는 거다... (갑자기 또 읽지 않은 책 하나가 생각난다,, 잘 있나요,,, 제 오만 원,,,) 다음 주 자바스크립트 코딩의 기술을 시작으로 사놓기만 한 책들을 읽어야겠다. 목표는 한 달에 3권 이상이다.  

---
추석 전 주라 알바하는 매장이 오지게 바빠졌다.(힘드뤄...) 때문에 트레이너님과 코드리뷰 티키타카가 좀 느린 템포로 진행된 느낌이다. 알바 끝나고 집에 오면 뻗어서 뒹굴거리지 말고 컴퓨터 앞에 바로 앉아야겠다ㅏㅌㅌㅌ