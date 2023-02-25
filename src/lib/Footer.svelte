<footer class="column">
  <div class="one row">
    <h5>technologies we <b>work</b></h5>
    <div class="icons row">
      <div />
      <div />
      <div />
      <div />
      <div />
      <div />
    </div>
  </div>
  <div class="two row">
    <div class="arg column">
      <p><b>Argentina</b> </p>
      <p>Arroyito (CBA)</p>
      <p>CP:X2434</p>
      <p>CUIT: 30-71593728-6</p>
    </div>
   <a class="logo" href="http://"></a>
    <div class="ita column">
      <p><b>Italia</b> </p>
      <p>Savigliano (CN)</p>
      <p>CAP: 12038</p>
      <p>P.IVA 04021830049</p>
    </div>

  </div>
  <div class="three row">
    <h5>San Martin 315 - Piso 1 - Oficina 2 - Arroyito - Cordoba - Argentina - Tel. +54 (03576) 454950 - Email info@armun.net - Politica de privacidad Politica de cookies </h5>
    <a class="mail" href="mailto:"></a>
  </div>
</footer>

<style lang="scss">
  footer {
    position: relative;
    align-items: center;
    // justify-content: space-between;
    height: calc(90vh);
    width: 100vw;
    padding: 4rem;
    gap: 4rem;
    &>*{
      justify-content: center;
      align-items: center;
    }

    .one {
      flex-basis: 50%;
      width: 100%;
      justify-content: space-evenly;
      gap: 1rem;
      flex-flow: nowrap;
      h5 {
        flex: auto;
        font-weight: 200;
        b {
          font-weight: 900;
        }
      }

      .icons {
        flex-basis: 70%;
        width: 100%;
        justify-content: space-evenly;
        gap: 1rem;

        & > * {
          width: 3rem;
          height: 3rem;

          &:nth-child(1) {
            background: center/ contain no-repeat
              url("../../assets/footer_1.png");
          }
          &:nth-child(2) {
            background: center/ contain no-repeat
              url("../../assets/footer_2.png");
          }
          &:nth-child(3) {
            background: center/ contain no-repeat
              url("../../assets/footer_3.png");
          }
          &:nth-child(4) {
            background: center/ contain no-repeat
              url("../../assets/footer_4.png");
          }
          &:nth-child(5) {
            background: center/ contain no-repeat
              url("../../assets/footer_5.png");
          }
          &:nth-child(6) {
            background: center/ contain no-repeat
              url("../../assets/footer_6.png");
          }
        }
      }
    }
    .two {
      width: 100%;
      justify-content: space-around;
      gap: 1rem;

      .logo{
        flex-basis: 30%;
        width: 8rem;
        height: 8rem;
        background: center/ contain no-repeat
              url("../../assets/logo_blanco.png");
      }
    }
    .three {
      text-align: center;

      .mail {
        background: center/ contain no-repeat
              url("../../assets/mail-1.svg");
        width: 5rem;
        height: 5rem;
        // transform: translateY(30%);
      }
    }
  }
</style>
