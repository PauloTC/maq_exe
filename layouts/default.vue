<template>
    <v-app  style="background-image: url('http://tinyimg.io/i/dYcgWbr.png')" >
		<v-content>
			<header class="header">
				<div class="header-container">
					<a href="#">
						<img src="http://tinyimg.io/i/Dm9qmWO.png" width="280"  alt="">
					</a>
					<nav class="header-nav" >
						<a href="">Nosotros</a>
						<a href="">Alumno</a>
						<a href="">Contacto</a>
						<a href="">Libro de reclamaciones</a>
						<a href="">Consulta comprobantes</a>
					</nav>
				</div>
			</header>
			<ul  class="submenu" >
				<li>
					<a href="">HOME</a>
				</li>
				<li>
					<a href="">CARRERAS</a>
				</li>
				<li>
					<a href="">CERTIFICACIONES</a>
				</li>
				<li>
					<a href="">GALAERIA</a>
				</li>
				<li>
					<a href="">Convenios</a>
				</li>
			</ul>
        	<nuxt />
		</v-content>
    </v-app>
</template>

<style lang="sass" >
.header
	background: #0063af
.submenu
	padding: 0
	display: flex
	background: #f8a602
	justify-content: center
	height: 45px
	li
		list-style: none
		display: flex
		align-items: center
		&:last-child
				padding-right: 0
				a
					&:after
							display: none
	a
		text-decoration: none
		color: #fff
		text-transform: uppercase
.header-container
	display: flex
	justify-content: space-between
	align-items: center
	height: 105px
	max-width: 1200px
	margin: auto
.header-nav,
.submenu
	a
		position: relative
		transition: all 0.25s
		padding: 0 15px
		&:after
				content: ""
				height: 15px
				width: 1px
				display: block
				background: #fff
				position: absolute
				right: 0
				top: 0
				bottom: 0
				margin: auto
.header-nav
	display: flex
	align-items: center
	a
		color: #fff
		text-decoration: none
		text-transform: uppercase
		position: relative
		&:hover
				color: #fffb03
		&:last-child
				padding-right: 0
				&:after
						display: none
.application
	background-size: cover !important
	min-height: 900px
	padding: 0 !important
html
	font-size: 16px
	word-spacing: 1px
	-ms-text-size-adjust: 100%
	-webkit-text-size-adjust: 100%
	-moz-osx-font-smoothing: grayscale
	-webkit-font-smoothing: antialiased
	box-sizing: border-box
*,
*:before,
*:after
	box-sizing: border-box
	margin: 0

</style>
