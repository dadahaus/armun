<section class={$$props.class}>
  <h3 class="one">we worry about maintenance so you don't have to</h3>
  <div class="two" />
</section>

<style lang="scss">
  .section {
    &__1 {
      height: auto;
      transform: translateY(2.5rem);
      align-items: center;
      justify-content: center;
      gap: 3rem;
      flex-wrap: wrap;
      & > * {
        flex-basis: 50%;
      }
      .one {
        text-align: center;
      }
      .two {
        overflow: hidden;
        height: 30vw;
        background: center/ contain no-repeat hsla(0, 0%, 93%, 0) url("../../assets/2.png");
      }
    }
  }
</style>
