<template>
  <header>
    <nav class="navbar">
      <div class="links"> 
        <a  href="#">Главная</a>
        <a  href="#">Наши Проекты</a>
        <a  href="#">Услуги</a>
        <a  href="#">Новости</a>
        <a  href="#">Контакты</a>
      </div>
    </nav>
    <div class="info">
      <p class="pinfo">Передовая IT студия</p>
      <h4 class="hinfo">
        <pre>Мы создаем легкие решения 
сложных задач и проблем</pre
        >
      </h4>
    </div>
    <div class="btn">
      <button type="button" class="btn btn-primary btn-lg">Наши проекты</button>
    </div>
  </header>
  <body>
    <div class="body">
      <div class="info2">
        <h4 class="hinfo2">
          Мы создаем мобильные приложения для крупных корпораций
        </h4>
        <p class="pinfo2">
          Lorem Ipsum - это текст-"рыба", часто используемый в печати и
          вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для текстов на
          латинице с начала XVI века.
        </p>
        <div class="site">
           <div class="h1">
            <h1>Создание сайтов</h1>
            <p class="p">Lorem Ipsum - это текст- "рыба", часто используе в печати и вэб-дизайне.</p>
           </div>
           <div class="h1">
            <h1>Создание сайтов</h1>
            <p class="p">Lorem Ipsum - это текст- "рыба", часто используе в печати и вэб-дизайне.</p>
           </div>
           <div class="h1">
            <h1>Создание сайтов</h1>
            <p class="p">Lorem Ipsum - это текст- "рыба", часто используе в печати и вэб-дизайне.</p>
           </div>
          </div>
           <div class="btnbt">
            <button type="button" class="btn btn-primary btn-lg">Все услуги</button>
            </div>
        </div>
      </div>
      <div class="standart">
        <div class="infocompany">
          <div class="infotxt">
            <h1 class="cm">Высокие стандарты разработки</h1>
            <p class="cm2">Lorem Ipsum - это текст-"рыба", часто используемый в печати и вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для текстов на латинице с начала XVI века.  стандартной "рыбой" для текстов на латинице с начала XVI века. </p>
            <a href="#">Подробнее о компании</a>
          </div>
          <div class="img">
            <img src="./assets/computer.png" alt="">
          </div>
        </div>
        <hr width="100%"/>
        <div class="project">
          <div class="vector">
            <img src="./assets/web-programming.png" alt="">
            <h2>125</h2>
            <img src="./assets/web-programming.png" alt="">
            <h2>125</h2>
            <img src="./assets/web-programming.png" alt="">
            <h2>125</h2>
            <img src="./assets/web-programming.png" alt="">
            <h2>125</h2>
            <img src="./assets/web-programming.png" alt="">
            <h2>125</h2>
          </div>
          <div class="p-bt">
            <p>Our projects</p>
            <p>Our projects</p>
            <p>Our projects</p>
            <p>Our projects</p>
            <p>Our projects</p>
          </div>
        </div>
      </div>
      
  </body>
</template>

<script>
export default {
  name: "App",
};
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.p-bt{
  display: flex;
}

.p-bt p{
  margin-right: 20px;
  margin-left: 20px;
}

.vector{
  display: flex;
  align-items: center;
}

.vector h2{
  font-family: 'Montserrat';
  font-weight: 400;
  font-size: 36px;
  line-height: 52.66px;
}

.vector img{
  margin-right: 20px;
  margin-left: 20px;
  width:30px;
  height: 26.47px;
}

.infotxt{
  margin-right: 121px;
}


.img{
  width: 100%;
  margin-top: 100px;
}

.standart{
  background-color: #F6F6F8;
  width: 1920px;
  height: 797px;
  display: flex;
  flex-direction: column;
}

.infocompany{
  display: flex;
  flex-direction: row;
  margin-left: 405px;
  margin-right: 121px;
}


.cm{
  margin-top: 152px;
  font-family: 'Montserrat';
  font-weight: 700;
  font-size: 36px;
  line-height: 52.66px;
}

.cm2{
  width: 489px;
  height: 117px;
  font-family: 'Montserrat';
  font-weight: 400;
  font-size: 16px;
  line-height: 25.36px;
  color: #999999;
}



.section{
  margin-top: 109px;
  
}

.btnbt{
  margin-top: 68px;
  align-items: center;
}

.site{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.h1{
  font-family: 'Montserrat';
  font-weight: 600;
  font-size: 18px;
  line-height: 21.94px;
  margin-left: 17px;
}
.p{
  font-family: 'Montserrat';
  font-weight: 400;
  font-size: 14px;
  line-height: 22.19px;
  color: #999999;
}

.site{
  margin-top: 70px;
}


header {
  
  background: linear-gradient(0deg, rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2));
  background-image: url("./assets//back.png");
  width: 1920px;
  height: 900px;
  
}

.links {
  margin-left: 952px;
  display: flex;
}

.links a{
  padding-bottom: 39px;
  margin: 40px;
  color: #ffffff;
  font-size: 16px;
  font-weight: 500;
  font-family: "Montserrat";
  text-decoration: none;
  line-height: 19.5px;
  
  
  
}

.links a:hover{
  border-bottom: 3px solid #ffffff;
}
.info {
  margin-top: 219px;
  text-align: center;
}

.pinfo {
  font-family: "Montserrat";
  color: #ffffff;
  font-weight: 500;
  font-size: 16px;
  line-height: 19.5px;
  margin-bottom: 20px;
}

.hinfo {
  color: #ffffff;
  font-family: "Montserrat";
  font-weight: 800;
  font-size: 48px;
  line-height: 64.36px;
}
.btn {
  margin-top: 50px;
  text-align: center;
}
body{
  width: 1920px;
  height: 900px;
}
.info2{
  margin-top: 110px;
 
}
.hinfo2{
  font-family: 'Montserrat';
  font-weight: 700;
  font-size: 36px;
  line-height: 52.66px;
  text-align: center;
}

.pinfo2{
  font-family: 'Montserrat';
  font-weight: 400;
  font-size: 16px;
  line-height: 25.36px;
  text-align: center;
  margin-top: 50px;
  color: #999999;
}
</style>
