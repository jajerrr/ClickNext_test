<template>
  <div class="zone zone1">
    <img src="../assets/bg_zone1.png" class="full-screen-img" alt="bgzone_1">
    <div class="content">
      <h1>INNOVATION<br>& SECURITY</h1>
      <div class="gradient-text">
        <h2>For</h2>
        <h3>Future Healthcare</h3>
      </div>
      <p class="locate-detail">
        <span class="day">24</span>
        <span class="month"> MAR 2023</span>
        <span class="vertical-line"></span>
        <span class="gradient-text adjusted">At Grand Ballroom 4th Floor</span>
        <br>
        <span class ="time">เวลา 13.00 - 19.00</span>
        <span class ="location-text">Pullman Bangkok Grande Sukhumvit</span>
      </p>
      <p class="detail-header">เหนือกว่า ด้วยโซลูชัน Healthcare แห่งอนาคต</p>
      <p class="detail">ทลายทุกความท้าท้าย เพิ่มศักยภาพการรักษาและการให้บริการด้านสาธารณสุขด้วย AI diagnosis, IoT, <br>
        Telemedicine, Self-service และ Medical Service Platform พร้อมการปกป้องข้อมูลส่วนบุคคล (PDPA) <br>
        และรับมือกับภัยคุกคามทางไซเบอร์ เพื่อความปลอดภัยขั้นสูงสุด</p>
      <img src="../assets/logo_clicknext.svg" class="logo_img" alt="">
      <img src="../assets/logo_kindee.svg" class="logo_img" alt="">
      <img src="../assets/logo_lenovo.svg" class="logo_img" alt="">
      <img src="../assets/logo_metro.svg" class="logo_img" alt="">
      <img src="../assets/logo_sangfor.svg" class="logo_img" alt="">
      <img src="../assets/logo_treg.svg" class="logo_img" alt="">
      <img src="../assets/logo_vrcomm.svg" class="logo_img" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Zone1'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@100..900&display=swap');
.zone1 {
  position: relative;
  width: 100vw;
  height: 100vh;
  background-color: transparent;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  margin: 0;
  padding: 0;
  font-family: 'Noto Sans Thai', sans-serif;
}

.full-screen-img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100vw;
  height: auto;
  object-fit: cover;
  z-index: -1;
  margin: 0;
  padding: 0;
}

.content {
  position: relative;
  top: 1px;
  left: -400px;
  color: white;
}

h1 {
  font-size: 130px;
  font-weight: 1000;
  margin-top: 65px;
  
  color: white;
}

h2 {
  font-size: 80px;
  margin-top: 10px;
}

h3 {
  font-size: 100px;
  font-weight: bold;
  margin-top: 10px;
}
 

