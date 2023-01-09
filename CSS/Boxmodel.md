CSS

## Box Model

> css 박스 모델은 문서 트리의 요소에 대해 생성되고 시각적 포맷팅 모델에 따라 배치된 사각형 상자를 나타낸다. 각 박스에는 content 영역과 padding, border, margin 영역을 선택적으로 사용할 수 있다.

- 블록 요소가 공간을 얼마나 차지하는지
- 테두리 또는 여백이 겹치거나 총돌하는지 여부
- 박스의 크기 등을 계산한다.

규칙은 다음과 같다.

- 블록 요소의 크기는 width, height, padding, border, margin에 의해 계산된다.
- height가 지정되어 있지 않으면, 블록 요소는 포함하고 있는 내용만큼의 높이를 가질 것이고, Padding을 더한다. (float이 아닌 경우)
- width가 지정되어 있지 않으면, float가 아닌 블록 요소는 부모의 너비(padding)에 맞게 확장된다.
- 요소의 height는 내용의 height에 의해 계산된다.
- 요소의 width는 내용의 width에 의해 계산된다.
- 기본적으로 padding과 border는 요소의 width와 height의 일부가 아니다.
