# JavaScript5

## **✅ 내장 객체란?**

- **자바스크립트 엔진에서 기본적으로 제공하는 객체**를 의미하며, 별도의 선언 없이 바로 사용할 수 있습니다.
- 예: `Object`, `Array`, `Math`, `Date`, `String`, `Number`, `RegExp`, `JSON` 등

## **✅ 주요 내장 객체 종류**

### 1. 날짜(Date) 객체

```jsx
var t = new Date();         // 현재 날짜와 시간
var nowMonth = t.getMonth(); // 현재 월 (0~11)
console.log(nowMonth);
```

### 2. 숫자(Number) 객체

```jsx
console.log("표현 가능한 가장 큰 수: " + Number.MAX_VALUE);
console.log("표현 가능한 가장 작은 수: " + Number.MIN_VALUE);
```

### 3. 수학(Math) 객체

```jsx
var maxNum = Math.max(10, 5, 8, 30);  // 최댓값
var minNum = Math.min(10, 5, 8, 30);  // 최솟값
```

### 4. 배열(Array) 객체

```jsx
var num = ['사당', '교대', '방배', '강남'];
num.sort();   // 오름차순 정렬
num.reverse(); // 역순 정렬
```

### 5. 문자열(String) 객체

```jsx
var str = "Web he she he";
str.indexOf("he");    // 첫 번째 'he' 위치
var str2 = "abc";
str2.toUpperCase();   // "ABC"로 변환
```

### 6. 정규 표현식(RegExp) 객체

```jsx
var str = "Html Css Jquery";
var reg1 = /css/;
var result = reg1.test(str); // true 또는 false 반환
console.log(result);
```

### 7. 문서 객체(DOM)

```jsx
<h1 id="title">웹표준</h1>
<script>
  document.getElementById("title").style.color = "blue";
</script>
```

### 8. 브라우저 객체(BOM)

```jsx
<button onclick="myFunction()">창 닫기</button>
<script>
  function myFunction() {
    window.close();
  }
</script>
```