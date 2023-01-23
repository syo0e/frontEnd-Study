JAVASCRIPT

\*\* EVENT LOOP

> 자바스크립트는 단일 스레드 기반의 언어로 한 번에 하나의 작업만 처리할 수 있다. 그렇기 때문에
> 자바스크립트 엔진은 어떤 작업을 하면 중간에 어떤 함수도 실행 될 수 없다. 하지만 그렇게 작업을 하게 되면 너무 많은 시간을 사용자는 기다려야 한다. 이러한 문제점을 해결하고자 함수 호출을 관리하는 call stack과 비동기 작업 처리를 위해 web api가 함께 작업을 처리하게 된다. web api는 작업 완료에 시간이 오래 걸리는 작업을 처리하게 되는데 이 결과값을 처리할 수 있는 callback 함수를 task queue에 쌓는다. 이 때 작업이 다 완료되어서 call stack이 비어있게 되면 task queue의 담겨 있는 callback 함수를 다시 call stack으로 담아서 callback을 실행시키게 된댜. 이 작업이 event loop 이다.
