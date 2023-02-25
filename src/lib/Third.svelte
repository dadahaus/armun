<section class={$$props.class}>
    <div class="two" />
    <div class="one column">
        <div>
            <p>Cultura y Tecnologias</p>
            <h4>
                Cómo es una transformación digital a través de tecnología Cloud
                Native:
            </h4>
        </div>
        <div>
            <p><b> Voice €40 million to €4 billion</b></p>
            <p>earnings from your own e-commerce platform</p>
        </div>
        <div>
            <p><b> 15 minutes is </b></p>
            <p>how soon a bug fix can be in production</p>
        </div>
        <div>
            <p><b>Go from 4 to 20</b></p>
            <p>deployments a day (in six months)</p>
        </div>
    </div>
</section>

<style lang="scss">
    .section {
        &__3 {
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
            }

            }
            .two {
                overflow: hidden;
                min-height: 70vh;
                max-height: 1000%;
                // width: 50vw;
                background: center/ contain no-repeat hsla(0, 0%, 93%, 0)
                    url("../../assets/third.png");
                justify-content: flex-start;
            }
        }
    }
</style>
