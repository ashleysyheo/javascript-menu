## 📋 기능 목록

- [x] 시작 문구 출력하기 
- [x] 메뉴 추천을 받을 코치 이름을 입력받기 
  - [x] 예외 사항: 
    - [x] 입력된 코치들이 최소 2명, 최대 5명이 아닌 경우 
    - [x] 입력된 코치의 이름이 최소 2글자, 최대 4글자가 아닌 경우 
    - [x] ','로 구분해서 입력하지 않은 경우 
- [x] 입력된 각 코치가 못 먹는 메뉴를 입력받기 
  - [x] 예외 사항: 
    - [x] 입력된 메뉴들이 최소 0개, 최대 2개가 아닌 경우 
    - [x] ','로 구분해서 입력하지 않은 경우 
- [x] 각 요일별 카테고리 선별하기 
  - [x] 한 주에 같은 카테고리는 최대 2회까지만 고를 수 있다 
    - 카테고리: 일식, 한식, 중식, 아시안, 양식 
    - [x] 추천할 수 없는 카테고리인 경우 랜덤 값을 생성해서 다시 선정한다 
- [x] 각 코치당 요일별 메뉴 선별하기 
  - [x] 각 코치에게 한 주에 중복되지 않는 메뉴를 추천해야 한다 
    - [x] 임의로 선정된 메뉴가 이미 추천한 메뉴, 먹지 못하는 메뉴인지 확인하기 
    - [x] 추천할 수 없는 메뉴인 경우 다시 선정하기 
- [x] 상수 만들기 