**수업내용정리(feat. notion)**

[11.20 수업내용 정리이동 (゜ ω ゜)=☞](https://www.notion.so/JavaScript-4133c44e7d5a43e5be157bf68d158394)

▶[2020년 11월 20일](#2020년-11월-20일)

▶[2020년 11월 23일](#2020년-11월-23일)

▶[2020년 11월 24일](#2020년-11월-24일)

▶[2020년 11월 25일](#2020년-11월-25일)

# 2020년 11월 20일

- 자바스크립트 수업 첫 시작
- 기초 부분은 자바와 비슷한 부분들이 많은 듯 하다.

  : 그리 해서 내용이 빠르게 지나갔다.

- 자바스크립에 대한 간단한 설명
- 데이터 타입, 출력, 조건문, 반복문, 탈출문, 배열...
- 함수 : 선언적 함수, 익명 함수
  - 함수의 매개변수와 리턴

# 2020년 11월 23일

- **즉시실행 함수**
- **화살표 함수**

  - 가독성이 좋으나, 사용법을 모르는 사람은 무엇인지 알 수 없음. → 자바의 람다식이 생각남.

- **스코프**

  - 함수 스코프와 블럭 스코프

- **클로저**

  - 함수 스코프의 보안 취약점

- **객체** (JSON)
  - 함수 형태를 객체 형태로 만들어 이용할 수 있게 사용했었으나, 이제 맵의 형태로 사용
  - 생성자 형태의 사용
- **JSON 파싱**
  - JSON.stringify(data);
  - JSON.parse(data)

# 2020년 11월 24일

### 이벤트

- **인라인이벤트**
- **기본이벤트**
- **표준이벤트**

# 2020년 11월 25일

### DOM

Document Object Model

문서객체 모델

**Element(태그) 노드 선택**

- getElementById() : object
- getElementsByName() : list
- getElementsByClassName() : list
- getElementsByTagName() : list

**css 선택자를 이용**

- querySelector() : object
- querySelectorAll() : list

노드를 선택, 속성변경, css속성 변경등을 할 수 있다.

**노드생성추가**

- createElement() : 요소생성
- createTextNode() : 텍스트 생성
- appendChild() : 자식 요소 추가
- innerHTML = : 요소에 문자열 추가

### BOM

Browser Object Model
