<template>
    <div class="zone zone4">
      <img src="../assets/bg_zone-4.svg" class="full-screen-img" alt="bgzone_1">
      <div class="content">
        <div class="header">
          <span class="vertical-line"></span>
          <span class="gradient-text">Main Speaker</span>
        </div>
        <div class="speaker-container">
          <div class="speaker-item">
            <img src="../assets/Main Speaker-1.svg" class="speaker_img" alt="">
            <p class="speaker-detail">รศ. วิรุฬห์ ศรีบริรักษ์</p>
            <p class="speaker-his">คณะวิศวกรรมศาสตร์ มหาวิทยาลัยบูรพา</p>
            <p class="speaker-com">ผู้ก่อตั้ง Bangsaen Design House Group<br>และ กิน-อยู่-ดี แพลตฟอร์ม</p>
          </div>
          <div class="speaker-item">
            <img src="../assets/Main Speaker-2.svg" class="speaker_img" alt="">
            <p class="speaker-detail">ผศ.ดร. กฤษณะ ชินสาร</p>
            <p class="speaker-his">คณบดีคณะวิทยาการสารสนเทศมหาวิทยาลัยบูรพา</p>
            <p class="speaker-com"></p>
            
          </div>
          <div class="speaker-item">
            <img src="../assets/Main Speaker-3.svg" class="speaker_img" alt="">
            <p class="speaker-detail">คุณวิญญู อดิศักดิ์ตระกูล</p>
            <p class="speaker-his">Solution Consultant Manager</p>
            <p class="speaker-com">บริษัท ซังฟอร์ เทคโนโลยี (ประเทศไทย) จำกัด</p>
          </div>
        </div>

        <div class="speaker-container">
          <div class="speaker-item">
            <img src="../assets/Main Speaker-4.svg" class="speaker_img" alt="">
            <p class="speaker-detail">คุณสรรชัย ลีฬหาเกียรติ</p>
            <p class="speaker-his">Senior Technical Management</p>
            <p class="speaker-com">บริษัท เลอโนโว (ประเทศไทย)</p>
          </div>
          <div class="speaker-item">
            <img src="../assets/Main Speaker-5.svg" class="speaker_img" alt="">
            <p class="speaker-detail">คุณวันพิชิต ชินตระกูลชัย</p>
            <p class="speaker-his">Chief Technology Officer</p>
            <p class="speaker-com">บริษัท แร็กน่าร์ คอร์ปอเรชั่น จำกัด และ<br>ผู้ก่อตั้ง t-reg PDPA Platform</p>
            
          </div>
          <div class="speaker-item">
            <img src="../assets/Main Speaker-6.svg" class="speaker_img" alt="">
            <p class="speaker-detail">คุณพิเชษฐ์ พิทักษ์วศิน</p>
            <p class="speaker-his">Chief Technology Officer</p>
            <p class="speaker-com">บริษัท คลิกเน็กซ์ จำกัด</p>
          </div>
        </div>
      </div>
    </div>
  </template>

<script>
export default {
    name: 'Zone4'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@100..900&display=swap');

.zone4 {
    position: relative;
    width: 100vw;
    height: auto;
    background-color: transparent;
    display: flex;
    align-items: flex-start; 
    overflow: hidden;
    margin: 0;
    padding: 0;
    font-family: 'Noto Sans Thai', sans-serif;
}

.content {
    margin-top: 10px;
    color: white;
}

.full-screen-img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    object-fit: cover;
    z-index: -1;
    margin: 0;
    padding: 0;
}

.header-text {
    font-size: 80px;
    font-weight: bold;
}

.vertical-line {
    position: relative;
}

.vertical-line::before {
  content: "";
  position: absolute;
  top: -65px;
  bottom: 0;
  width: 20px;
  height: 120px;
  background-color: #25DF6C;
  margin-left: 70px;
  border-radius: 10px;
  transform: translateX(-50%);
}

.gradient-text {
  background: linear-gradient(to right, #0E044B, #2C309B,#89E8FD);
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
  border-inline-color: transparent;
  font-size: 70px;
  font-weight: bold;
  margin-left: 120px;
  
}

.header {
    margin-top: 100px;
}

.speaker-container {
    display: flex;
    justify-content: space-around;
    align-items: flex-start;
    margin-top: 50px; 
    margin-left: 250px;
}

.speaker-item {
    text-align: center;
    width: 700px;
}

.speaker_img {
    width: 100%;
    height: 300px;
    display: block;
    margin: 0 auto;
}

.speaker-detail {
    color: #1F2883;
    font-size: 45px;
    font-weight: bold;
    margin-top: 10px;
}

.speaker-his {
    color: #359EFF;
    font-size: 30px;
    font-weight: 500;
}

.speaker-com {
    color: #262E3F;
    font-size: 30px;
    font-weight: 400;
}

/* สำหรับหน้าจอขนาดกลาง */
@media (max-width: 1024px) {
  .header-text {
    font-size: 50px;
  }

  .vertical-line::before {
    top: -45px;
    width: 15px;
    height: 90px;
    margin-left: 50px;
  }

  .gradient-text {
    font-size: 50px;
    margin-left: 80px;
  }

  .speaker-container {
    flex-direction: column;
    align-items: center;
    margin-left: 0;
  }

  .speaker-item {
    width: 80%;
    margin-bottom: 20px;
  }

  .speaker_img {
    height: 200px;
  }

  .speaker-detail {
    font-size: 30px;
  }

  .speaker-his,
  .speaker-com {
    font-size: 20px;
  }
}

/* สำหรับหน้าจอขนาดเล็ก */
@media (max-width: 768px) {
  .content{
    margin-top:-5vh;
  }
  .header-text {
    font-size: 40px;
  }

  .vertical-line::before {
    top: -2vh;
    width: 10px;
    height: 50px;
    margin-left: 40px;
  }

  .gradient-text {
    font-size: 30px;
    margin-left: 60px;
  }

  .speaker-container {
    flex-direction: column;
    align-items: center;
    margin-left: 0;
  }

  .speaker-item {
    width: 100%;
    margin-bottom: 15px;
  }

  .speaker_img {
    height: 150px;
  }

  .speaker-detail {
    font-size: 25px;
  }

  .speaker-his,
  .speaker-com {
    font-size: 18px;
  }
}

/* สำหรับหน้าจอขนาดเล็กมาก */
@media (max-width: 480px) {

  .content{
    margin-top:-8vh;
  }
  .header-text {
    font-size: 30px;
  }

  .vertical-line::before {
    top: -1vh;
    width: 8px;
    height: 40px;
    margin-left: 30px;
  }

  .gradient-text {
    font-size: 20px;
    margin-left: 40px;
  }

  .speaker-container {
    flex-direction: column;
    align-items: center;
    margin-left: 0;
  }

  .speaker-item {
    width: 100%;
    margin-bottom: 10px;
  }

  .speaker_img {
    height: 100px;
  }

  .speaker-detail {
    font-size: 20px;
  }

  .speaker-his,
  .speaker-com {
    font-size: 15px;
  }
}


</style>
