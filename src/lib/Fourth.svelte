<section class={$$props.class}>
  <div class="one">
    <a href="#"
      ><div class="image-wrapper" id="heroImage">
        <img class="image" src="../../assets/9.png" alt="some pic" />
      </div></a
    >
    <a href="#"
      ><div class="image-wrapper" id="heroImage">
        <img class="image" src="../../assets/9.png" alt="some pic" />
      </div></a
    >
    <a href="#"
      ><div class="image-wrapper" id="heroImage">
        <img class="image" src="../../assets/9.png" alt="some pic" />
      </div></a
    >
    <a href="#"
      ><div class="image-wrapper" id="heroImage">
        <img class="image" src="../../assets/9.png" alt="some pic" />
      </div></a
    >
    <a href="#"
      ><div class="image-wrapper" id="heroImage">
        <img class="image" src="../../assets/9.png" alt="some pic" />
      </div></a
    >
    <a href="#"
      ><div class="image-wrapper" id="heroImage">
        <img class="image" src="../../assets/9.png" alt="some pic" />
      </div></a
    >
  </div>

  <div class="two">
    <a href="#"><h2 class="hr-lines">Design resources</h2></a>
    <a href="#"><h2 class="hr-lines">some other strategy</h2></a>
    <a href="#"><h2 class="hr-lines">project number three</h2></a>
  </div>
</section>

<style lang="scss">
  .section {
    // text-align: center;
    &__4 {
      margin-top: 5rem;
      padding: 0;
      .one {
        // margin-top: -3rem;
        gap: 2rem;
        margin-bottom: -2rem;
        min-height: 50vh;
        display: flex;
        flex-flow: row wrap;
        justify-content: center;
        align-items: center;
        width: 100vw;
        // align-items: flex-end;
        // overflow: hidden;
        .image-wrapper {
          // flex-basis: 1%;
          // position: relative;
          // overflow: hidden;
  
          z-index: -1;
          display: flex;
          align-items: center;
          .image {
            border-radius: 2rem;

            // position: absolute;
            width: 10rem;
            height: 10rem;
            object-fit: cover;
            z-index: -1;
          }
        }
      }
      .two {
        text-transform: uppercase;

        &:after {
          content: " ";
          display: block;
          height: 1px;
          width: 100%;
          position: relative;
          bottom: 0%;
          left: 0;
          background-color: whitesmoke;
        }
        .hr-lines {
          position: relative;

          &:before {
            content: " ";
            display: block;
            height: 1px;
            width: 100%;
            position: absolute;
            top: 0%;
            left: 0;
            background-color: whitesmoke;
          }
        }
      }
    }
  }
</style>
