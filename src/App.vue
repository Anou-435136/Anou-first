<template>
  <div id="app">
    <CommonHeader></CommonHeader>
    <main>
      <div class="top-content flex">
        <h1 class="top-title">機械ではできない仕事を</h1>
        <div class="news-content">
          <div class="sub-news-content">
            <div><small>2019/01/01</small></div>
            <p><small>ニュースタイトルがここには入ります。3月の決算報告書</small></p>
          </div>
          <a href="#">news</a>
        </div>
      </div>

      <div class="top-content2">
        <img src="./assets/mission-img.jpg" alt="">
        <div class="text">
          <h2>お客様のために進化する成長企業であり続ける</h2>
          <p>顧客主導型サービスを提供する企業として、お客様の会社経営に必要なサービスと情報を提供し続ける企業支援会社を目指します。企業が現在直面している「勝ち残るため」の戦略を提供できる会社として、ホームページをはじめ、各種マーケティングをご提供いたします。</p>
          <a href="#">ミッション詳細</a>
        </div>
      </div>

      <div id="service-content">
        <h2 class="section-title">service</h2>
        <img src="./assets/service2.jpg" alt="">
        <div class="service-text1">
          <h3>web制作事業</h3>
          <small>コーチングのミッション</small>
          <p>ユーザーが求める物を分析し、ユーザービリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります</p>
          <a  href="#">サービス詳細</a>
        </div> 
        <img src="./assets/service1.jpg" alt="">
        <div class="service-text1">
          <h3>web制作事業</h3>
          <small>コーチングのミッション</small>
          <p>ユーザーが求めるものを分析し、ユーザービリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります。</p>
          <a href="#">サービス詳細</a>
        </div>
      </div>

      <div id="sub-content">
        <div class="sub-content-img flex between">
          <img class="img1" src="./assets/company.jpeg" alt="">
          <img class="img2" src="./assets/recruit.jpg" alt="">
        </div>
        <div class="campany-text">
          <h2 class="section-title">company</h2>
          <p>会社概要</p>
        </div>
        <div class="recruit-text">
          <h2 class="section-title">recruit</h2>
          <p>採用情報</p>
        </div>
        <div class="faq-content flex">
          <h2>FAQ</h2>
          <p>良くある質問</p>
        </div>
      </div>

      <div id="contact">
        <div class="contact-title">
          <h2 class="section-title">contact</h2>
          <h3>お問い合わせ</h3>
        </div>
        <p class="contact-catchphrase">お気軽にお問い合わせください。</p>
        <p class="contact-text">資料請求・お問い合わせなどお気軽にお問い合わせください。お仕事のご連絡もお問い合わせページに飛んでいただいて、入力フォーム
        ご記入お願いいたします。
        </p>
        <p><a href="#">お問い合わせへ</a></p>
      </div>
    </main>
    <CommonFooter></CommonFooter>
  </div>
</template>

<script>
import CommonHeader from "./components/CommonHeader.vue";
import CommonFooter from "./components/CommonFooter.vue";
export default {
  components: {
    CommonHeader,
    CommonFooter
  }
};
</script>

<style>
/* @charset "UTF-8";はVue.jsでは必要ないです */

/*
html5doctor.com Reset Stylesheet
v1.6.1
Last Updated: 2010-09-17
Author: Richard Clark - http://richclarkdesign.com
Twitter: @rich_clark
*/

html, body, div, span, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
abbr, address, cite, code,
del, dfn, em, img, ins, kbd, q, samp,
small, strong, sub, sup, var,
b, i,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, figcaption, figure,
footer, header, hgroup, menu, nav, section, summary,
time, mark, audio, video {
    margin:0;
    padding:0;
    border:0;
    outline:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

body {
    line-height:1;
}

article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section {
    display:block;
}

nav ul {
    list-style:none;
}

blockquote, q {
    quotes:none;
}

blockquote:before, blockquote:after,
q:before, q:after {
    content:'';
    content:none;
}

a {
    margin:0;
    padding:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

/* change colours to suit your needs */
ins {
    background-color:#ff9;
    color:#000;
    text-decoration:none;
}

/* change colours to suit your needs */
mark {
    background-color:#ff9;
    color:#000;
    font-style:italic;
    font-weight:bold;
}

del {
    text-decoration: line-through;
}

abbr[title], dfn[title] {
    border-bottom:1px dotted;
    cursor:help;
}

table {
    border-collapse:collapse;
    border-spacing:0;
}

/* change border colour to suit your needs */
hr {
    display:block;
    height:1px;
    border:0;  
    border-top:1px solid #cccccc;
    margin:1em 0;
    padding:0;
}

input, select {
    vertical-align:middle;
}


.section-title {
 font-size: 35px;
 font-weight: bold;
 text-align: center;
 padding: 18px;
}

img {
  width: 100%;
  display: block;
}

.flex {
  display: flex;
  align-items: center;
}

.between {
  justify-content: space-between;
}

.around {
  justify-content: space-around;
}

.top-content {
  height: 700px;
  background-image: url(./assets/eyecatch.jpg);
  background-size: cover;
  background-position: center;
  position: relative;
}

.top-title {
  font-size: 45px;
  transform: skew(-10deg);
  color: #fff;
  margin: 200px 0 0 150px;
}

.news-content .sub-news-content {
  position: absolute;
  bottom: 0;
  right: 150px;
  width: 40%;
  height: 50px;
  background-color: #fff;
}

.news-content a {
  position: absolute;
  bottom: 0;
  right: 0;
  display: block;
}

.top-content a {
  width: 150px;
  height: 60px;
  line-height: 60px;
  text-align: center;
  font-size: 13px;
  background-color: #000;
  color: #fff;
  text-decoration: none;
}

.news-content div {
  font-size: 15px;
  padding: 5px;
}

.news-content p {
  font-size: 13px;
  padding-left: 15px;
}

.top-content2 {
  height: 480px;
  background-color: #000;
  position: relative;
}

.top-content2 img {
  position: absolute;
  top: 120px;
  right: 75px;
  width: 620px;
  z-index: 1;
}

.text {
  position: absolute;
  top: 150px;
  left: 290px;
  width: 52%;
  color: #fff;
  z-index: 2;
}

.text h2 {
  font-size: 24px;
}
.text p {
  font-size: 13px;
  line-height: 25px;
  margin: 25px 0;
}

.text a {
  font-size: 13px;
  padding: 5px 20px;
  color: #000;
  background-color: #fff;
  text-decoration: none;
}

#service-content {
  margin-top: 160px;
  height: 1300px;
  background-color: #cccccc;
  position: relative;
}

#service-content img:nth-of-type(1) {
  position: absolute;
  right: 0;
  width: 50%;
}

