**수업내용정리(feat. notion)**

[11.20 수업내용 정리이동 (゜ ω ゜)=☞](https://www.notion.so/JavaScript-4133c44e7d5a43e5be157bf68d158394)

▶[2020년 11월 20일](#2020년-11월-20일)

▶[2020년 11월 23일](#2020년-11월-23일)

▶[2020년 11월 24일](#2020년-11월-24일)

▶[2020년 11월 25일](#2020년-11월-25일)

▶[2020년 11월 26일](#2020년-11월-26일)

▶[2020년 11월 27일](#2020년-11월-27일)

▶[2020년 11월 30일](#2020년-11월-30일)

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
  - `JSON.stringify(data)`
  - `JSON.parse(data)`

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

- `getElementById()` : object
- `getElementsByName()` : list
- `getElementsByClassName()` : list
- `getElementsByTagName()` : list

**css 선택자를 이용**

- `querySelector()` : object
- `querySelectorAll()` : list

노드를 선택, 속성변경, css속성 변경등을 할 수 있다.

**노드생성추가**

- `createElement()` : 요소생성
- `createTextNode()` : 텍스트 생성
- `appendChild()` : 자식 요소 추가
- `innerHTML` = : 요소에 문자열 추가

# 2020년 11월 26일

**list라는 것이 사용할 수 있는 모든것을 보여줌**

`console.dir(list);`

### 노드삭제

- `remove()`
- `removeChild()`

### 노드삭제를 위한 자식선택

- `childNodes` : 공백 포함 자식 엘리먼트 선택
- `children` : 공백 제외한 순수 자식 엘리먼트 선택

### 형제 노드 선택

- 부모노드
  - `parentElement`
  - `parentNode`
- 다음형제노드
  - `nextElementSibling`
  - `nextSibling` // 텍스트까지 잡아냄 , 공백포함
- 이전형제노드
  - `previousElementSibling`
  - `previousSibling` // 텍스트까지 잡아냄 , 공백포함
- 자식노드
  - `firstElementChild`
  - `firstChild` // 텍스트까지 잡아냄 , 공백포함

# 2020년 11월 27일

### 노드의 속성 추가 및 제거

- `getAttribute()` : 요소의 속성 취득
- `setAttribute()` : 요소의 속성 저장
- `removeAttribute()` : 요소의 속성 제거

### 이벤트 위임

- `event.target` : 이벤트 걸린곳
- `event.currentTarget` : 실제 이벤트가 걸렸있는 곳!

### 캡처링/버블링

**DOM의 동작방식 : 버블링**

**캡처링**

**버블링**

`stopPropagation()` : 이벤트의 전파를 막는다, 실제 잘 사용하지 않음.

`preventDefault()` : 고유특성을 가진 태그의 이벤트를 제거

# 2020년 11월 30일

### 토글탭 만들기

### form 사용

- 유일하게 name으로 바로 접근이 가능함.

### 날짜 사용

- `new Date();`

### BOM

- DOM은 BOM의 자식 객체라고 생각하면 됨
- window, location, history, document, navigator......등등

**window 객체**

1. 팝업

   - `window.open()` : 새로운 창을 띄워주는 메서드

2. 기본 내장 함수

   - `window.alert()` 인데 생략 후 사용

   - 인터벌

     - `setInterval(실행할 함수, 인터벌시간)` : 인터벌시간에 1번씩 함수 실행

     - `clearInterval(멈출 setInterval함수)` : 인터벌 함수 종료

     - `setTimeout(실행할 함수, 연기시간)` : 연기시간 후 함수 실행

     - `clearTimeout(멈출 setTimeout함수)` : 타임함수 실행 전 종료
