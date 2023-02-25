<section class={$$props.class}>
  <div class="one column">
    <div>
      <h5><b> Expandiendo su alcance de mercado </b></h5>
      <p>
        Nuestros expertos lo ayudarán a diseñar soluciones nativas de la nube
        para el futuro. Garantizan una latencia de milisegundos, procesan
        millones de solicitudes por segundo y pueden admitir millones de
        usuarios en cualquier parte del mundo. Podrá ingresar a nuevos mercados
        y llegar a más clientes a medida que su negocio crece sin el costo y el
        dolor de cabeza de reescribir sus aplicaciones.
      </p>
    </div>
    <div>
      <h5><b>Gran elasticidad</b></h5>
      <p>
        Los ingenieros de Armun lo asesorarán sobre cómo escalar su arquitectura
        nativa en la nube para evitar cuellos de botella comunes. Ayudamos a las
        empresas a aumentar o disminuir los recursos en respuesta a los aumentos
        y fluctuaciones del tráfico.
      </p>
    </div>
    <div>
      <h5><b>Seguridad mejorada</b></h5>
      <p>
        Armun es un proveedor de desarrollo de software con certificación ISO.
        Utilizamos las mejores prácticas en seguridad de datos e inteligencia de
        amenazas. Siguiendo el enfoque de DevSecOps, incorporaremos la seguridad
        en cada paso del desarrollo de aplicaciones nativas de la nube para
        garantizar que cumpla con la normativa de la industria.
      </p>
    </div>
  </div>
  <div class="two column">
    <div>
      <h5><b>Tiempo de comercialización más rápido </b></h5>
      <p>
        Llevamos a cabo una planificación rigurosa, diseñamos flujos de trabajo
        eficientes, hacemos uso de la automatización en CI/CD y garantizamos una
        gestión eficaz del proceso de lanzamiento. Todo esto le permitirá
        reducir el tiempo de comercialización de sus aplicaciones nativas de la
        nube sin comprometer la calidad.
      </p>
    </div>
    <div>
      <h5><b>Optimización de costos</b></h5>
      <p>
        Lo ayudaremos a reducir su gasto general en aplicaciones nativas de la
        nube mediante la identificación de recursos mal administrados, la
        eliminación de desperdicios, la reserva de capacidad para mayores
        descuentos y el dimensionamiento adecuado de los servicios informáticos
        para escalar.
      </p>
    </div>
  </div>
</section>

<style lang="scss">
  .section {
    &__5 {
      height: auto;
      // transform: translateY(2.5rem);
      margin-top: 5%;
      align-items: flex-start;
      justify-content: center;
      gap: 6rem;
      flex-wrap: wrap;
      & > * {
        flex-basis: 45%;
        display: flex;
        flex-flow: column;
        gap: 2rem;
        & > * {
          display: flex;
          flex-flow: column;
          gap: 1rem;
        }
      }
      .one {
        justify-content: flex-start;
        // gap: 2rem;
      }
      .two {
        overflow: hidden;
        justify-content: flex-start;
        align-items: start;

        min-height: 50vh;
        max-height: 1000%;
        // width: 50vw;
        // background: center/ contain no-repeat hsla(0, 0%, 93%, 0) url("../../assets/hero_image.jfif");
        justify-content: flex-start;
      }
    }
  }
</style>
