<template>
  <section class="sponsors">
    <h1 class="titulo">Our sponsors</h1>
    <div class="imagens">
      <img src="../assets/img/Apple.png" alt="">
      <img src="../assets/img/microsoft 1.png" alt="">
      <img src="../assets/img/Slack_Technologies_Logo 1.png" alt="">
      <img src="../assets/img/Group 246.png" alt="">
    </div>
  </section>
</template>

<style lang="scss">
  .sponsors{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 100px;
    width: 100%;
    height: 903px;
      h1.titulo{
        font-family: 'Inter';
        font-style: normal;
        font-weight: 700;
        font-size: 42px;
        line-height: 44px;
        text-align: center;
        letter-spacing: -0.02em;
        color:var(--white);
      }
  }
  @media screen and (min-width:912px){
    .sponsors{
      flex-direction: row;
    }
  }
</style>

<script>
  export default {
    name: 'OurSponsors',
  }
</script>