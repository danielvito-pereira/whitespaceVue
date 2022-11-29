<template>
  <section class="WorkManagement">
    <div class="content">
      <div class="heading">
        <div class="head">
          <div class="text-block">
            <h1 class="titulo">Project Management</h1>
            <p class="paragrafo">
              Images, videos, PDFs and audio files are supported. Create math expressions and diagrams directly from the app. Take photos with the mobile app and save them to a note.
            </p>
          </div>
          <a class="bt -azul">Get Started</a>
        </div>
      <div class="img"></div>
      </div>
    </div>
    <div class="content">
      <div class="heading">
        <div class="head">
          <div class="text-block">
            <h1 class="titulo">Work together</h1>
            <p class="paragrafo">
              With whitepace, share your notes with your colleagues and collaborate on them.
              You can also publish a note to the internet and share the URL with others.

            </p>
          </div>
          <a class="bt -azul">Try it now</a>
        </div>
      <div class="img"></div>
      </div>
    </div>
  </section>

</template>
<style lang="scss">
  .WorkManagement{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 80px 16px;
    gap: 100px;
    width: 100%;
    height: 1586.74px;
    left: 0px;

    .content{
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 0px;
      gap: 60px;
      width: 90%;
      height: 659px;
      
        .heading{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 0px;
        gap: 50px;
        height:100%;
        min-width: 288px;
        height: 653px;
 
        .head{

          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          padding: 1em;
          gap: 60px;
          width: 100%;
          .text-block {
            background:red;
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
              font-size: 35px;
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
          width: 80%;
          min-width: 270px;
          height: 191px;
        }
        }
    }
  }
</style>

<script>
export default {
  name: 'HeroSection',
}
</script>