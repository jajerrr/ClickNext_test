<template>
  <div class="zone zone2">
    <div class="content">
      <p>
        <span class="head-detail">สำรองที่นั่งล่วงหน้า</span>
        <span class="detail"> (จำนวนจำกัด*)</span>
      </p>
      <p class="detail">หมายเหตุ : สัมมนา Exclusive สำหรับกลุ่มโรงพยาบาล และสาธารณะสุข</p>
      <a href="https://docs.google.com/forms/d/e/1FAIpQLSdf-Px9QA76gCH1byd_sV1aTEsOJkd_bGDPHt8_tqhDKBhGMw/viewform?usp=send_form" class="btn btn-primary btn-lg custom-btn" target="_blank">ลงทะเบียน</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Zone2'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@100..900&display=swap');

.zone2 {
  position: relative;
  width: 100vw;
  height: auto;
  background-color: transparent;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  margin: 0;
  padding: 0;
  font-family: 'Noto Sans Thai', sans-serif;
  background: linear-gradient(180deg, #0B0F17, #0E044B),#2C309B;
}

.full-screen-img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  z-index: -1;
  margin: 0;
  padding: 0;
  
}

.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: white;
  z-index: 1;
  text-align: center;
  margin:40px auto;
}

.head-detail {
  font-size: 60px;
  font-weight: bold;
  color: white;
}

.detail {
  font-size: 40px;
  font-weight: normal;
  color: #BAD0F2;
}

p {
  margin: 0;
}

.custom-btn {
  background: linear-gradient(115.71deg, #0BB64C 2.75%, #27D96B 79.77%);
  border: none;
  color: white;
  font-weight: bold;
  padding: 30px 200px;
  border-radius: 20px;
  transition: background 0.3s;
  margin-top: 60px;
  text-decoration: none;
  display: inline-block;
  font-size: 40px;
}


/* Media Queries for different screen sizes */

@media (max-width: 1024px) {

  .zone2{
    width: 100vw;
    height: auto;

  }
  .head-detail {
    font-size: 3vh;
  }

  .detail {
    font-size: 2.5vh;
  }

  .custom-btn {
    padding: 10px 8vw;
    font-size: 2.5vh;
    margin-top: 20px;
    border-radius: 5px;
  }
}

@media (max-width: 768px) {

  .zone2{
    width: 100vw;
    height: auto;

  }
.head-detail {
  font-size: 2.5vh;
}

.detail {
  font-size: 2vh;
}


.custom-btn {
  padding: 10px 50px;
  border-radius: 5px;
  margin-top: 20px;
  font-size: 2vh;
}

}

@media (max-width: 480px) {

  .zone2{
    width: 100vw;
    height: auto;

  }
  .head-detail {
    font-size: 2vh;
  }

  .detail {
    font-size: 1.5vh;
  }

  .custom-btn {
    padding: 10px 40px;
    border-radius: 5px;
    margin-top: 15px;
    font-size: 1.5vh;
  }
}

@media (max-width: 360px) {
  .head-detail {
    font-size: 1.5vh;
  }

  .detail {
    font-size: 1vh;
  }

  .custom-btn {
    padding: 8px 30px;
    border-radius: 5px;
    margin-top: 10px;
    font-size: 1vh;
  }
}

@media (max-width: 320px) {
  .head-detail {
    font-size: 1.5vh;
  }

  .detail {
    font-size: 1vh;
  }

  .custom-btn {
    padding: 6px 20px;
    border-radius: 5px;
    margin-top: 10px;
    font-size: 1vh;
  }
}


</style>
