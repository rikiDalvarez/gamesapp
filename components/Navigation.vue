<template>
	<header class="navbar">
		<img src="../../FilmDalvarez_ID_visual/DA-logo-white.svg" weidth="50" height="50">
				<!-- <Logo><nuxt-link to="/" class="brand"></nuxt-link></Logo> -->
							<nav>
								<ul>
									<li><nuxt-link to="/about">about</nuxt-link></li>
									<li><nuxt-link to="/contact">contact</nuxt-link></li>
								</ul>
							</nav>
		</header>
</template>
<script>
import Logo from "./Logo"
export default {
	components: {
		Logo
	},
	
}
</script>
<style>

.container__navbar{
	height: 200px;
}
nav{
	width: 800px;
}
img{
	height: 120px;
	width: auto;
}
header{
	display: flex;
	justify-content: space-between;
}
header nav ul{
	position: relative;
	background-color: gold;
}
ul{
	display: flex;
	justify-content:flex-end;
	margin:auto;
	padding:auto;
	
}

	/* .navbar{
		display: inline-block;
		grid-template-columns: 10px 20px auto 20px 20px 10px;
		width: 100%;
		height: 100px;

	} */
	div.navbrand{
		display:inline-block;
	}
	.navbrand{
  display:inline-block;
  flex-wrap:wrap;
  background-color:#ffffffaa;
  padding:0 10%;
  justify-content:space-between;
  box-shadow:0 0 10px #00000077;
  backdrop-filter:blur(5px);
}

header.navbar{
	background-color:#59D25D;
}

	
</style>