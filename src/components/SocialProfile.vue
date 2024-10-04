<template>
  <div class="social-bg">
    <div class="container social-contents">
      <i class="pi pi-tiktok"></i>
      <h1>เชื่อมรหัสสมาชิก กับ Tiktok</h1>
      <i class="fa-solid fa-file-circle-plus"></i>
      <h1>เข้าสังกัดแล้ว</h1>
      <i class="bi bi-person-lines-fill"></i>
      <h1>ลงทะเบียนข้อมูลส่วนตัวแล้ว</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SocialProfile',
};
</script>

<style scoped>
.social-bg {
  background: linear-gradient(170deg, #8316B9, #371B70);
  display: flex;
  align-items: center;
  justify-content: center;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  position: relative;
}

.social-contents {
  display: flex;
  flex-direction: row;
  /* จัดเรียงในแนวแถว */
  align-items: center;
  /* จัดให้อยู่กลางในแนวตั้ง */
  gap: 40px;
  padding: 2rem 0;
}

.pi-tiktok, .fa-file-circle-plus, .bi-person-lines-fill {
  background-color: white;
  padding: 0.5rem;
  font-size: 3rem;
  border-radius: 4px;
  color: #371B70;
}

h1 {
  color: white;
  font-size: 2rem;
}
</style>
