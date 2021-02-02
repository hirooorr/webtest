<template>
  <footer>
        <div class="footer-main">
            <h3 class="footer-title">estra inc.</h3>
            <div class="footer-lists">
                <a class="footer-list" href="#">home</a>
                <a class="footer-list" href="#">about</a>
                <a class="footer-list" href="#">service</a>
                <a class="footer-list" href="#">works</a>
                <a class="footer-list" href="#">price</a>
                <a class="footer-list" href="#">contact</a>                
            </div>
        </div>
        <p class="last">Copyright 2019 estra inc.All Rights Reserved.</p>
    </footer>
</template>

<script>
export default {

}
</script>

<style scoped>
.footer-main {
    color:white;
    background: black;
    height: 50px;
    width: 100%;
}

.footer-main a{
    padding-left: 20px;
    font-size: 14px;
    text-decoration: none;
}

.footer-title{
    float: left;
    padding: 15px 30px;
}

.footer-lists{
    float: right;
    padding: 15px 30px;
}

.footer-list{
    color: white;
}
.last{
    font-size: 11px;
    text-align: center;
    color: white;
    padding-bottom: 10px;
    width: 100%;
    background-color: black;
}

@media screen and (max-width:768px){
    .footer-lists{
        display: none;
    }
}
</style>