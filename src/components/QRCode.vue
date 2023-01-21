<template>
  <div class="root-container">
    <div class="main-container">
      <img alt="qr-code" class="qr-code-image" src="@/assets/image-qr-code.png">
      <h1 class="title">Improve your front-end skills by building projects</h1>
      <p class="description">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'QRCode',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.root-container {
}

.main-container {
  padding: 1rem;
  background-color: #FFFFFF;
  box-shadow: 0 25px 25px rgba(0, 0, 0, 0.0476518);
  border-radius: 20px;
  max-width: 320px;
  max-height: 497px;
  display: flex;
  flex-direction: column;
}

.qr-code-image {
  border-radius: 20px;
}

.title {
  margin-top: 1.5rem;
  color: #1F314F;
  font-family: 'Outfit', serif;
  font-style: normal;
  font-weight: 700;
  font-size: 22px;
  line-height: 28px;
  text-align: center;
}

.description {
  margin: 1rem 1rem 2.5rem 1rem;
  font-family: 'Outfit', serif;
  font-style: normal;
  font-weight: 400;
  font-size: 15px;
  line-height: 19px;
  text-align: center;
  letter-spacing: 0.1875px;
  color: #7D889E;
}
</style>
