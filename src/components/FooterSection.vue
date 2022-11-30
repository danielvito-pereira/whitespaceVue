
<template>
  <footer>
    <div class="conteudo">
      <div class="info">
        <div class="logo-description">
          <img src="./assets/img/Logo.png" alt="">
          <p class="paragraph">whitepace was created for the new ways we live and work. 
            We make beautyfully designed around the world</p>
        </div>
        <div class="inf">
          <h1>Product</h1>
          <p>Overview</p>
          <p>Pricing</p>
          <p>Customer Stories</p>
        </div>
        <div class="inf">
          <h1>Resources</h1>
          <p>Blog</p>
          <p>Guides & tutorials</p>
          <p>Help center</p>
        </div>
        <div class="inf">
          <h1>Company</h1>
          <p>About us</p>
          <p>Careers</p>
          <p>Media Kit</p>
        </div>
        <di class="try-btn">
          <h1>Try It Today</h1>
          <p class="paragraph">Get started for free.
            Add your whole team as your needs grow.</p>
            <button  class="main-button -blue">Start today </button>
        </di>
      </div>
    </div>
    <div class="btm">
      <div class="terms">
        <p  class="paragraph">Terms & privacy</p>
        <p class="paragraph">Security</p>
        <p class="paragraph">Status</p>
        <p class="paragraph">©2021 Whitepace LLC.</p>
      </div>
      <div class="social">
        <a href="">
          <img src="./assets/img/Icon_11_.png" alt="">
        </a>
        <a href="">
          <img src="./assets/img/Group11.png" alt="">
        </a>
        <a href="">
          <img src="./assets/img/Linkedin.png" alt="">
        </a>
      </div>
    </div>
  </footer>
</template>

<style lang="scss">

  @media screen and (min-width:912px){

  }
  @media screen and (min-width:1400px ){

  }

/*Botão */
  .bt{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 1em ;
    width: 227px;
    background: #4F9CF9;
    color: #FFFFFF;
    border-radius: 8px;
    cursor: pointer;


    &:hover{
      color: #043873;
      transition: all .5s ease-in-out;
    }
    
    
  }
  .-azul {
      &::after{
      content: url("../assets/img/Group\ 212.png");    
      display: block;
      margin-left:1em;
    }
    &:hover:after {
      transform:  translate(5px, 0%);
      transition: all 0.5s ease-in-out;
    }
    }
</style>

<script>
export default {
  name: 'FooterSection',
}
</script>