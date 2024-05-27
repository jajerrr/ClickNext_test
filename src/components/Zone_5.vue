<template>
    <div class="zone zone5">
      <div class="content">
        <div class="header">
          <span class="vertical-line"></span>
          <span class="gradient-text">Schedule</span>
        </div>
        <p class="white-line" />
        <div class="detail_1">
          <span class="time">ช่วงที่ 1  13:00 - 15:30 น.</span>
        </div>
        <ul class="custom-list">
          <li>PDPA ในโรงพยาบาล ความท้าทายใหม่หลังการบังคับใช้ พ.ร.บ.คุ้มครองข้อมูลส่วนบุคคล</li>
          <li>Improving Cyber resilience with AI & Automation</li>
          <li>Lenovo Intelligent Infrastructure to enable Smart Healthcare</li>
        </ul>
        <p class="white-line" />
        <div class="detail_1">
          <span class="time">ช่วงที่ 2  15:35 - 17:05 น.</span>
        </div>
        <ul class="custom-list">
          <li>Enhance customer experience for Healthcare with digital technologies</li>
          <li>Holistic IoT & AI for Healthcare, Telemedicine and Medical Service Platform</li>
          <li>Empowering Health Tech solution with AI diagnosis</li>
        </ul>
        <p class="white-line" />
        <div class="detail_1">
          <span class="time">17:05 - 19:00 น.</span>
          <span class="text">ร่วมรับประทานอาหาร (International Dinner Buffet)</span>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Zone5'
  }
  </script>
  
  <style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@100..900&display=swap');
  
  .zone5 {
    position: relative;
    width: 100vw;
    height: auto; /* ตั้งค่าความสูงให้เต็มจอ */
    background-color: transparent;
    display: flex;
    align-items: flex-start; 
    overflow: hidden;
    margin: 0;
    padding: 0;
    font-family: 'Noto Sans Thai', sans-serif;
    
    
  }
  
  .content {
    color: #2f3d5c;
    border-radius: 40px;
    padding: 20px;
    background-color: #EEF6FF;
    width: 80vw;
    height: 80vh;
    margin: 30px auto;
  
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  
  .header {
    margin-bottom: 50px;
    margin-left: 10px;
    position: relative;
  }
  
  .gradient-text {
    background: linear-gradient(to right, #0E044B, #2C309B,#89E8FD);
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    border-inline-color: transparent;
    font-size: 60px;
    font-weight: bold;
    margin-left: 120px;
  }
  
  .vertical-line {
    position: relative;
  }
  
  .vertical-line::before {
    content: "";
    position: absolute;
    top: -50px;
    bottom: 0;
    width: 20px;
    height: 100px;
    background-color: #25DF6C;
    margin-left: 70px;
    border-radius: 10px;
    transform: translateX(-50%);
  }
  
  .white-line {
    position: relative;
    bottom: -10px; 
    left: 0;
    width: 200%;
    height: 10px;
    background-color: white;
    border: none;
    margin-left: -50px;
  }
  
  .time {
    font-size: 35px;
    color: white;
    background: #0CC553;
    font-weight: bold;
    padding: 10px 60px;
    border-radius: 40px;
  }
  
  .text {
    font-size: 35px;
    color: #2f3d5c;
    margin-left: 50px;
  }
  
  .detail_1 {
    margin-top:60px;
    margin-left: 60px;
  }
  
  .custom-list {
    list-style: none;
    padding: 0;
    text-align: left;
    font-size: 35px;
    color: #2f3d5c;
  }
  
  .custom-list li {
    position: relative;
    padding-left: 50px;
    margin: 30px 80px;
  }
  
  .custom-list li::before {
    content: '';
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateY(-50%) rotate(45deg);
    width: 20px;
    height: 20px;
    background-color: #25DF6C;
    border-radius: 2px;
  }


  @media (max-width: 1024px) {
    .content {
    width: 90vw; /* ปรับขนาด width เมื่อหน้าจอเล็กกว่าหรือเท่ากับ 768px */
    height: auto; /* กำหนด height เป็น auto เพื่อให้ความสูงของ content ขยายตามเนื้อหา */
    margin: 10px auto; /* ปรับ margin เพื่อให้ content อยู่กึ่งกลาง */
    padding: 10px; /* ปรับ padding เมื่อหน้าจอเล็กกว่าหรือเท่ากับ 768px */
  }
  .custom-list {
    font-size: 16px;
    margin-left: 32px;
  }
  
  .custom-list li {
    padding-left: 32px;
    margin: 16px 0;
    
  }
  
  .custom-list li::before {
    width: 12px;
    height: 12px;
  }


  .time {
    font-size: 16px;
    padding: 10px 30px;
    border-radius: 40px;
  }
  .detail_1{
    margin-top:15px;
    margin-left: 30px;
    margin-bottom: 10px;
  
  }

  .text{
    font-size:16px ;
    margin-left: 10px;
    
  }

  .header {
    margin-bottom: 10px;
    margin-left: 5px;
    margin-top:10px;
    
  }
  
  .vertical-line::before {
    top: -10px;
    width: 10px;
    height: 40px;
    margin-left: 15px;
    border-radius: 10px;
    
  }

  .gradient-text {
    padding-top: 5px;
    font-size: 30px;
    margin-left: 30px;
    
  }

  .white-line {
    bottom: -10px; 
    width: 200%;
    height: 3px;
  }
  

}

@media (max-width: 768px) {
  .content {
    width: 90vw; /* ปรับขนาด width เมื่อหน้าจอเล็กกว่าหรือเท่ากับ 768px */
    height: auto; /* กำหนด height เป็น auto เพื่อให้ความสูงของ content ขยายตามเนื้อหา */
    margin: 10px auto; /* ปรับ margin เพื่อให้ content อยู่กึ่งกลาง */
    padding: 10px; /* ปรับ padding เมื่อหน้าจอเล็กกว่าหรือเท่ากับ 768px */
  }
  .custom-list {
    font-size: 16px;
    margin-left: 32px;
  }
  
  .custom-list li {
    padding-left: 32px;
    margin: 16px 0;
    
  }
  
  .custom-list li::before {
    width: 12px;
    height: 12px;
  }


  .time {
    font-size: 16px;
    padding: 10px 30px;
    border-radius: 40px;
  }
  .detail_1{
    margin-top:15px;
    margin-left: 30px;
    margin-bottom: 10px;
  
  }

  .text{
    font-size:16px ;
    margin-left: 10px;
    
  }

  .header {
    margin-bottom: 10px;
    margin-left: 5px;
    margin-top:10px;
    
  }
  
  .vertical-line::before {
    top: -10px;
    width: 10px;
    height: 40px;
    margin-left: 15px;
    border-radius: 10px;
    
  }

  .gradient-text {
    padding-top: 5px;
    font-size: 30px;
    margin-left: 30px;
    
  }

  .white-line {
    bottom: -10px; 
    width: 200%;
    height: 3px;
  }
  
}

@media (max-width: 480px) {
  .content {
    width: 90vw; /* ปรับขนาด width เมื่อหน้าจอเล็กกว่าหรือเท่ากับ 480px */
    height: auto; /* กำหนด height เป็น auto เพื่อให้ความสูงของ content ขยายตามเนื้อหา */
    margin: 10px auto; /* ปรับ margin เพื่อให้ content อยู่กึ่งกลาง */
    padding: 10px; /* ปรับ padding เมื่อหน้าจอเล็กกว่าหรือเท่ากับ 480px */
  }
  .custom-list {
    font-size: 12px;
    
  }
  
  .custom-list li {
    padding-left: 24px;
    margin: 12px 0;
  }
  
  .custom-list li::before {
    width: 8px;
    height: 8px;
  }

  .time {
    font-size: 12px;
    padding: 10px 20px;
    border-radius: 40px;
    
  }
  .detail_1{
    margin-top:10px;
    margin-left: 30px;
    margin-bottom: 10px;
  }
  .text{
    font-size:10px ;
    margin-left: 10px;
    
  }
  .header {
    margin-bottom: 10px;
    margin-left: 5px;
    margin-top:10px;
    
  }
  
  .vertical-line::before {
    top: -3px;
    width: 10px;
    height: 30px;
    margin-left: 15px;
    border-radius: 10px;
    
  }

  .gradient-text {
    padding-top: 5px;
    font-size: 20px;
    margin-left: 30px;
    
  }

  .white-line {
    bottom: -10px; 
    width: 200%;
    height: 5px;
  }
}

@media (max-width: 360px) {
  .content {
    width: 90vw; /* ปรับขนาด width เมื่อหน้าจอเล็กกว่าหรือเท่ากับ 360px */
    height: auto; /* กำหนด height เป็น auto เพื่อให้ความสูงของ content ขยายตามเนื้อหา */
    margin: 10px auto; /* ปรับ margin เพื่อให้ content อยู่กึ่งกลาง */
    padding: 10px; /* ปรับ padding เมื่อหน้าจอเล็กกว่าหรือเท่ากับ 360px */
  }

  .header {
    margin-bottom: 10px;
    margin-left: 5px;
    margin-top:10px;
    
  }
  
  .vertical-line::before {
    top: -3px;
    width: 10px;
    height: 30px;
    margin-left: 15px;
    border-radius: 10px;
    
  }

  .gradient-text {
    padding-top: 5px;
    font-size: 20px;
    margin-left: 30px;
    
  }
  .custom-list {
    font-size: 12px;
  }
  
  .custom-list li {
    padding-left: 24px;
    margin: 12px 0;
  }
  
  .custom-list li::before {
    width: 8px;
    height: 8px;
  }
  .time {
    font-size: 10px;
    padding: 2vw 10px;
    border-radius: 20px;
  }
  .detail_1{
    margin-top:10px;
    margin-left: 20px;
  }
  .text{
    font-size:10px ;
    margin-left: 10px;
    
  }
  .white-line {
    bottom: -10px; 
    width: 200%;
    height: 5px;
  }
}

  </style>
  