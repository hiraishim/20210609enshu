<template>
 <div id="app">
  <CommonHeader></CommonHeader>
  
  
    <div id="firstview">
     <p class="catchcopy">機械ではできない仕事を</p>
      <div class="newsflex">
        <div class="news-content">
          <p class="news_date">2019/01/01</p>
          <p class="news_title">
            ニュースタイトルがここには入ります。3月の決算報告書
          </p>
       </div>
        <div class="news-icon">news</div>
      </div>
    </div>  
 <div id="hamburger">
      <span></span>
      <span></span>
      <span></span>
    </div>
<main>
      <div class="mission">
         <div class="mission-content">
          <h2 class="mission_title">
            お客様のために進化する成長企業であり続ける
          </h2>
          <p class="mission_text">
            顧客主導型サービスを提供する企業として、お客様の会社経営に必要なサービスと情報を提供し続ける企業支援会社を目指します。企業が現在直面している「勝ち残るため」の戦略を提供できる会社として、ホームページをはじめ、各種マーケティングをご提供いたします。
          </p>
          <!--このbtnを修正1/4-->
          <a href="" v-on:click="CommonBtnMissionBtn">ミッション詳細</a>
         </div>
        <div class="mission-img">
          
         </div>
      </div>
    
      <div class="service">
        <h2 class="service-title section-title">service</h2>
        <div class="service-content">
          <div class="service-img">
            
          </div>
          <div class="service-content_inner">
            <h3 class="mgb-15">web制作事業</h3>
            <p class="mgb-15">コーチングのミッション</p>
            <p class="mgb-15">
              ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります
            </p>
            <!--このbtnを修正2/4-->
            <a href="" v-on:click="CommonBtnServiceBtn">サービス詳細</a>
          </div>
        </div>
        <div class="service-content">
          <div class="service-img service-img_second">
            
          </div>
          <div class="service-content_inner service-content_inner-second">
            <h3 class="mgb-15">web制作事業</h3>
            <p class="mgb-15">コーチングのミッション</p>
            <p class="mgb-15">
              ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります
            </p>
            <!--このbtnを修正3/4-->
            <a href="" v-on:click="CommonBtnServiceBtn">サービス詳細</a>
          </div>
        </div>
      </div>

      <div class="company">
        <div class="recruit-company flex">
          <div class="recruit-company_size company-img">
            <h2 class="company-title section-title">
              company<br /><span>会社概要</span>
            </h2>
          </div>
          <div class="recruit-company_size recruit-img">
            <h2 class="company-title section-title">
              recruit<br /><span>採用情報</span>
            </h2>
          </div>
        </div>
      </div>
      <div class="faq">
        <h2 class="faq-title">FAQ</h2>
        <p class="faq-title-jp">良くある質問</p>
      </div>
      <div class="contact">
        <h2 class="contact-title section-title">
          contact<br /><span>お問い合わせ</span>
        </h2>
        <p class="contact-subtitle section-title">
          お気軽にお問い合わせください。
        </p>
        <p class="contact-text">
          資料請求・お問い合わせなどなんでも気軽にお問い合わせください。お仕事のご連絡もお問い合わせページに飛んでいただいて、入力フォームにご記入お願いいたします。
        </p>
        <!--このbtnを修正4/4-->
        <a href="" v-on:click="CommonBtnContactBtn">お問い合わせへ</a>
      </div>
    </main>
    <CommonFooter></CommonFooter>
  </div>
</template>

<script>
import CommonHeader from "./components/CommonHeader.vue";
import CommonFooter from "./components/CommonFooter.vue";
export default {
  methods: {
    CommonBtnMissionBtn(){
     console.log("ミッション詳細");
    },
    CommonBtnServiceBtn(){
      console.log("サービス詳細");
    },
    CommonBtnContactBtn(){
      console.log("お問い合わせ");
    }
  },

   components:{
     CommonHeader,
     CommonFooter
  },
};
</script>




  
<style>
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

/*共通のスタイル*/
html {
  height: 100%;
}

a {
  color:#333333;
  text-decolatation: none;
}

img {
  width: 100%;
  height: 100%;
  display: block;
}

.flex{
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap:wrap;
}
body{
  color:#333333;
  height:100%;
}
.mgb-15{
  margin-bottom:15px;
}
.common-btn{
   display:block;
   width: 130px;
   height :40px;
   line-height: 40px;
   background: #fff;
   padding: 0 20px;
   color :#000;
   text-align: center;
}

.section-title {
  font-size: 40px;
  line-height: 1;
}

.section-title span {
  font-size: 20px;
}

#firstview {
  height: 500px;
  background: url(../img/eyecatch.jpg) no-repeat;
  background-size: cover;
  background-position: center;
  position: relative;
}

.catchcopy  {
  position: absolute;
  top: 60%;
  left: 10%;
  font-family:MS Gothic;
  font-size: 50px;
  font-style: italic;
  font-weight: bold;
  color: #fff;
  line-height: 1;
}
/*news*/
.newsflex {
  position: absolute;
  bottom: 0;
  right: 0;
  width: 50%;
  display:flex;
}
.news-content {
  background: #fff;
  width: 80%;
  height: 50px;
}

