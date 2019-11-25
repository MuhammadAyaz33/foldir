<template>
    <div class="header">
        <h2>props data</h2>
        <a href="#"><img src="../assets/view.svg" alt="view"></a>
    </div>
</template>

<script>
export default {
  name: 'header',
  data() {
    return {
      
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
.header{
    height: 60px;
    flex-shrink: 0;
    background: #191718;
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    justify-content: center;
    align-items: center;
    text-align: center;
}
</style>
