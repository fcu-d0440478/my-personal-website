<template>
  <div class="about-page">
    <img src="@/assets/personal-photo.jpg" alt="個人照片" class="personal-photo">
    <h1>關於我</h1>
    <p class="paragraph">您好，我是林永義，畢業於逢甲大學資訊工程所。喜歡攝影、PC電腦零件組裝，以及對3C產品的資訊和趨勢感興趣。而對我來說，程式開發和資料分析不僅僅是專業領域，更是我熱愛且投入的領域。憑藉著五年的Python程式開發經驗，我能夠熟練地進行網頁爬蟲、資料分析以及自然語言處理(NLP)等工作。我熟悉使用Pandas進行Excel資料的讀取和操作，同時也具有Selenium網頁爬蟲和Grafana資料視覺化的經驗。</p>
    <p class="paragraph">除了Python，我還有兩年的Java開發經驗，擅長物件導向程式設計(OOP)，並能夠使用Android Studio進行應用程式開發。在資料庫方面，我使用過MSSQL Server、phpMyAdmin和mongoDB，這些經驗使我能夠進行複雜的資料操作和管理。此外，我還具一年C開發經驗，能夠處裡常見資料結構。另外還有過三個月使用過ASP.NET環境下用C#進行網頁維護的經驗等。</p>
    <p class="paragraph">在工作技能方面，我擁有豐富的軟體工程系統開發經驗，能夠進行PC電腦設備的裝配和軟體程式的設計。我的證照包括Oracle OCP Java Dev.和經濟部初級行動裝置程式設計師(Android)，這些證照證明了我的專業能力。</p>
    <p class="paragraph">在多次的實習經驗中，我學習到了各種技術，包括Selenium自動化測試網頁、C#維護網頁、產線模擬軟體等。我曾參與LineBot每日學習程式語言相關的英文專案，並且進行了應用社群資料分析於檢視線上解題平台內容以提升學習效率的碩士論文研究。</p>
    <router-link to="/" class="home-button">返回首頁</router-link>
  </div>
</template>

<script>
export default {
  name: 'AboutPage',
  // ...
};
</script>

<style scoped>
.about-page {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  text-align: center;
}

.personal-photo {
  width: 100%;
  max-width: 400px;
  margin-bottom: 20px;
}

.paragraph {
  text-align: left;
  text-indent: 2em; /* 添加首行縮進，相當於兩個字符的寬度 */
}

.home-button {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  color: #fff;
  background-color: #42b983;
  text-decoration: none;
  border-radius: 5px;
}
</style>