.news_date {
  padding-left: 5px;
}

.news_title {
  padding: 0 15px;
}
.news-icon {
  background: #000;
  width: 20%;
  height: 50px;
  line-height: 50px;
  text-align: center;
  color: #fff;
}


/*mission*/
.mission {
  position: relative;
  background: #000;
  margin-bottom: 10%;
  z-index: 999;
}

.mission-content {
  padding: 10% 0 10% 20%;
  box-sizing: border-box;
  width: 70%;
}

.mission_title,
.mission_text {
  margin-bottom: 30px;
  color: #fff;
}

.mission_title {
  font-size: 30px;
}

.mission-img {
  background: url(../img/mission-img.jpg)center/cover no-repeat;
  width: 5%;
  position: absolute;
  bottom: -10%;
  right: 5%;
  padding:15%;
  z-index: -999;
}

/*service*/
.service {
  background: #e5e5e5;
  margin-bottom: 10%;
}

.service-title {
  text-align: center;
  padding: 20px 0;
}

.service-content {
  position: relative;
  padding-bottom: 15%;
}

.service-img {
  background : url(../img/service1.jpg)center/cover no-repeat;
  width: 50%;
  margin-left: 50%;
  padding-top:35%;


}

.service-img_second {
  background :url(../img/service2.jpg)center/cover no-repeat;
  margin: 0 50% 0 0;
  padding-top:35%;
}

.service-content_inner {
  position: absolute;
  top: 15%;
  left: 20%;
  background: #fff;
  width: 40%;
  padding: 5% 5%;
  box-sizing: border-box;
}

.service-content_inner-second {
  left: 40%;
}

.service-btn {
  border: 1px solid #000;
  margin: 0 0 0 auto;
}

/*company*/
.company {
  margin-bottom: 10%;
}

.recruit-company_size {
  width: 48%;
  height: 200px;
  position: relative;
}

.company-img {
  background: url(../img/company.jpeg) center/cover no-repeat;
}

.recruit-img {
  background: url(../img/recruit.jpg) center/cover no-repeat;
}

.company-title {
  text-align: center;
  color: #fff;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.company-title span {
  color: #fff;
}


/*faq*/
.faq {
  width: 70%;
  background: #000;
  margin: 0 auto 10%;
  padding: 30px;
}

.faq-title,
.faq-title-jp {
  display: inline-block;
  color: #fff;
}

.faq-title {
  font-size: 40px;
  width: 10%;
}

.faq-title-jp {
  font-size: 20px;
  width: 80%;
  text-align: center;
}

/*contact*/

.contact {
  background: url(../img/contact-bg.jpg) center/cover no-repeat;
  padding: 10%;
}

.contact-title,
.contact-title span,
.contact-subtitle,
.contact-text {
  color: #fff;
  text-align: center;
}

.contact-title,
.contact-subtitle,
.contact-text {
  margin-bottom: 40px;
}

.contact-btn {
  margin: 0 auto;
  background: none;
  border: 1px solid #fff;
  color: #fff;
}


@media screen and (max-width: 768px) {
   .header-nav {
    display: none;
  }
  .catchcopy {
    top: 50%;
    left: 50%;
    width: 80%;
    text-align: center;
    transform: translate(-50%, -50%);
  }

  .news {
    width: 100%;
  }
  .mission-content {
    padding: 10% 0;
    margin: 0 auto;
  }
  .service-content_inner {
    width: 60%;
    left: 10%;
  }
  .service-img {
    width: 70%;
    margin-left: 30%;
    height:100px;
  }
  .service-img_second {
    margin: 0 30% 0 0;
  }
  .service-content_inner-second {
    left: 30%;
  }
  .service-content {
    margin: 0 auto;
  }
  .service-content_inner {
    width: 90%;
    position: inherit;
    background: rgba(255, 255, 255, 0.8);
    left: 5%;
  }
  .service-img {
    width: 90%;
    margin: 0 auto;
  }
  .recruit-company_size {
    width: 100%;
    height:350px;
  }
  .faq{
    width:85%;
    height:200px;
    margin: 0 auto 10%;
    padding: 30px;
  }
  
  .faq-title {
    font-size: 30px;
    background-size:cover;
  }
  .top-footer .header-logo {
    margin: 0;
    width: 100%;
    text-align: center;
  }
   #hamburger {
    width: 40px;
    height: 40px;
    position: absolute;
    cursor: pointer;
    z-index: 100;
    top: 15px;
    right: 20px;
    transition: 0.4s;
    display: block;
  }
  #hamburger span {
    display: block;
    width: 35px;
    height: 2px;
    background-color: #fff;
    transition: 0.8s;
  }
  #hamburger span:nth-of-type(1) {
    position: absolute;
    top: 10px;
    left: 2px;
  }
  #hamburger span:nth-of-type(2) {
    position: absolute;
    top: 20px;
    left: 2px;
  }
  #hamburger span:nth-of-type(3) {
    position: absolute;
    top: 30px;
    left: 2px;
  }
}


</style>
