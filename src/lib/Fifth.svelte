<section class={$$props.class}>
  <div class="one"></div>
  <div class="two row">
    <h5>some other strategy</h5>
    <a href="http://"><div></div></a>
    <a href="http://"><div></div></a>

  </div>
</section>

<style lang="scss">
  .section {
    &__5 {
      height: 100vh;
      padding: 0;
      .one {
        flex-basis: 10%;
        height: 100%;
        width: 100%;
        background: center/ cover no-repeat #eee url("../../assets/image.jpg");
      }
      .two {
        justify-content: space-evenly;
        align-items: center;
        flex-basis: 90%;
        &>*:nth-child(n+2){
        background: center/ cover no-repeat #eee url("../../assets/2.png");
        width: 15%;
        height: 15%;
        border-radius: 5rem;
        }
      }
    }
  }
</style>
