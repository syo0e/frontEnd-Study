HTML

## innerHTML을 쓰면 안되는 이유

### textContent

> textContent의 값은 식별자 노드의 내부 콘텐츠를 text/plain 으로 파싱(Parsing)한 결과이다.
> 즉, 해당 요소 내부의 원시 텍스트(raw text) 이다. 그래서 다른 프로퍼티들에 비해 파싱이 빠르다.

### innerText

> innerText 프로퍼티의 값 또한 text/plain 으로 파싱한 결과이다. 그래서 innerText는 textContent와 혼동하기 쉬우나, 중요한 차이점이 있다. innerText의 값은 원시 텍스트가 최종적으로 (화면에) 렌더링 된 모습, 예를 들어 내용 숨김이나 줄바꿈 같이 의도적인 스타일링이 들어간 후 의 모습이 된다.

### innerHTML

innerHTML 프로퍼티의 값은 text/html으로 파싱한 결과이다. 그래서 상대적으로 파싱이 느리다.
하지만 더 큰 문제는 innerHTML이 대표적으로 xss 공격에 취약한 사례로 언급된다.