#service-content img:nth-of-type(2) {
  position: absolute;
  left: 0;
  top: 50%;
  width: 50%;
}

/* #service-content img:nth-of-type(1) {
  margin-left: auto;
} */

.service-text1 {
  width: 480px;
  padding: 75px;
  background-color: #fff;
}

.service-text1 h3 {
  font-size: 14px;
}

.service-text1 small {
  display: inline-block;
  font-size: 13px;
  margin: 17px 0;
}

.service-text1 p {
  font-size: 13px;
  line-height: 20px;
  margin-bottom: 10px;
}

.service-text1 a {
  display: block;
  width: 120px;
  font-size: 12px;
  padding: 9px;
  margin-left: auto;
  text-align: center;
  color: #000;
  border: 1px solid #000;
  text-decoration: none;  
}

.service-text1:nth-of-type(1) {
  position: absolute;
  top: 200px;
  left: 300px;
}

.service-text1:nth-of-type(2) {
  position: absolute;
  bottom: 300px;
  right: 300px;
}

#sub-content {
  height: 800px;
  position: relative;

}

.sub-content-img img {
  width: 47%; 
  height: 240px;
  object-fit: cover;
  margin-top: 150px;
  z-index: 1;
}

.campany-text {
  position: absolute;
  top: 220px;
  left: 250px;
  color: #fff;
  z-index: 2;
}

.recruit-text {
  position: absolute;
  top: 220px;
  right: 270px;
  color: #fff;
  z-index: 2;
}
.campany-text p, .recruit-text p {
  font-size: 16px;
  font-weight: bold;
  text-align: center;
}

.faq-content {
  width: 85%;
  padding: 65px;
  margin: 180px auto; 
  color: #fff;
  background-color: #000;
}

.faq-content h2 {
  font-size: 30px;
}

.faq-content p {
  font-size: 18px;
  width: 90%;
  text-align: center;
  letter-spacing: 2px;
}

#contact {
  background-image: url(./assets/contact-bg.jpg);
  background-position: center;
  background-size: cover;
  color: #fff;
  margin-top: 120px;
  padding: 180px 0;
  text-align: center;
}

#contact h1 {
  font-size: 30px;
}

#contact p {
  width: 100%;
  margin: 50px 0;
}

#contact a {
  color: #fff;
  padding: 8px 25px;
  border: 1px solid #fff;
  text-decoration: none;
}

.contact-catchphrase {
  font-size: 40px;
}

@media screen and (max-width: 768px) {
  .top-content {
    width: 100%;
  }

  .top-title {
    font-size: 70px;
    margin: auto;
    text-align: center;
  }

  .news-content .sub-news-content {
    position: absolute;
    bottom: 0;
    right: 70px;
    width: 80%;
  }

  .news-content a {
    width: 70px;
  }

  .top-content2 {
    position: relative;
    height: 490px;
  }

  .top-content2 img {
    position: absolute;
    top: 450px;
    right: 20px;
    width: 150px;
    height: auto;
  }

  .text {
    position: absolute;
    top: 50px;
    left: 60px;
    width: 70%;
    line-height: 45px;
  }

  .text h2 {
    font-size: 30px;
    letter-spacing: 2px;
  }

  .text a {
    font-size: 15px;
    padding: 10px 35px;
  }

  #service-content {
    margin-top: 45px;
    height: 1050px;
    position: relative;
  }

  #service-content img {
    width: 90%;
    margin: 0 auto 280px;
  }

  .service-text1 {
    width: 83%;
    height: 200px;
  }

  .service-text1:nth-of-type(1) {
    top: 296px;
    left: 18px;
    padding: 20px 14px 0;
  }

  .service-text1:nth-of-type(2) {
    top: 766px;
    left: 18px;
    padding: 20px 14px 0;
  }

  .sub-content {
    position: relative;
  }

  .sub-content-img img {
    width: 100%;
    height: auto;
    margin-top: 50px;
  }

  .img2 {
    position: absolute;
    top: 248px;
    left: 0;
  }

  .campany-text {
    position: absolute;
    top: 130px;
    left: 83px;
  }

  .recruit-text {
    position: absolute;
    top: 370px;
    left: 110px;
  }

  .recruit-text p {
    width: 160px;
    text-align: center;
  }

  .faq-content {
    width: 60%;
    margin: 300px auto;
  }
  
  #contact {
    height: 380px;
    margin-top: 10px;
  } 
  
  #contact p {
    width:85%;
    margin: 50px auto;
    text-align: center;
  }

  .contact-text {
    line-height: 30px;
  }
}
</style>
