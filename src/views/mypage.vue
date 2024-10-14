<template>
    <div class="mypage-container">
      <h1>마이페이지</h1>
      <ul>
        <li><router-link to="/order-history">주문 기록</router-link></li>
        <li><router-link to="/edit-user-info">사용자 정보 수정</router-link></li>
        <li><router-link to="/qna">Q&A</router-link></li>
        <li><router-link to="/reviews">리뷰</router-link></li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: 'MyPage',
  };
  </script>
  
  <style scoped>
  .mypage-container {
    padding: 20px;
  }
  
  ul {
    list-style-type: none;
  }
  
  li {
    margin-bottom: 10px;
  }
  
  a {
    color: #4CAF50;
    text-decoration: none;
  }
  </style>
  