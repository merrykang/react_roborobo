# 2. The Basics Of React

> react의 power

- js 만들고 html에 삽입 (<-> 기존 vanila.js : html 만들고 -> js 삽입)
- const h3 = React.createElement("h3", {
  onMouseEnter: () => console.log("mouse enter"),
  }, "Hello, I'm a span");
  - 위 코드가 아래 코드 대체 (1. id 지정 2. getElementById로 선택 3. addEventListener) 사용
    - <button id="btn">Click me</button>
    - const button = document.getElementById("btn");
    - button.addEventListener("mouseenter", handleClick);
- on + event명 = 리액트가 인식하는 event listener 로 인식
