## HTML

\*\* async / defer 의 차이

> <script>가 HTML 파싱과 병렬적으로 실행되는지, 절차적으로 실행되는지에 대한 차이점이 있다. <script>는 HTML 파싱을 중단하고 해당 스크립트를 바로 실행한다. 이 때 스크립트 실행이 다 끝난다면, 다시 HTML 파싱이 재개되어진다. <script async>는 HTML 파싱과 병렬적으로 실행되어지며, HTML파싱이 완료되지 않았어도, 스크립트 실행할 수 있을 때 즉시, 실행되어진다. 마지막으로 <script defer>는 <script async>와 유사하지만, HTML 파싱이 끝나야지만 스크립트가 실행되어진다. 이 태그는 HTML이 파싱이 된 후 스크립트가 실행되어진다는 점에서, <script>태그를 <body> 태그가 끝나기 직전에 위치시키는 것과 거의 비슷한 효과를 가져온다.
