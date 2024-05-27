<template>
    <div class="zone zone6">
        <div class="content">
            <div class="head">
                <div class="text-container">
                    <div class="header-detail-container">
                        <img src="../assets/ic_location.svg" class="location_icon" alt="">
                        <span class="head-detail">ณ ห้องแกรนด์บอลรูม ชั้น 4</span>
                    </div>
                    <span class="detail">โรงแรมพูลแมน กรุงเทพแกรนด์ สุขุมวิท</span>
                    <button class="button">ดูแผนที่ google map</button>
                </div>
                <img src="../assets/Grand Ballroom Classroom1.svg" class="location_img" alt="">
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Zone6'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@100..900&display=swap');

.zone6 {
    position: relative;
    width: 100vw;
    height: auto; /* ตั้งค่าความสูงให้เต็มจอ */
    display: flex;
    align-items: flex-start; 
    overflow: hidden;
    margin: 0;
    padding: 0;
    font-family: 'Noto Sans Thai', sans-serif;
    
}

.content {
    background: linear-gradient(230.87deg, #5D97E3 -7.19%, #0C2192 66.6%);
    border-radius: 40px;
    padding: 20px;
    width: 80vw;
    height: 35vh;
    margin: 30px auto;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.head {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.text-container {
    margin-left: 5%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin-top: -3%;
}

.header-detail-container {
    display: flex;
    align-items: center;
    margin-bottom: -5%;
}

.head-detail {
    font-size: 65px;
    font-weight: bold;
    color: white;
    margin-left: 75px;
}

.detail {
    font-size: 60px;
    font-weight: normal;
    color: #FFFFFF;
    margin-left: 250px;
}

.button {
    background: rgba(53, 158, 255, 1);
    border: none;
    color: white;
    font-size: 40px; 
    font-weight: bold;
    padding: 30px 70px;
    border-radius: 90px;
    margin-top: 40px;
    align-self: flex-start;
    margin-left: 250px; 
}

.location_img {
    width: 20vw;
    height: auto;
    margin-right: 20px;
}

.location_icon {
    width: 6vw;
    height: auto;
    margin-top: 80px;
}

/* Media Queries */
@media (max-width: 1024px) {
    .content {
        width: 90vw;
        height: auto;
    }

    .head {
        flex-direction: column;
        align-items: flex-start;
    }

    .head-detail {
        font-size: 30px;
        margin-left: 7vw;
    }

    .header-detail-container {
    margin-bottom:-2vh;
}

    .detail {
        font-size: 25px;
        margin-left: 15vw;
        margin-bottom:-2vh;
    }

    .button {
        font-size: 25px;
        padding: 10px 30px;
        margin-left: 15vw;
    }

    .location_img {
        width: 25vw;
        height: auto;
        margin-left: 60vw;
        margin-top: -22vh;
    }

    .location_icon {
        width: 8vw;
        margin-top: 5vh;
    }
}

@media (max-width: 768px) {
    .content {
        width: 90vw;
        height: auto;
    }

    .head {
        flex-direction: column;
        align-items: flex-start;
    }

    .head-detail {
        font-size: 25px;
        margin-left: 2vw;
    }

    .header-detail-container {
    margin-bottom:-3vh;

}

    .detail {
        font-size: 20px;
        margin-left: 10vw;
        margin-bottom:-3vh;
    }

    .button {
        font-size: 20px;
        padding: 5px 20px;
        margin-left: 10vw;
    }

    .location_img {
        width: 25vw;
        height: auto;
        margin-left: 60vw;
        margin-top: -15vh;
    }

    .location_icon {
        width: 8vw;
        margin-top: 5vh;
    }
}

@media (max-width: 480px) {

    .content {
        width: 90vw;
        height: 15vh;
    }

    .head {
        flex-direction: column;
        align-items: flex-start;
    }

    .head-detail {
        font-size: 15px;
        margin-left: 2vw;
    }

    .header-detail-container {
    margin-bottom:-2vh;
   

}

    .detail {
        font-size: 13px;
        margin-left: 10vw;
        margin-bottom:-3vh;
    }

    .button {
        font-size: 13px;
        padding: 5px 10px;
        margin-left: 10vw;
        margin-bottom:3vh;
    }

    .location_img {
        width: 22vw;
        height: auto;
        margin-left: 60vw;
        margin-top: -13vh;
    }

    .location_icon {
        width: 8vw;
        margin-top: 2vh;
    }

    .text-container {
    margin-left:2vw;
    margin-top: -3%;
}
    
}

@media (max-width: 380px) {

    .content {
        width: 90vw;
        height: auto;
    }

    .head {
        flex-direction: column;
        align-items: flex-start;
    }

    .head-detail {
        font-size: 13px;
        margin-left: 2vw;
    }

    .header-detail-container {
    margin-bottom:-2vh;
   

}

    .detail {
        font-size: 10px;
        margin-left: 10vw;
        margin-bottom:-3vh;
    }

    .button {
        font-size: 10px;
        padding: 5px 10px;
        margin-left: 10vw;
        margin-bottom:3vh;
    }

    .location_img {
        width: 25vw;
        height: auto;
        margin-left: 55vw;
        margin-top: -10vh;
    }

    .location_icon {
        width: 8vw;
        margin-top: 2vh;
    }

    .text-container {
    margin-left:-2vw;
    margin-top:-2vh;
}
    
}
</style>
