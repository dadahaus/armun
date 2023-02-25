<section class={$$props.class}>
  <h3 class="one">we worry about maintenance so you don't have to</h3>
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
