<template>
    <div class="zone zone7">
        <div class="border-wrapper">
            <div class="content">
                <div class="header">
                    <span class="gradient-text">สำหรับผู้เข้าร่วมงานลุ้นรับรางวัล</span>
                </div>
                <div class="container">
                    <div class="item">
                        <img src="../assets/reward_ipad.svg" class="reward_img" alt="">
                        <p class="name">Ipad Gen 10 64GB</p>
                        <p class="detail">1 รางวัล</p>
                    </div>
                    <div class="item">
                        <img src="../assets/reward_applewatch.svg" class="reward_img" alt="">
                        <p class="name">Apple watch SE</p>
                        <p class="detail">1 รางวัล</p>
                    </div>
                    <div class="item">
                        <img src="../assets/reward_sms.svg" class="reward_img" alt="">
                        <p class="name">Bulk SMS 5,000 sms</p>
                        <p class="detail">1 รางวัล</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Zone7'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@100..900&display=swap');

.zone7 {
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

.border-wrapper {
    background: linear-gradient(180deg,#152F9B00,#34EA67 );
    border-radius: 40px;
    padding: 5px;
    width: 80vw;
    height: 45vh;
    margin: 30px auto;
    box-sizing: border-box;
    display: flex;
    justify-content: center;
    align-items: center;
}

.content {
    background: white;
    border-radius: 30px;
    padding: 20px;
    width: 100%;
    height: 100%;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    overflow: hidden;
}

.header {
    margin-left: 70px;
    margin-top: 30px;
    position: relative;
}

.gradient-text {
    background: linear-gradient(to right, #0E044B, #2C309B, #97ecfe);
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    border-inline-color: transparent;
    font-size: 60px;
    font-weight: bold;
}

.container {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-top: 50px;
    margin-left: 15%;
    flex-wrap: wrap; /* ทำให้ .container สามารถ wrap .item ได้เมื่อหน้าจอเล็กลง */
}


.item {
    width: 350px;
    
    
}

.reward_img {
    width: 100%;
    height: 250px;
}

.name {
    color: rgba(38, 46, 63, 1);
    font-size: 40px;
    font-weight: bold;
    margin-top: 10px;
}

.detail {
    color: rgba(111, 119, 136, 1);
    font-size: 30px;
    font-weight: 500;
}

@media (max-width: 1024px) {
    .zone7 {
        width: 100vw;
        height: auto;
    }
    .border-wrapper {
        width: 90vw;
        height: auto;
    }
    .header {
        margin-left: 40px;
        margin-top: 10px;
    }
    .gradient-text {
        font-size: 40px;
    }
    .container {
        padding: 0 8%;
        gap: 20px;
        margin-left: 10px;
    }
    .item {
        width: 160px;
    }
    
    .name {
        font-size: 24px;
    }
    .detail {
        font-size: 24px;
    }
}

@media (max-width: 768px) {
    .zone7 {
        width: 100vw;
        height: auto;
    }
    .border-wrapper {
        padding: 5px;
        width: 90vw;
        height: auto;
    }
    .header {
        margin-left: 20px;
        margin-top: 10px;
    }
    .gradient-text {
        font-size: 30px;
    }
    .container {
        padding: 0 5%;
        gap: 20px;
    }
    .item {
        width: 100%;
    }
    .reward_img {
        height: auto;
        width: 20vw;
    }
    .name {
        font-size: 24px;
    }
    .detail {
        font-size: 24px;
    }
}

@media (max-width: 480px) {
    .zone7 {
        width: 100vw;
        height: auto;
    }
    .border-wrapper {
        padding: 5px;
        width: 95vw;
        height: auto;
    }
    .header {
        margin-left: 10px;
        margin-top: 10px;
    }
    .gradient-text {
        font-size: 24px;
    }
    .container {
        padding: 0 3%;
        gap: 30px;
        margin-top:20px;
        
    }
    .item {
        width: 200px;
        
    }
    .reward_img {
        height: auto;
        width: 20vw;
    }
    .name {
        font-size: 18px;
    }
    .detail {
        font-size: 18px;
    }
}

@media (max-width: 380px) {
    .zone7 {
        width: 100vw;
        height: auto;
    }
    .border-wrapper {
        padding: 5px;
        width: 95vw;
        height: auto;
    }
    .header {
        margin-left: 10px;
        margin-top: 10px;
    }
    .gradient-text {
        font-size: 24px;
    }
    .container {
        padding: 0 3%;
        gap: 30px;
        margin-top:20px;
        
    }
    .item {
        width: 200px;
        
    }
    .reward_img {
        height: auto;
        width: 20vw;
    }
    .name {
        font-size: 18px;
    }
    .detail {
        font-size: 18px;
    }
}

</style>
