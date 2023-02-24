<section class={$$props.class}>
  <h5>We provide quality content for the masses</h5>
  <div class="pin-wrapper">
    <a href="#"><div class="image-wrapper" id="heroImage">
      <img class="image" src="../../assets/9.png" alt="some pic" />
    </div></a>
    <a href="#"><div class="image-wrapper" id="heroImage">
      <img class="image" src="../../assets/1.png" alt="some pic" />
    </div></a>
    <a href="#"><div class="image-wrapper" id="heroImage">
      <img class="image" src="../../assets/10.png" alt="some pic" />
    </div></a>
    <a href="#"><div class="image-wrapper" id="heroImage">
      <img class="image" src="../../assets/3.png" alt="some pic" />
    </div></a>
    <a href="#"><div class="image-wrapper" id="heroImage">
      <img class="image" src="../../assets/4.png" alt="some pic" />
    </div></a>
    <a href="#"><div class="image-wrapper" id="heroImage">
      <img class="image" src="../../assets/5.png" alt="some pic" />
    </div></a>
    <a href="#"><div class="image-wrapper" id="heroImage">
      <img class="image" src="../../assets/6.png" alt="some pic" />
    </div></a>
    <a href="#"><div class="image-wrapper" id="heroImage">
      <img class="image" src="../../assets/7.png" alt="some pic" />
    </div></a>
    
  </div>
</section>

<style lang="scss">
  .section {
    &__2 {
      h5{
        margin-bottom: 18rem;
      }
      // padding: 1rem;
      text-align: center;

      justify-content: center;
      align-items: center;
      height: auto;
      // gap: 6rem;
      // padding: 1rem;
      & > * {
        flex-basis: 50%;
      }

      .pin-wrapper {
        // margin-top: -3rem;
        min-height: 50vh;
        display: flex;
        flex-flow: row wrap;
        gap: 2rem; 
        justify-content: center;
        width: 100vw;
        // align-items: flex-end;
        // overflow: hidden;
      }
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
  }
</style>
