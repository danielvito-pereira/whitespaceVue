<template>
  <section class="YourSponsors">
    <h1 class="titulo">Your sponsors</h1>
    <div class="sponsors">
          <figure>
            <img src="../assets/img/Apple.png" alt="">
          </figure>
          <figure>
            <img src="../assets/img/microsoft 1.png" alt="">
          </figure>
          <figure>
            <img src="../assets/img/Slack_Technologies_Logo 1.png" alt="">
          </figure>
          <figure>
            <img src="../assets/img/Group 246.png" alt="">
          </figure>
        </div>
  </section>
</template>

<style lang="scss">
  .sponsors {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    height: 813.16px;
    gap: 100px;

  }
</style>

<script>
  export default {
    name: 'YourSponsors',
  }
</script>