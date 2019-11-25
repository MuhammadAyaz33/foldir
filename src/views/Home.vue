<template>
    <div class="my-container">
        <div class="page-header">
            <h2>SITES</h2>
            <a href="#"><img src="../assets/view.svg" alt="view"></a>
        </div>
        <main>
             <button type="button">NEW SITE</button>
        </main>
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
.my-container{
    display: flex;
    flex-direction: column;
    height: 90vh;
    .page-header{
        height: 60px;
        flex-shrink: 0;
        background: #191718;
        display: flex;
        padding: 0px 10px;
        justify-content: space-between;
        align-items: center;
        h2{
            font-weight: bold;
            font-size: 18px;
            line-height: 22px;
            color: #F8F0EA;
        }
    }
    main {
        flex: 1 0 auto;
         button{
            width: 160px;
            height: 40px;
            border-radius: 20px;
            margin: 15px 10px;
            font-weight: bold;
            font-size: 18px;
            line-height: 22px;
            background: #F7C99F;
            border: 2px solid #000000;
            border-radius: 20px;
            &:focus{
                outline: none;
            }
        }
    }
}

</style>
