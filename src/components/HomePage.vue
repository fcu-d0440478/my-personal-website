<template>
  <div class="home-page">
    <img src="@/assets/profile.jpg" alt="大頭貼" class="profile-pic">
    <h1>歡迎來到FantasyLin的個人網站</h1>
    <p>這裡是首頁的內容。</p>
    <p>我是一名3C、電腦零件宅，平常也很喜歡玩steam線上遊戲</p>
    <a href="https://github.com/fcu-d0440478" target="_blank">查看我的Github</a>
    <br>
    <router-link to="/about" class="about-button">點擊這裡已獲得更多關於我的資訊</router-link>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  // ...
};
</script>

<style scoped>
.home-page {
  max-width: 800px;
  margin: 0 auto;
  text-align: center;
}

.profile-pic {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  margin-bottom: 20px;
}

.about-button {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  color: #fff;
  background-color: #42b983;
  text-decoration: none;
  border-radius: 5px;
}
</style>