<template>
  <div id="app">
    <homeHeader></homeHeader>
    <main>
        <div class="background">
            <div class="main-title">
                <h3>機械ではできない仕事を</h3>
            </div>
            <div class="news">
                <div class="time">
                    <p>2019/01/01</p>
                </div>
                <div class="ex">
                    <p>ニュースタイトルがここには入ります。3月の決定報告書</p>
                </div>
                <div class="news-logo">
                    <p>news</p>
                </div>
            </div>
        </div>

        <div class="content">
            <img class="content-img" src="./assets/photo/img/mission-img.jpg" alt="">
            <div class="content-text">
                <h3 class="content-title">お客様のために進化する成長企業であり続ける</h3>
                <p class="content-ex">顧客主導型サービスを提供する企業として、お客様の会社経営に必要なサービスと情報を提供し続ける企業支援会社を目指します。企業が現在直面している「勝ち残るため」の戦略を提供できる会社として、ホームページをはじめ、各種マーケティングをご提供いたします。</p>
                <button class="btn mission" type="submit" >ミッション詳細</button>
            </div>
        </div>

        <div class="service">
            <h3 class="service-title">servise</h3>
            <img class="service-img1" src="./assets/photo/img/service2.jpg" alt="">
            <img class="service-img2" src="./assets/photo/img/service1.jpg" alt="">

            <div class="service-text">
                <h3>web制作事業</h3>
                <p>コーチングのミッション</p>
                <p>ユーザーが求めるものを分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります。</p>
                <button class="btn service1">サービス詳細</button>
            </div>

            <div class="service-sub">
                <h3>web制作事業</h3>
                <p>コーチングのミッション</p>
                <p>ユーザーが求めるものを分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります。</p>
                <button class="btn sub">サービス詳細</button>
            </div>
        </div>

        <div class="overview">
            <div class="view">
                <div class="view-left">
                    <div class="company-ex">
                        <button class="btn company1">
                            <h3>company</h3>
                            <p>会社概要</p>
                        </button>
                    </div>
                </div>
    
                <div class="view-right">
                    <div class="recruit-ex">
                        <button class="btn recruit1">
                            <h3>recruit</h3>
                            <p>採用情報</p>
                        </button>
                    </div>
                </div>
            </div>
            

            <div class="question">
                <button class="btn question1">よくある質問
                    <h3>FAQ</h3>
                </button>
            </div>
        </div>

        <div class="contact">
            <img src="./assets/photo/img/contact-bg.jpg" alt="">
            <div class="contact-con">
                <div class="contact-title">  
                    <h2>contact</h2>
                    <p>お問い合わせ</p>
                </div>
                <div class="contact-ex">
                    <h2>お気軽にお問い合わせください。</h2>
                    <p>資料請求・お問い合わせなどなんでも気軽にお問い合わせください。お仕事のご連絡もお問い合わせページに飛んでいただいて、入力フォームにご記入お願いいたします。</p>
                </div>
                <button class="btn contact-btn">お問い合わせ</button>
            </div>
        </div>
    </main>
    <homeFooter></homeFooter>
  </div>
</template>

<script>
import homeHeader from './components/homeHeader.vue'
import homeFooter from './components/homeFooter.vue'

