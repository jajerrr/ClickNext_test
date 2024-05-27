<template>
    <div class="zone zone8">
      <div class="content">
        <p>
          <span class="head-detail">สำรองที่นั่งล่วงหน้า</span>
          <span class="detail"> (จำนวนจำกัด*)</span>
        </p>
        <p>หมายเหตุ : สัมมนา Exclusive สำหรับกลุ่มโรงพยาบาล และสาธารณะสุข</p>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSdf-Px9QA76gCH1byd_sV1aTEsOJkd_bGDPHt8_tqhDKBhGMw/viewform?usp=send_form" class="btn btn-primary btn-lg custom-btn" target="_blank">ลงทะเบียน</a>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Zone8'
  }
  </script>
  
  <style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@100..900&display=swap');
  
  .zone8 {
    position: relative;
    width: 100vw;
    height: auto; /* ตั้งค่าความสูงให้เต็มจอ */
    background-color: transparent;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
    margin: 0;
    padding: 0;
    font-family: 'Noto Sans Thai', sans-serif;
    background: linear-gradient(360deg,  #dff4ff 0.8%, rgba(255, 255, 255, 0.96) 32.31%, rgba(255, 255, 255, 0) 83.81%);
    
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
    margin: 30px auto;
    text-align: center;
  }
  
  .head-detail {
    font-size: 45px;
    font-weight: bold;
    color: #0C2292;
;
  }
  
  .detail {
    font-size: 45px;
    font-weight: normal;
    color: #6E7788;
  }
  
  p {
    margin: 0;
    font-size: 35px;
    font-weight: normal;
    color: #262E3F;
  }
  
  .custom-btn {
    background: linear-gradient(115.71deg, #0BB64C 2.75%, #27D96B 79.77%);
    border: none;
    color: white;
    font-size: 50px;
    font-weight: bold;
    padding: 30px 400px;
    border-radius: 20px;
    transition: background 0.3s;
    margin-top: 40px;
    text-decoration: none;
    display: inline-block;
  }
  
  
  
  
  @media (max-width: 1024px) {
    .head-detail, .detail {
        font-size: 35px;
    }
    p {
        font-size:25px;
    }
    .custom-btn {
        font-size: 25px;
        padding: 1vh 15vw;
    }
}

@media (max-width: 768px) {
  .head-detail, .detail {
        font-size: 30px;
    }
    p {
        font-size:20px;
    }
    .custom-btn {
        font-size: 20px;
        padding: 1vh 15vw;
    }
}

@media (max-width: 480px) {
  .head-detail, .detail {
        font-size: 25px;
    }
    p {
        font-size:15px;
    }
    .custom-btn {
        font-size: 15px;
        padding: 1vh 15vw;
    }
}

@media (max-width: 380px) {
  .head-detail, .detail {
        font-size: 20px;
    }
    p {
        font-size:15px;
    }
    .custom-btn {
        font-size: 10px;
        padding: 1vh 15vw;
    }
}
</style>
  