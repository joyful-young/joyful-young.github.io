---
title: "[JavaScript] 자바스크립트 기초"
categories:
    - JavaScript
tags:
    - javascript
    - note
    - mimo_app
toc: true
toc_label: "My Table of Contents"
toc_icon: "cog"
---

최초작성일: 2023-01-15
*작성중*

# JavaScript Basics

## Creating Variables

### Variable Names

- 변수를 생성할 때에는 `let`이나 `const`를 이용한다.
- 변수의 이름은 공백이 없는 한 개의 단어로 이루어져야 한다.
- 다수의 단어를 쓰고 싶으면 `camel case` 사용.
    ```javascript
    let homeCity
    ```
- 잘 알아볼 수 있게 설명해주는 이름으로 지어야 한다.
    ```javascript
    const highScore
    ```
- 변수 이름에 숫자를 포함할 수도 있다.
    ```javascript
    const car1
    ```

<br/>

### Variable Values

- 변수에 변수값을 저장한다.    
    ```
    let 변수 이름 = 변수 값
    ```
- 변수 생성을 끝내려면 세미콜론(semicolon, ;)을 줄 끝에 넣는다.
    ```javascript
    const city = "Chicago"; # 변수 city가 "Chicago"라는 값을 저장
    ```
- 문자열(string)은 큰따옴표(")로 감싼다.

<br/>

### Let and Const Differences
- `const`는 값이 변하지 않을 변수임을 선언하기 위해 사용한다.(constant의 약자)
- `const` 변수에 저장된 값을 업데이트하려고 하면 에러가 발생한다.
    ```javascript
    const age = 90;
    age = 91;

    --> TypeError: Assignment to constant variable
    ```


