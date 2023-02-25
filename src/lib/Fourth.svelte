<section class={$$props.class}>
  
  <div class="one column">
      <div>
          <p>Beneficios al implementar</p>
          <h4 class="orange">
            DevOps & SecOps
          </h4>
      </div>
      <div>
          <h5><b> + Productividad y Eficiencia</b></h5>
          <p>Las empresas que han adoptado DevOps tienen un tiempo de entrega 208 veces más rápido y una tasa de fallas de software 7 veces menor en comparación con las empresas que no han adoptado estas metodologías</p>
      </div>
      <div>
          <h5><b>+ Confiabilidad y Seguridad </b></h5>
          <p>La implementación de SecOps puede reducir significativamente el tiempo de detección y respuesta a las amenazas de seguridad, lo que puede minimizar el impacto de los ataques y mejorar la confianza de los clientes

          </p>
      </div>
      <div>
          <h5><b>+ Display surface</b></h5>
          <p>Lorem ipsum dolor sit amet, con

            sectetur adipiscing elit. Mauris
            
            </p>
      </div>
  </div>
  <div class="two" />
</section>

<style lang="scss">
  .section {
      &__4 {
          height: auto;
          // transform: translateY(2.5rem);

          align-items: center;
          justify-content: center;
          gap: 3rem;
          flex-wrap: wrap;
          & > * {
              flex-basis: 45%;
              display: flex;
          }
          .one {
              text-align: left;
              // justify-content: flex-end;
              gap: 2rem;
              & > * {
              display: flex;
              flex-flow: column;
              gap: 0.5rem;
              .orange{
                color: hsla(43, 73, 69, 1)
              }
          }

          }
          .two {
              overflow: hidden;
              min-height: 90vh;
              max-height: 100%;
              // width: 50vw;
              background: center/ contain no-repeat hsla(0, 0%, 93%, 0)
                  url("../../assets/fourth.jpg");
              justify-content: flex-start;
          }
      }
  }
</style>
