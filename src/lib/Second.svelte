<section class={$$props.class}>
  <div class="one column">
    <h3>what is cloud architecture?</h3>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt natus
      asperiores animi doloribus esse quibusdam consectetur cupiditate neque,
      dolorum placeat vel deleniti tempora alias aspernatur assumenda mollitia
      laboriosam, qui non?
    </p>
  </div>
  <div class="two">
    <a href="#"
      ><div class="image-wrapper" id="heroImage">
        <img class="image" src="../../assets/9.png" alt="some pic" />
      </div></a
    >
    <a href="#"
      ><div class="image-wrapper" id="heroImage">
        <img class="image" src="../../assets/1.png" alt="some pic" />
      </div></a
    >
    <a href="#"
      ><div class="image-wrapper" id="heroImage">
        <img class="image" src="../../assets/10.png" alt="some pic" />
      </div></a
    >
    <a href="#"
      ><div class="image-wrapper" id="heroImage">
        <img class="image" src="../../assets/3.png" alt="some pic" />
      </div></a
    >
  </div>
  <div class="three" />
</section>

<style lang="scss">
  .section {
    &__2 {
      // padding: 1rem;
      text-align: center;
      flex-flow: column;
      justify-content: center;
      align-items: center;
      height: auto;
      // gap: 6rem;
      // padding: 1rem;
      gap: 4rem;
      &>* {
        flex-basis: 50%;
        display: flex;
      
      }
      .one {
        gap: 2rem;
        max-width: 50ch;
      }
      .two {
        // margin-top: -3rem;
        min-height: 50vh;
        display: flex;
        flex-flow: row wrap;
        gap: 2rem;
        justify-content: center;
        width: 100vw;

        .image-wrapper {
          // flex-basis: 1%;
          // position: relative;
          // overflow: hidden;
          width: auto;
          z-index: -1;
          display: flex;
          align-items: center;
          justify-content: center;

          .image {
            border-radius: 2rem;

            // position: absolute;
            width: 15rem;
            height: 15rem;
            object-fit: cover;
            z-index: -1;
          }
   }
      }

      // align-items: flex-end;
      // overflow: hidden;
    }
  }
</style>
