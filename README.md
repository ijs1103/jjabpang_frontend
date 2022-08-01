# Vite + React + Typescript + Eslint + Prettier 

[boilerplate 출처](https://github.com/TheSwordBreaker/vite-reactts-eslint-prettier)

## 스택

React, Typescript, React-Router, styled-components, redux, @reduxjs/toolkit, react-query

## PR

개인 branch에서 작업 => 단위 기능당 기능 구현 및 리팩토링 완료 후 develop branch에 merge => 배포전 main branch에서 최종 merge

feature/이슈내용, fix/이슈내용, refactor/이슈내용 prefix 붙이기 

## 구조

📦src
 ┣ 📂components
 ┣ 📂hooks
 ┣ 📂pages
 ┣ 📂utils

pages: 페이지 컴포넌트
components: 공통 컴포넌트
hooks: 커스텀 훅
utils: 각종 유틸 함수들

## 규칙

컴포넌트 내부에서의 이벤트 핸들러는 handle prefix

외부에서 props로 주입받은 이벤트 핸들러는 on prefix

ex) onClick(자식에서 props로 받으면), handleClick(부모 내부에서 쓰이면)