.gradient-text {
  background: linear-gradient(to right, #14DB60, #AAFFCB);
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
  border-inline-color: transparent;
}

.gradient-text.adjusted {
  margin-left: 140px;
  font-size: 50px;
  font-weight: bold;
}

.locate-detail {
  margin-top: 60px; 
}

.day {
  font-size: 100px;
  font-weight: bold;

}

.month {
  font-size: 50px;
  font-weight: bold;
}

.time {
  font-size: 30px;
  color: #100751;
  background: white;
  font-weight: bold;
  padding: 10px 60px; 
  border-radius: 30px;
}

.vertical-line {
  position: relative;
}

.vertical-line::before {
  content: "";
  position: absolute;
  top: -30px;
  bottom: 0;
  width: 5px;
  height: 150px;
  background-color: #0CC553;
  margin-left: 70px;
  border-radius: 10px;
  transform: translateX(-50%); 
}

.location-text {
  font-size: 35px;
  margin-left: 150px;
}

.detail-header {
  font-size: 60px;
  margin-top: 150px;
  font-weight: bold;
}

.detail {
  font-size: 30px;
  color: #BAD0F2;

}

.logo_img {
  width: 250px;
  height: 60px;
  margin-top: 130px;
  
}

/************* Media Queries for different screen sizes ************/

@media (max-width: 1024px) {

  .zone1 {
  position: relative;
  width: 100vw;
  height: auto;
}
  .content {
    margin-left: 45%;
    margin-top: -4%;
    
  }

  h1 {
    font-size: 3.8vh;
  }

  h2 {
    font-size: 3.8vh;
  }

  h3 {
    font-size: 3.8vh;
  }

  .gradient-text.adjusted {
    margin-left:8vh;
    font-size: 2vh;
  }

  .day {
    font-size: 3vh;
  }

  .month {
    font-size: 2vh;
  }

  .time {
  font-size: 1.5vh;
  padding: 0.5vh 1vh; 
  border-radius: 5vw;
  margin:5vh 0;
}

  .vertical-line::before {
    width: 0.5vw;
    height: 8vh;
    margin-left: 4vw;
    top: -1vh;
    bottom: 0;
 
  }

  .locate-detail{
    margin-top: 2vh;
  }

  .location-text {
    margin-left:7.5vh;
    font-size: 2vh;
  }

  .detail-header {
    font-size: 2.5vh;
    margin-top: 5vh;
  }

  .detail {
    font-size: 1.5vh;
  }

  .logo_img {
    width: 7vh;
    margin-top:0%;
    margin: 0vw 0.5vh;
  }
}

@media (max-width: 768px) {
  .zone1 {
  position: relative;
  width: 100vw;
  height: auto;
  
}
  .content {
    margin-left: 57%;
    margin-top: -5%;
    
  }

  h1 {
    font-size: 3vh;
  }

  h2 {
    font-size: 3vh;
  }

  h3 {
    font-size: 3vh;
  }

  .gradient-text.adjusted {
    margin-left:5.5vh;
    font-size: 1.5vh;
  }

  .day {
    font-size: 2vh;
  }

  .month {
    font-size: 1.2vh;
  }

  .time {
  font-size: 1vh;
  padding: 0.2vh 1vh; 
  border-radius: 5vw;
  margin:5vh 0;
}

  .vertical-line::before {
    width: 0.5vw;
    height: 5.5vh;
    margin-left: 4vw;
    top: 0.4vh;
    bottom: 0;
 
  }

  .locate-detail{
    margin-top: 1vh;
  }

  .location-text {
    margin-left:4vh;
    font-size: 1.2vh;
  }

  .detail-header {
    font-size: 1.8vh;
    margin-top: 2vh;
  }

  .detail {
    font-size: 1.2vh;
    margin-top: -1vh;
  }

  .logo_img {
    width: 4vh;
    margin-top:0%;
    margin: 0vw 0.5vh;
  }
}

@media (max-width: 480px) {
  .content {
    left: 0;
    margin: 0 5vw;   
  }

  h1 {
    font-size: 3vw;
    margin-top: 3vh; 
  }

  h2 {
    font-size: 2.5vw;
    
  }

  h3 {
    font-size: 3vw;
   
  }

  .gradient-text.adjusted {
    font-size: 2vw;
    margin-left: 1.5vh; 
  }

  .day {
    font-size: 3vw;
    
  }

  .month {
    font-size: 2vw;
  }

  .time {
    font-size: 1vw;
    padding: 0.5vw 2vw;
    border-radius: 2vw;
    
    
    
  }

  .vertical-line::before {
    width: 0.5vw;
    height: 3.5vh;
    margin-left: 1.3vw;
    margin-top: 0.5vh;
  }

  .location-text {
    font-size: 2vw;
    margin-top: -5vh;
    margin-left: 2.5vh; 
  }

  .locate-detail{
    margin-top: -0.5vh;
    line-height: 1;
  }

  .detail-header {
    font-size: 3vw;
    margin-top: 1vh; 
  }

  .detail {
    font-size: 2vw;
    margin-top: -1vh; 
  }

  .logo_img {
    width: 5vw;
    margin-top: -2vh;
  }
}

@media (max-width: 360px) {

.content {
    left: 0;
    margin-left: -9vw;   
  }

  h1 {
    font-size: 2.8vw;
    margin-top: 2vh; 
  }

  h2 {
    font-size: 2.3vw;
    
  }

  h3 {
    font-size: 2.8vw;
   
  }

  .gradient-text.adjusted {
    font-size: 2vw;
    margin-left: 1.5vh; 
  }

  .day {
    font-size: 2vw;
    
  }

  .month {
    font-size: 1.8vw;
  }

  .time {
    font-size: 1vw;
    padding: 0.3vw 1vw;
    border-radius: 2vw;
    
    
    
  }

  .vertical-line::before {
    width: 0.5vw;
    height: 2.5vh;
    margin-left: 1.3vw;
    margin-top: 0.5vh;
  }

  .location-text {
    font-size: 1.8vw;
    margin-left: 2vh; 
  }

  .locate-detail{
    line-height: 0.5;
  }

  .detail-header {
    font-size: 2.8vw;
    margin-top: 1vh; 
  }

  .detail {
    font-size: 1.8vw;
    margin-top: -1vh; 
  }

  .logo_img {
    width: 5vw;
    margin: -4vh 1vw;
    
  }
}


</style>
