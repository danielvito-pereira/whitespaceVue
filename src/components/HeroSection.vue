<template>
  <section class="heroSection">
    <div class="heading">
      <div class="head">
        <div class="text-block">
          <h1 class="titulo">Get More Done with whitepace</h1>
          <p class="paragrafo">
            Project management software that enables your teams to collaborate, plan, analyze and manage everyday tasks
          </p>
        </div>
        <a class="bt -azul">Try Whitepace free</a>
      </div>
      <div class="img"></div>
    </div>
  </section>
</template>

<style lang="scss">
  .heroSection{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 1em;
    gap: 100px;
    width: 100%;
    height: 813px;
    background: #043873;
    background-image: url("../assets/img/Element.svg");
    background-repeat: no-repeat;
    background-size: cover;
    .heading{
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 0px;
      gap: 50px;
      height:90%;
      min-width: 288px;
      height: 653px;

      .head{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 1em;
        gap: 60px;
        width: 90%;
        .text-block {
          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          padding: 1em;
          gap: 24px;
          width: 100%;
          h1.titulo{
            font-family: 'Inter';
            font-style: normal;
            font-weight: 700;
            font-size: 46px;
            line-height: 44px;
            text-align: center;
            letter-spacing: -0.02em;
            color:var(--white);
          }
          .paragrafo{
            font-family: 'Inter';
            font-style: normal;
            font-weight: 400;
            font-size: 18px;
            line-height: 30px;
            text-align: center;
            letter-spacing: -0.02em;
            color:var(--white);
          }

        }
      }
      .img{
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        padding: 0px;
        gap: 4px;
        background-color: aqua;
        width: 90%;
        min-width: 270px;
        height: 191px;
      }
    }
  }

/*Botão */
  .bt{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 1.5em ;
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
  name: 'HeroSection',
}
</script>