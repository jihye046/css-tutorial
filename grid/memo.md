## grid 행, 열 생성
- **grid-template-columns**: 열 생성  
  - 예) 100px 크기로 5열 만들기  
    ☝ `.container { grid-template-columns: 100px 100px 100px 100px 100px; }`  
    ✌ `.container { grid-template-columns: repeat(5, 1fr); }`  

- **grid-auto-rows**: 행 생성  
  - 예) 컨텐츠 길이에 따라 크기가 유동적으로 변하되 최소 높이는 150px을 유지하도록  
    ☝ `.container { grid-auto-rows: minmax(150px, auto); }`
<br>

## grid 셀 합치기
- **grid-column**: 열 합치기
  - ☝ 합치려는 column의 '시작번호 / 끝번호'
  - ✌ 합치려는 column의 '시작번호 / span 합치고자하는 칸 개수'
- **grid-row**: 행 합치기
  - ☝ 합치려는 row의 '시작번호 / 끝번호'
  - ✌ 합치려는 row의 '시작번호 / span 합치고자하는 칸 개수'

  [![image](https://github.com/user-attachments/assets/8efd53c9-aa50-4f7f-b34d-7e8e8f0f3639)](https://github.com/jihye046/css-tutorial/blob/main/grid/gridPracC.css)

- 예시
![image](https://github.com/user-attachments/assets/3f2d0db4-6461-4d44-8737-ac5c0c401617)  
☝ `.item2 { grid-column: 2 / 5; grid-row: 1 / 3;}`  
✌ `.item2 { grid-column: 2 / span 3; grid-row: 1 / span 2; }` 
<br>


## grid 간격 조절
- **grid-column-gap**: 열 간격
- **grid-row-gap**: 행 간격
- **grid-gap**: 행, 열 간격
<br>

## grid 배치
- **grid-template-areas**:
    'a a a'
    'b c c'
    'b d g'
    와 같이 가상의 배치 구도를 잡고 아이템을 `grid-area:`를 통해 넣어준다.
- 예) `.container {
            grid-template-areas:
              'a a a'
              'b c c'
              'b d g'
       }`  
       `.image1 { grid-area: a; }`  
       `.image2 { grid-area: b; }`  
       `.image3 { grid-area: c; }`  
       ` ... `  


[![image](https://github.com/user-attachments/assets/957dd6e1-b2d4-4d6d-8382-3687240cf10b)](https://github.com/jihye046/css-tutorial/blob/main/grid/image.css)

[![image](https://github.com/user-attachments/assets/30612ebd-f677-44af-b506-7bc915fe8d22)](https://github.com/jihye046/css-tutorial/blob/main/grid/index.css)

![image](https://github.com/user-attachments/assets/ce6e1747-2f03-4a5c-89a2-47713a3f5141)  
<br>

## MDN 예제
[![image](https://github.com/user-attachments/assets/c7af003c-72ec-4c4b-b3ef-7029f1a988d8)](https://github.com/jihye046/css-tutorial/blob/main/grid/prac/mdnEx.css)  
<br>


## MDN
<a href="https://developer.mozilla.org/ko/docs/Learn/CSS/CSS_layout/Grids">MDN - CSS 그리드  









