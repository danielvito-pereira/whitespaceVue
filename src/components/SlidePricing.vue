<template>
  <section class="SlidePricing">
    <div class="head">
        <div class="text-block">
          <h1 class="titulo">Choose Your Plan</h1>
          <p class="paragrafo">
            Whether you want to get organized, keep your personal life on track, or boost workplace productivity, Evernote has the right plan for you.
          </p>
        </div>
    </div>
    <div class="priceList">
      <div class="priceBoard -dourado">
        <div class="text">
            <h1>Free</h1>
            <p>$0</p>
            <p>Capture ideas and find them quickly</p>
          </div>
          <div class="bulletPoint">
            <div class="point -t">
              <img src="" alt="" srcset="">
              <p>Sync unlimited devices</p>
            </div>
            <div class="point -t">
              <img src="" alt="" srcset="">
              <p>10 GB monthly uploads</p>
            </div>
            <div class="point -t">
              <img src="" alt="" srcset="">
              <p>200 MB max. note size</p>
            </div>
            <div class="point -t">
              <img src="" alt="" srcset="">
              <p>Customize Home dashboard and access extra widgets</p>
            </div>
            <div class="point -t">
              <img src="" alt="" srcset="">
              <p>Connect primary Google Calendar account</p>
            </div>
            <div class="point -t">
              <img src="" alt="" srcset="">
              <p>Add due dates, reminders, and notifications to your tasks</p>
            </div>
          </div>
      </div>
      <div class="priceBoard">
        <div class="text">
          <h1>Personal</h1>
          <p class="-goldNumber">$11.99</p>
          <p>Keep home and family on track</p>
        </div>
        <div class="bulletPoint">
          <div class="point -t">
            <img src="" alt="" srcset="">
            <p>Sync unlimited devices</p>
          </div>
          <div class="point -t">
            <img src="" alt="" srcset="">
            <p>10 GB monthly uploads</p>
          </div>
          <div class="point -t">
            <img src="" alt="" srcset="">
            <p>200 MB max. note size</p>
          </div>
          <div class="point -t">
            <img src="" alt="" srcset="">
            <p>Customize Home dashboard and access extra widgets</p>
          </div>
          <div class="point -t">
            <img src="" alt="" srcset="">
            <p>Connect primary Google Calendar account</p>
          </div>
          <div class="point -t">
            <img src="" alt="" srcset="">
            <p>Add due dates, reminders, and notifications to your tasks</p>
          </div>
        </div>
      </div>
      <div class="priceBoard -dourado">
        <div class="text">
          <h1>Organization</h1>
          <p>$49.99</p>
          <p>Capture ideas and find them quickly</p>
        </div>
        <div class="bulletPoint">
            <div class="point -t">
              <img src="" alt="" srcset="">
              <p>Sync unlimited devices</p>
            </div>
            <div class="point -t">
              <img src="" alt="" srcset="">
              <p>10 GB monthly uploads</p>
            </div>
            <div class="point -t">
              <img src="" alt="" srcset="">
              <p>200 MB max. note size</p>
            </div>
            <div class="point -t">
              <img src="" alt="" srcset="">
              <p>Customize Home dashboard and access extra widgets</p>
            </div>
            <div class="point -t">
              <img src="" alt="" srcset="">
              <p>Connect primary Google Calendar account</p>
            </div>
            <div class="point -t">
              <img src="" alt="" srcset="">
              <p>Add due dates, reminders, and notifications to your tasks</p>
            </div>
        </div>

      </div>
    </div>
    <div class="indicadores">
      <button id="bb" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" aria-label="Slide 1" class="" aria-current="true"></button>
      <button id="bb" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" aria-label="Slide 2" class="active" aria-current="true"></button>
      <button id="bb" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" aria-label="Slide 3" class="" aria-current="true"></button>
    </div>
  </section>
</template>


<style lang="scss">
    .SlidePricing{
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      gap: 50px;
      width: 100%;
      padding: 5em;
      overflow: hidden;
      .head{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 60px;
        width: 100%;
        padding:1em;
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
        }
      .priceList{
          display: flex;
          flex-direction: row;
          justify-content: center;
          align-items: center;
          padding: 0px;
          gap: 32px;
          width: 1481px;
          padding: 1em;
          background-color: red;
          .priceBoard{
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: flex-start;
            padding: 80px 44px;
            gap: 25px;
            width: 90%;
            padding: 1em;
            background: #04730a;
            box-shadow: 0px 4px 50px rgba(0, 0, 0, 0.08);
            border-radius: 10px;
              .text{
                  display: flex;
                  flex-direction: column;
                  align-items: flex-start;
                  padding: 0px;
                  gap: 25px;
                  width: 90%;
                  padding: 1em;
                  background: #730404;
                  h1{
                    font-family: 'Inter';
                    font-style: normal;
                    font-weight: 600;
                    font-size: 24px;
                    line-height: 36px;
                  }
                  p.-goldNumber{
                    font-family: 'Inter';
                    font-style: normal;
                    font-weight: 700;
                    font-size: 36px;
                    line-height: 44px;
                    /* identical to box height */

                    letter-spacing: -0.02em;

                    color: #FFE492;
                  }
              }
          }
          .priceBoard.-dourado{
            background-color: var(--white);
            color: var(--negro);
            border: 1px solid var(--button2);
          }

        }  
      .indicadores{
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center;
        padding: 0px;
        gap: 12px;
        width: 60px;
        height: .5em;
        
        #bb{
          width: 12px;
          height: 12px;
          border-radius:50%;
          background: var(--blue-2);
          cursor: pointer;
          
          &:hover{
            background:var(--primary-color);
            transition: all .5s ease-in-out;
          }
        }
      }  
    }

</style>

      


<script>
export default {
  name: 'SlidePricing',

}
</script>