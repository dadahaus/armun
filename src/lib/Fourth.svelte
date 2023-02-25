<section class={$$props.class}>
  <div class="one column">
    <div> <h5>Cómo es una transformación digital a través de tecnología Cloud Native:</h5>
    </div>
    <div></div>
    <div></div>
    <div></div>
  </div>
  <div class="two" />
</section>

<style lang="scss">
  .section {
    &__4 {
      height: auto;
      // transform: translateY(2.5rem);
      margin-top: 5%;
      align-items: center;
      justify-content: center;
      gap: 3rem;
      flex-wrap: wrap;
      & > * {
        flex-basis: 45%;
        display: flex;
      }
      .one {
        text-align: center;
        justify-content: flex-end;

      }
      .two {
        overflow: hidden;
        min-height: 50vh ;
        max-height: 1000% ;
        // width: 50vw;
        background: center/ contain no-repeat hsla(0, 0%, 93%, 0) url("../../assets/hero_image.jfif");
        justify-content: flex-start;
      }
    }
  }
</style>
