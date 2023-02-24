
<nav class={$$props.class}>
  <ul>
		<div class="left_nav">
			<a href="/"> <img src="../../assets/behance.svg" alt="logo" srcset="" /> </a>
		</div>
		<div class="center_nav">
			<a href="http://"><li>menu</li></a>
			<a href="http://"><li>work</li></a>
			<a href="http://"><li>contact</li></a>
		</div>
		<div class="right_nav">
			<a href="http://"> <img src="../../assets/behance-2.svg" alt="logo" srcset="" /> </a>
			<a href="http://"><img src="../../assets/mail-1.svg" alt="logo" srcset="" /> </a>
			<a href="http://"><img src="../../assets/dribbble.svg" alt="logo" srcset="" /> </a>
		</div>
	</ul>

</nav>


<style lang="scss">
	nav {
    z-index: 100;
		padding: 2rem;
		position: fixed;
		top: 0rem;
		width: 100%;
		text-transform: uppercase;
		ul {
			display: flex;
			align-items: center;
			justify-content: space-between;
			gap: 5rem;
			.left_nav {
				flex: 1;
				img {
					width: 3rem;
					height: 3rem;
				}
			}
			.center_nav {
				flex: 1;

				display: flex;
				justify-content: space-evenly;
				gap: 1rem;
				// text-transform: uppercase;
				font-weight: 900;
			}
			.right_nav {
				display: flex;
				justify-content: flex-end;
				gap: 1rem;
				flex: 1;
				// gap: 1rem;
				img {
					width: 3rem;
					height: 3rem;
				}
			}
		}
	}
</style>
