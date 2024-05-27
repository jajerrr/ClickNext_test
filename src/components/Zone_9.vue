<template>
  <div class="zone zone9">
      <div class="content">
          <p>
              <span class="detail">ติดต่อสอบถามรายละเอียดเพิ่มเติม</span>
              <img src="../assets/ic_phone.svg" class="icon" alt="">
              <span class="contact">คุณนันทพร ทองเพชร</span>
              <span class="contact">084-118-4868</span>
          </p>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Zone9'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@100..900&display=swap');

.zone9 {
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
  background: white;
}

.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: white;
  z-index: 1;
  text-align: center;
  margin-top: 50px;
}

.contact {
  font-size: 40px;
  font-weight: bold;
  color: #3138A0;
  margin-left: 30px;
}

.detail {
  font-size: 40px;
  font-weight: normal;
  color: #6E7788;
}

.icon {
  width: 80px;
  height: auto;
  margin-left: 50px;
  margin-bottom: 20px;
}

@media (max-width: 1024px) {
  .zone9{
    width:auto;
    height: auto;
  }
  .contact, .detail {
      font-size: 20px;
      margin-left: 10px;
  }
  .icon {
      width: 40px;
      margin-left: 15px;
  }
}

@media (max-width: 768px) {
  .zone9{
    width:auto;
   height: 10vh;
  }
  .contact, .detail {
      font-size: 20px;
      margin-left: 10px;
  }
  .icon {
      width: 40px;
      margin-left: 15px;
  }
}

@media (max-width: 480px) {
  .zone9{
    width:auto;
    height: 10vh;
  }
  .contact, .detail {
      font-size: 15px;
      margin-left: 15px;
  }
  .icon {
      width: 20px;
      margin-left: 15px;
  }
}

@media (max-width: 380px) {
  .zone9{
    width:auto;
   height: 10vh;
  }
  .contact, .detail {
      font-size: 15px;
      margin-left: 10px;
  }
  .icon {
      width: 20px;
      margin-left: 15px;
  }
}
</style>
