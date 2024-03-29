- Reactive Extensions For JavaScript의 약자로, 리액티브 프로그래밍을 지원하는 라이브러리이다.
- 함수형 프로그래밍, Observer 패턴, Iterator 패턴을 조합하여 제공하는 형태이다.
- Observer 패턴은 시스템에 의해 발생하는 이벤트를 감시하여, 이벤트 발생 시마다 사전에 정의된 동작을 수행하게 하는 프로그래밍 패턴의 한 종류이다.
- Iterator 패턴은 반복자 패턴이라고도 하며, 구조가 서로 다른 각각의 저장 객체에 접근하기 위해 인터페이스를 통일할 때 사용되는 프로그래밍 패턴의 한 종류이다.
- RxJS는 일련의 이벤트들로 이루어진 이벤트 스트림을 Observable 객체로 매핑하여, 비동기 형식의 이벤트 형태로 작동하도록 한다.
- 즉, 자바스크립트의 비동기 프로그래밍에서 나타나는 문제점들을 해결하기 위해 사용된다.
- RxJS의 Observable 라이프 사이클은 다음과 같이 구성된다.
- 생성 : 이벤트는 생성 시점에 발생되지 않는다.
- 구독 : 이벤트를 구독하는 시점이다.
- 구독 해제 : 구독하고 있는 대상의 구독이 모두 종료되는 시점이다.
- 실행 : 이벤트를 구독하는 대상에게 값을 리턴한다.
