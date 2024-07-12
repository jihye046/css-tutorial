## flex-direction
- **row**: 아이템들을 수평 정렬 (기본값)
- **column**: 아이템들을 수직 정렬
- row-reverse: 아이템들을 수평으로 역순 정렬
- column-reverse: 아이템들을 수직으로 역순 정렬
<br>

## flex-wrap
- **nowrap**: 아이템들이 한 줄로 배치되도록 강제 (기본값)
- **wrap**: 아이템들이 컨테이너의 크기에 맞추어 여러 줄로 배치
- wrap-reverse
<br>

## flex-flow
`flex-direction`과 `flex-wrap`을 한번에 지정할 때 사용하며, 공백으로 구분  
- 예) `.item { flex-flow: column wrap; }`
<br>

## justify-content (수평 방향 배치)
- **flex-start**: 아이템들을 컨테이너의 x축 왼쪽에 정렬
- **flex-end**: 아이템들을 컨테이너의 x축 오른쪽에 정렬
- **center**: 아이템들을 컨테이너의 x축 중앙에 정렬
  ![image](https://github.com/user-attachments/assets/360f58cb-4e29-4117-93a4-2c0fffe875dd)
  
- **space-between**: 첫 번째와 마지막 아이템은 컨테이너의 양 끝에 정렬하고, 나머지 아이템들은 동일한 간격으로 배치
- **space-around**: 첫 번째와 마지막 아이템을 동일한 간격으로 배치하고, 나머지 아이템들은 사이에 동일한 간격으로 배치
  ![image](https://github.com/user-attachments/assets/fc438637-dfba-4dfe-84aa-1e53dfcbbd91)

- **space-evenly**: 모든 아이템 사이에 동일한 간격으로 배치
  ![image](https://github.com/user-attachments/assets/96f0f022-2ef5-44bb-9fd9-9b8b50c61de8)
<br>

## align-items (수직 방향 배치)
- **flex-start**: 아이템들을 컨테이너의 y축 위쪽에 정렬
- **flex-end**: 아이템들을 컨테이너의 y축 아래쪽에 정렬
- **center**: 아이템들을 컨테이너의 y축 중앙에 정렬
  ![image](https://github.com/user-attachments/assets/f96edf05-3aa0-4bf6-895a-866e24f96210)
  
- baseline
- stretch
<br>

## align-content
여러 줄 사이의 간격을 지정  
- flex-start
- flex-end
- center
- space-between
- space-around
- stretch
<br>

## order
아이템의 배치 순서를 지정  
- 예) `.item { order: 3; }`
<br>

## flex-basis
아이템이 컨테이너 내에서 차지할 기본 크기를 지정  
- 예) `.item { flex-basis: 60%; }`
<br>

## align-self
개별 아이템의 위치를 지정
- 예) `.item { align-self: baseline; }`
<br>

## MDN
<a href="https://developer.mozilla.org/ko/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox">MDN - flexbox의 기본 개념
<br>

## css code game
<a href="https://flexboxfroggy.com/#ko">![image](https://github.com/user-attachments/assets/2f886526-fada-4035-b8c7-000419619802)
