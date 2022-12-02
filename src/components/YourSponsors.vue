<template>
  <section class="YourSponsors">
    <div class="text-block">
      <h1 class="titulo">Your sponsors</h1> 
    </div>
    <div class="sponsors">
          <figure class="-t">
            <img src="../assets/img/Apple.png" alt="">
          </figure>
          <figure>
            <img src="../assets/img/microsoft1.png" alt="">
          </figure>
          <figure>
            <img src="../assets/img/SlackTechnologiesLogo1.png" alt="">
          </figure>
          <figure>
            <img src="../assets/img/Group246.png" alt="">
          </figure>
        </div>
  </section>
</template>

<style lang="scss">
  .YourSponsors{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    padding: 1em;
    gap: 100px;
    
    .text-block {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      gap: 24px;
      width: 100%;
      h1.titulo{
        font-family: 'Inter';
        font-style: normal;
        font-weight: 700;
        font-size: 42px;
        line-height: 44px;
        text-align: center;
        letter-spacing: -0.02em;
        color:var(--negro);
      }
      .paragrafo{
        font-family: 'Inter';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 30px;
        text-align: center;
        letter-spacing: -0.02em;
        color:var(--negro);
      }

    }
    .sponsors {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 1em;
      gap: 100px;
      figure.-t{
          width: 30%;
          height: 30%;
        }
      figure{
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
        height: 100%;
          img {
          width: 90%;
        }
      }
    }
  }
 
  @media screen and (min-width:912px){
    .YourSponsors{

      .sponsors {
 
 
      }
    }
     /*
    .YourSponsors{
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 80px 16px;
      gap: 100px;
      width: 100%;
      height: 903px;
      left: 0px;
      margin-bottom: 3rem;
      .sponsors {
        flex-direction: row;
        width: 100%;
        gap: 50px;
        height: 71px;
        figure.-t{
          width: 30%;
          height: 30%;
        }
        figure{
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
        height: 100%;
          img {
          width: 90%;
        }
      }
      }
    }
    */  
  }     
</style>

<script>
  export default {
    name: 'YourSponsors',
  }
</script>