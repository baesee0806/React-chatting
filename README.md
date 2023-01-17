## 기획

React chatting

- 유저끼리 실시간 채팅을 할수있다.

## 스택

- React
- React query
- Axios
- Typescript
- Scss / Sass
- Styled components
- firebase

## pigma

[https://www.figma.com/file/pty89Qnz93086BnKTtBzKA/Untitled?node-id=0%3A1&t=nbhiRUF5Kjd4T7eJ-1](https://www.figma.com/file/pty89Qnz93086BnKTtBzKA/Untitled?node-id=0%3A1&t=nbhiRUF5Kjd4T7eJ-1)

## 파일 구조

component

- mk login
- mk user
- mk chat

page

- login.jsx
- user.jsx
- chat.jsx

share

- router.js

common

- firebase.js
- util.js

## DB 구조

로그인후 ⇒ 유저 검색 ⇒ 해당유저 채팅 누르면 ⇒ firestore database Chat 컬렉션 생성 ⇒ 안에 채팅 추가

{

createdAt

text

uid

}

유저 검색

## 트러블 슈팅
