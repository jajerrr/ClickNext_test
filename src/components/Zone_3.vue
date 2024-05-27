<template>
    <div class="zone zone3">
      <div class="content">
        <p class = "header">
          <span class="detail">พบกับกุญแจสำคัญของ</span><span class="detail-green">   ”Healthcare”   </span> 
          <span class="detail">แห่งอนาคตได้ที่งานสัมมนานี้</span>
        </p>
        <ul class="custom-list">
          <li>เพิ่มศักยภาพการรักษา และการให้บริการด้วย IoT, AI diagnosis, Telemedicine, Self-service และ Medical Service Platform</li>
          <li>ก้าวสู่ Smart Healthcare ด้วย Intelligent Infrastructure</li>
          <li>ยกระดับความสามารถในการรับมือกับภัยคุกคามทางไซเบอร์ด้วย AI & Automation</li>
          <li>ยกระดับการดูแลรักษาข้อมูลสำคัญในโรงพยาบาลด้วยเทคโนโลยีการปกป้องข้อมูล</li>
          <li>ลดระยะเวลาการทำงานของบุคลากรทางการแพทย์</li>
          <li>ยกระดับความพึงพอใจของผู้รับบริการด้านสาธารณสุข</li>
        </ul>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Zone3'
  }
  </script>
  
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@100..900&display=swap');

.zone3 {
    position: relative;
    width: 100vw;
    height: auto;
    background-color: transparent;
    display: flex;
    align-items: flex-start; 
    justify-content: center;
    overflow: hidden;
    margin: 0;
    padding: 0;
    font-family: 'Noto Sans Thai', sans-serif;
}

.content {
    margin-top: 20px;
    color: white;
    
}

.header{
    margin-top: 50px;

}
.detail {
    font-size: 70px;
    font-weight: bold;
    color: #1D1A73;
  }
  
  .detail-green {
    font-size: 70px;
    font-weight: bold;
    color: #0CC553;
  }
  
  .custom-list {
    list-style: none;
    text-align: left;
    font-size: 50px;
    color: black;

    
  }
  
  .custom-list li {
    position: relative;
    padding-left: 80px; 
    margin: 50px 0;
    
  }
  
  .custom-list li::before {
    content: '';
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateY(-50%) rotate(45deg);
    width: 40px;
    height: 40px;
    background-color: #25DF6C; 
    border-radius: 2px;
  }

  @media (max-width: 1024px) {
  .content {
    margin-left: 20px;
  }

  .detail {
    font-size: 32px;
  }
  
  .detail-green {
    font-size: 32px;
  }
  
  .custom-list {
    font-size: 24px;
  }
  
  .custom-list li {
    padding-left: 40px;
    margin: 24px 0;
  }
  
  .custom-list li::before {
    width: 20px;
    height: 20px;
  }
}

@media (max-width: 768px) {
  .content {
    margin-left: 30px;
  }

  .detail {
    font-size: 24px;
  }
  
  .detail-green {
    font-size: 24px;
  }
  
  .custom-list {
    font-size: 16px;
  }
  
  .custom-list li {
    padding-left: 32px;
    margin: 16px 0;
  }
  
  .custom-list li::before {
    width: 12px;
    height: 12px;
  }
}

@media (max-width: 480px) {
  .content {
    margin: 20px 20px;
  }

  .detail {
    font-size: 16px;
  }
  
  .detail-green {
    font-size: 16px;
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
}




  </style>
  