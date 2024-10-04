<template>
    <div class="Baner"></div>

    <div class="container">
        <div class="nav">
            <i class="pi pi-bell"></i>
            <div>
                <div>รหัสสมาชิก 2456789 </div>
                <div>รหัสผู้แนะนำ: 1203456</div>
            </div>
            <i class="pi pi-cog"></i>
        </div>
    </div>

    <div class="profile-layout">
        <div class="profile-info">
            <div class="avatar-container">
                <img src="/Avatar.png" alt="Profile Picture" class="profile-avatar" />
                <i class="pi pi-camera"></i>
            </div>
            <div class="profile-details">
                <div class="member-id-container">
                    <h2 class="member-id">รหัสสมาชิก 2456789</h2>
                    <h2 class="vip-label"><i class="fa-solid fa-medal"></i> VIP</h2>
                </div>
                <h2 class="end-profile-details">คุณธิดารินทร์ ธรรมวิเศษดำรง</h2>
            </div>
            <div class="container-link">
                <div class="link-profile">
                    <h3>ลิงค์สมัคร</h3>
                    <h3>Connect Tiktok to Zmall</h3>
                </div>
            </div>
            <div class="container-salary">
                <div class="head-salary">
                    <h2>รายได้วันนี้</h2>
                    <h2>0.00 <span class="currency">บาท</span></h2>
                </div>
                <div class="content-salary">
                    <h2>รายได้รวมทั้งหมด</h2>
                    <h2>19,000.00 <span class="currency">บาท</span></h2>
                </div>
                <div class="divider"></div> <!-- เส้นกั้น CSS -->
                <div class="end-salary">
                    <h>อัพเดท ณ วันที่ 21 ก.ย. 67</h>
                    <button>ดูรายละเอียด</button>
                </div>
            </div>
            <div class="container-score">
                <div class="head-score">
                    <h2>คะแนนสะสมจากการ Shoping</h2>
                    <h2>56.45 <span class="unit">คะแนน</span></h2>
                </div>
                <div class="content-score">
                    <h2>คะแนนที่โอนเป็น ZP แล้ว</h2>
                    <h2>24.00 <span class="unit">คะแนน</span></h2>
                </div>
                <div class="content-score">
                    <h2>คะแนนที่ App ยืนยันแล้ว</h2>
                    <h2>00.45 <span class="unit">คะแนน</span></h2>
                </div>
                <div class="content-score">
                    <h2>คะแนนที่รอ App ยืนยัน</h2>
                    <h2>32.00 <span class="unit">คะแนน</span></h2>
                </div>
                <div class="divider"></div> <!-- เส้นกั้น CSS -->
                <div class="end-score">
                    <h3>อัพเดท ณ วันที่ 23 ก.ย. 67</h3>
                    <button>ดูรายละเอียด</button>
                </div>
            </div>
        </div>
    </div>


</template>

<script>
 export default {
    name: 'DashboardProfile',
  };
</script>

<style scoped>
@import '/src/styles/DashboardProfile.css';
</style>