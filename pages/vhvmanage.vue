<template>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" />
    <div class="page">
        <div class="sidebar">
            <img src="/assets/pictures/logotab.png" alt="logotab" />

            <div class="sidebar-item">
                <div class="sidebar-icon">
                    <i class="fa-solid fa-chart-pie"></i>
                </div>
                <a href="#" class="act">
                    <p>หน้าหลัก</p>
                </a>
            </div>

            <div class="sidebar-item">
                <div class="sidebar-icon">
                    <i class="fa-solid fa-circle-info"></i>
                </div>
                <a href="#">
                    <p>จัดการข้อมูลผู้ป่วย</p>
                </a>
            </div>

            <div class="sidebar-item">
                <div class="sidebar-icon">
                    <i class="fa-solid fa-chart-line"></i>
                </div>
                <a href="#">
                    <p>สถานะการติดตาม</p>
                </a>
            </div>

            <div class="sidebar-item siderbar-item-active">
                <div class="sidebar-icon ">
                    <i class="fa-solid fa-people-group" style="color: white;"></i>
                </div>
                <a href="#">
                    <p style="color: white;">จัดการข้อมูลเจ้าหน้าที่ฯลฯ</p>
                </a>
            </div>

            <div class="sidebar-item">
                <div class="sidebar-icon">
                    <i class="fa-solid fa-right-from-bracket"></i>
                </div>
                <a href="#">
                    <p>ออกจากระบบ</p>
                </a>
            </div>

            <div class="hr"></div>
        </div>
        <div class="content">
            <!-- Top Bar -->
            <div class="flex items-center justify-between">
                <div class="top-bar-header">
                    <h1>จัดการข้อมูลเจ้าหน้าที่ติดตามผู้ป่วย</h1>
                </div>
                <!-- Nav bar -->
                <div style="display: flex; align-items: center; margin: 0 10px">
                    <i class="fa-regular fa-bell" style="color: black; margin: 0 8px; padding: 8px; border-radius: 5px; background-color: #e5e7eb"></i>
                    <img style="width: 35px; height: 35px; margin: 0 5px; border-radius: 10px;" src="https://scontent.fcnx4-1.fna.fbcdn.net/v/t39.30808-6/340812573_1222119048693459_7878843100786500839_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=5f2048&_nc_ohc=b9yduR4LQ9kQ7kNvgGaKCrb&_nc_ht=scontent.fcnx4-1.fna&oh=00_AYDRLmFq01Xm3Kk-IHJEmezeU7fczDbwG1Czn6OgCs2UYA&oe=667260C2" alt="">
                    <p style="font-size: 10px; font-weight: 500;">Kanlayanee</p>
                </div>
            </div>

        </div>
       
    </div>

</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Kanit:wght@500&family=Mali:wght@700&family=Noto+Sans:ital,wght@0,100..900;1,100..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Noto Sans", sans-serif;
}

/* .top-bar {
    background-color: #5D97EF;
    display: flex;
    align-items: center;
} */


h1 {
    font-family: "Poppins", sans-serif;
    font-weight: 600;
    font-style: normal;
    font-size: 30px;
    padding: 10px;
}

.page {
    width: 100%;
    height: 100vh;
    background-color: rgb(255, 255, 255);
    display: flex;
    color: #151D48;
}

.sidebar {
    width: 25%;
    padding: 15px;
}

.content {
    width: 100%;
    background-color: rgb(255, 255, 255);
    /* border: 5px solid black; */
}


.sidebar-item {
    display: flex;
    align-items: center;
    margin: 20px 0;
    color: #808191;
}

.sidebar-icon {
    width: 45px;
    height: 45px;
    color: #808191;
    /* background-color: #353540; */
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 10px;
    margin-right: 20px;
}

.siderbar-item-active {
    color: #737791;
}

.siderbar-item-active {
    background-color: #5D97EF;
    color: #ffff;
    border-radius: 10px;
}

.fa-chart-pie {
    color: #737791;
}

.sidebar-item a {
    text-decoration: none;
    color: #737791;
}

.sidebar-item .act {
    text-decoration: none;
    color: #737791;
}

.fa-solid {
    font-size: 1.5rem;
}

.hr {
    width: 100%;
    height: 1px;
    background-color: #393846;
}
</style>

<script>

</script>