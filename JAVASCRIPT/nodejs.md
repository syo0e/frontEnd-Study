JAVASCRIPT

Nodejs는 싱글 스레드 인가

> node.js는 싱글 스레드 방식이 아니다. 싱글 스레드 방식으로 동작하는 것은 브라우저에 내장된 자바스크립트 엔진이다. 만약 모든 자바스크립트 코드가 자바스크립트 엔진에서 싱글 스레드 방식으로만 동작한다면 비동기적으로 동작할 수 없을 것이다. 즉, 자바스크립트 엔진은 싱글 스레드로 동작하지만 브라우저나 node.js는 멀티 스레드로 동작하는 것이다.
