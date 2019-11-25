<template>
    <div class="container" >
        <main>
            <div class="top-content">
                <img src="../assets/logo.svg" alt="logo">
                <h2>foldr.me</h2>
                <p>One page website for creator</p>
            </div>
            <div class="form">
                <input type="email" name="email" placeholder="Email" />
                <button type="button">Reset Password</button>
            </div>
        </main>
        <div class="page-footer">
            <a href="">TERMS</a><span class="separator">|</span>
            <a href="">PRIVACY</a><span class="separator">|</span>
            <a href="">CONTACT</a>
            <p>COPYRIGHT 2019@FOLDIR.ME</p>
        </div>
    </div>
</template>

<script>
export default {
  name: 'forgotpassword',
  data() {
    return {
      
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
*{
    padding: 0px;
    margin: 0px;
}
.container{
    display: flex;
    flex-direction: column;
    height: 100vh;
}
main {
  flex: 1 0 auto;
}
a{
    text-decoration: none;
    color: #000000;
}
.top-content{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: #000000;
    img{

    }
    h2{
        font-style: normal;
        font-weight: bold;
        font-size: 32px;
        line-height: 39px;
    }
    p{
        font-style: normal;
        font-weight: bold;
        font-size: 11px;
        line-height: 13px;
    }
}
.form{
    display: grid;
    justify-content: center;
    align-items: center;
    text-align: center;
    font-style: normal;
    font-weight: normal;
    margin-top: 70px;
    input{
        width: 240px;
        height: 40px;
        background: #FFFFFF;
        border: 2px solid #000000;
        border-radius: 20px;
        padding: 0px 10px;
        margin: 5px 0px;
        
        font-size: 11px;
        line-height: 13px;
        &:focus{
            outline: none;
        }
    }
    button{
        width: 240px;
        height: 40px;
        margin: 5px 0px;
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
    .signup-txt{
        font-size: 14px;
        line-height: 17px;
    }
    .forgot-txt{
        font-size: 10px;
        line-height: 12px;
        margin-top: 20px;
    }
}
.page-footer{
    height: 50px;
    flex-shrink: 0;
    text-align: center;
    a{
        font-size: 10px;
        line-height: 12px;
        padding-right: 5px;
    }
    .separator{
        font-size: 10px;
        line-height: 12px;
    }
    p{
        font-size: 10px;
        line-height: 12px;
        margin-top: 10px;
    }
}
</style>
