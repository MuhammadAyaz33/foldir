<template>
    <div class="footer">
        <a href="#"><img src="../assets/upload.svg" alt="upload"></a>
        <a href="#"><img src="../assets/stats.svg" alt="stats"></a>
        <a href="#"><img src="../assets/add.svg" alt="add"></a>
        <a href="#"><img src="../assets/adjust.svg" alt="edit"></a>
        <a href="#"><img src="../assets/user.svg" alt="profile"></a>
    </div>
</template>

<script>
export default {
  name: 'footer',
  data() {
    return {
      
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
.footer{
    height: 60px;
    background: #191718;
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    justify-content: center;
    align-items: center;
    text-align: center;
}
</style>