export default {
  components:{
    homeHeader,
    homeFooter
  }
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

.background{
    background-image: url(assets/photo/img/eyecatch.jpg);
    height: 600px;
    background-size: cover;
    position: relative;
}
.main-title h3{
    position: absolute;
    top: 70%;
    left: 15%;
    color: white;
    font-size: 40px;
    letter-spacing: 0.1em;
    transition-duration: 1s;
    transform: skew(-15deg);
}
.news{
    width: 100%;
    font-size: 11px;
    position: absolute;
    bottom: 0;
    right: 0;
    color:rgb(0, 0, 0);
    background-color: rgb(255, 255, 255);
    display: grid;
}

.time {
    grid-area: 1/1/2/2;
    width: 410px;
}

.ex{
    grid-area: 2/1/2/2;
    padding: 0 20px;
    float: left;

}
.news-logo{
    grid-area: 1/2/3/3;
    padding: 0 20px;
    color: white;
    background-color: #000;
}
.news-logo p{
    line-height: 44px;
}

.content{
    height: 400px;
    background-color: black;
    position: relative;
}
.content-text {
    position: absolute;
    top: 40%;
    left: 22%;
    color: white;
}
.content-img{
    height: 320px;
    width: 480px;
    position: absolute;
    bottom: -8%;
    right: 5%;   
}
.content-title{
    font-size: 18px;
    padding-bottom: 20px;
    letter-spacing: 0.1em;
    
}
.content-ex{
    width: 60%;
    font-size: 11px;
    line-height: 1.7em;
    letter-spacing: 0.1em;
    padding-bottom: 20px;
}
.btn{
    padding: 5px 20px;
    font-size: 10px;
    background-color: white;
    cursor: pointer;
    transition: 0.4s;
}
.btn:hover{
    color: white;
    background-color: rgb(128, 128, 128);
}

.service{
    height: 1200px;
    margin: 100px 0;
    background-color: #cccccc;
    position: relative;
}
.service-title{
    font-size: 25px;
    padding: 10px ;
    text-align: center;
}
.service-img1{
    height: 420px;
    width: 630px;
    float: right;
}
.service-img2{
    height: 360px;
    width: 630px;
    position: absolute;
    top:55%;
}
.service-text{
    background-color: white;
    position: absolute;
    top: 12%;
    left: 20%;
    width: 400px;
    padding: 50px;
}
.service-text p,h3{
    font-size: 12px;
    padding-bottom: 20px;
}
.service1{
    float: right;
}
.service1:hover{
    border: #000 solid 2px;
}

.service-sub{
    background-color: white;
    position: absolute;
    top: 60%;
    left: 40%;
    width: 400px;
    padding: 50px;
}
.service-sub p,h3{
    font-size: 12px;
    padding-bottom: 20px;
}
.sub{
    float: right;
}
.sub:hover{
    border: #000 solid 2px;
}

.overview{
    margin-bottom: 100px;
}
.view{
    display: flex;
    justify-content: space-between;
    position: relative;
}
.company1{
    background-image: url(assets/photo/img/company.jpeg);
    height: 250px;
    width: 550px;
    background-size: cover;
}
.company-ex{
    color: white;
    
}
.recruit1{
    background-image: url(assets/photo/img/recruit.jpg);
    height: 250px;
    width: 550px;
    background-size: cover;
}
.overview h3{
    font-size: 25px;
}
.overview p{
    font-size: 11px;
}
.question{
    margin: 100px auto;
    text-align: center;
}
.question1{
    line-height: 100px;
    color: white;
    background-color: #000;
    height: 100px;
    width: 900px;
    position: relative;

}
.question h3{
    position: absolute;
    top: 0;
    color: white;
}
.contact{
    position: relative;

}

.contact img{
    height: 600px;
    width: 100%;
    background-size: cover;
    vertical-align: bottom;
}
.contact-con{
    color: white;
    text-align: center;
    position: absolute;
    top: 30%;
    left: 15%;
}
.contact-title h2{
    font-size: 25px;
}
.contact-title p{
    font-size: 11px;
    padding-top: 5px;
}
.contact-ex h2{
    font-size: 25px;
    font-weight: lighter;
    padding: 20px 0;    
}
.contact-ex p{
    font-size: 11px;
}
.contact-btn{
    padding: 5px 20px;
    color: white;
    margin: 20px;
    background-color: rgba(0,0,0,0);
}

@media screen and (max-width:768px){
    .main-title h3{
        text-align: center;
        position: absolute;
        left: 0;
    }

    .news-logo{
        text-align: center;
    }
    .news{
        width: 100%;
    }
    .time{
        width: 100px;
    }
    .ex{
        width: 100px;
    }

    .content-text{
        position: absolute;
        top: 10%;
        left: 27%;
    }
    .content-img{
        width: 150px;
        height: 90px;
    }
    
    .service{
        height: 1000px;
    }
    .service-img1{
        width: 90%;
        height: 200px;

        margin: 0 5%;
    }
    .service-text{
        position: absolute;
        top: 245px;
        left: 5%;
        padding: 5%;
        width: 80%;
    }
    
    .service-img2{
        width: 90%;
        height: 200px;
        margin: 0 5%;
    }
    
    .service-sub{
        position: absolute;
        top: 745px;
        left: 5%;
        padding: 5%;
        width: 80%;
    }
    .view{
        display: flex;
        flex-flow: column;
    }
    .company1{
        width: 100%;
        height: 50vh;
    }
    .recruit1{
        width: 100%;
        height: 50vh;
    }
    .question1{
        width: 100%;
    }
    .contact-con{
        position: absolute;
        left: 5%;
        right: 5%;
    }
}
</style>
