<template>
  <div class="logos-wrapper">
    <h2 class="title-header">Find Best Logos</h2>
    <div class="item-logos">
      <img src="../assets/docs.png" alt="Google Docs" class="logo" />
    </div>
    <div class="item-logos">
      <img src="../assets/drive.png" alt="Google Drive" class="logo" />
    </div>
    <div class="item-logos">
      <img src="../assets/gmail.png" alt="Google Gmail" class="logo" />
    </div>
    <div class="item-logos">
      <img src="../assets/maps.png" alt="Google Maps" class="logo" />
    </div>
    <div class="item-logos">
      <img src="../assets/photos.png" alt="Googlw Photos" class="logo" />
    </div>
  </div>
</template>

<script>
export default {
  name: `logos`
};
</script>

<style scoped>
.title-header {
  margin-bottom: 80px;
  text-align: left;
}
.logos-wrapper {
  width: 70%;
  overflow: hidden;
  margin: auto;
}

.item-logos {
  float: left;
  margin-right: 30px;
  margin-bottom: 70px;
  width: 150px;
  height: 150px;
}

.item-logos .logo {
  width: 120px;
  height: 120px;
}
</style>