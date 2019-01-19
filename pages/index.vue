<template>
	<section class="container" >
		<div class="course_container">
			<div class="course_info">
				<div class=course_before>
					<h3>NO ESPERES 
						<span>para ser </span>
					</h3>
					<img src="http://tinyimg.io/i/bjXYH1M.png" alt="">
				</div>
				<figure class="course_student" >
					<img src="http://tinyimg.io/i/mYfAUBb.png" alt="">

				</figure>
				<div class="course_after">
					<div class="course_img" >
						<img width="170" src="http://tinyimg.io/i/YLJReoQ.png" alt="">
						<img src="http://tinyimg.io/i/pOxBnPj.png" alt="">	
					</div>
					<p>Carrera profesional de</p>
					<h3>Gestión</h3>
					<h4>Logística</h4>
					<img class="course_certification" src="http://tinyimg.io/i/CQ9YZXe.png" alt="">
				</div>
			</div>
			<div class="course_form-container">
				<h3>Déjanos tus datos y participa en nuestro evento.</h3>
				<img src="http://tinyimg.io/i/dHq74Yq.png" alt="">
				<v-form class="course_form" >
					<v-text-field
						label=""
						placeholder="Nombres"
						required
					></v-text-field>
					<v-text-field
						placeholder="Apellidos"
						required
					></v-text-field>
					<div class="form_double-input">
						<v-text-field
							placeholder="Teléfono / Celular"
							required
						></v-text-field>
						<v-text-field
							placeholder="Correo"
							required
						></v-text-field>
					</div>
					<v-textarea
						placeholder="Mensaje"
					></v-textarea>
					<v-checkbox
						class="form_checkbox"
						label="¿Autoriza el uso de sus datos?"
					></v-checkbox>
					<v-btn  style=" background-image: url('http://tinyimg.io/i/hbnrYPg.png')"  class="form-btn"> </v-btn>
				</v-form>
				<img class="footer_logo" src="http://tinyimg.io/i/fIu0lZH.png" alt="">
				<p>Av. San Felipe 650 - Jesús María - Lima</p>
				<p>Teléf. 219 1711 - 219 1712 - 219 1718 - 219 1851</p>
				<p>informes@icam.edu.pe</p>
				<em>powered by  <a target="_blank"  href="http://exe.pe/">exe.pe</a> </em>
			</div>
		</div>
	</section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>
<style lang="sass" >
.course_certification
	margin-top: 130px
	position: relative
	z-index: 5
.form-btn
	background-size: cover
	width: 250px
	height: 55px
	box-sixing: border-box
	margin: 0
	.v-btn__content
		font-size: 27px
		font-family: 'Gobold High'
.form_double-input
	.v-input
		&:first-child
				margin-right: 10px
	.v-input__slot
		margin-bottom: 0 !important
.course_form
	::-webkit-input-placeholder  /* Chrome/Opera/Safari */
		color: pink
	::-moz-placeholder  /* Firefox 19+ */
		color: pink
	:-ms-input-placeholder  /* IE 10+ */
		color: pink
	:-moz-placeholder  /* Firefox 18- */
		color: pink
	.v-input
		padding-top: 0
	input
		background: #fff
		max-height: 45px
		height:  45px
		padding: 0 15px
	textarea
		background: #fff
		padding: 15px
.form_double-input
	display: flex
.course_form-container
	background: #083e8c
	width: 515px
	padding: 50px
	box-sixing: border-box
	.v-input__slot
		margin-bottom: 0
	em
		font-size: 12px
		color: #fff
		display: block
		margin-top: 35px
		text-transform: uppercase
		font-style: normal
		a
			color: #fff
			text-decoration: none
	p
		margin: 0
		font-size: 12px
		color: #fff
	h3
		font-weight: normal
		color: #fff
		font-size: 30px
		text-align: center
		font-family: 'Gobold'
		margin-bottom: 15px
		line-height: 35px
	> img
			margin-bottom: 30px
.course_container
	width: 1670px
	display: flex
	justify-content: center
	margin: auto
.course_img
	display: flex
	flex-direction: column
	margin-bottom: 80px
	img
		margin: 0 0 0 auto
.container
  margin: 0 auto
  min-height: 900px
  display: flex
  align-items: center
  text-align: center
  background-size: cover
  padding: 0
.course_before
	color: #fff
	h4
		text-align: left
		font-size: 50px
		font-family: 'Gobold High'
		color: #fff20a
	h3
		font-weight: normal
		text-align: left
		font-size: 50px
		font-family: 'Gobold'
		line-height: 45px
	span
		display: block
		font-size: 30px
	img
		margin-left: -10px
.course_info
	display: flex
	position: relative
	width: 1040px
	justify-content: space-between
	min-height: 900px
	padding-top: 50px
	margin-right: 120px
.course_after
	text-align: right
	color: #fff
	p
		font-size: 17px
		font-family: 'Raleway'
		font-weight: 600
	h3,
	h4
		font-weight: normal
		font-family: 'Lemon/Milk'
	h3
		font-size: 27px
	h4
		font-size: 60px
		line-height: 60px
.course_student
	position: absolute
	left: 0
	right: 0
	margin: auto
	bottom: 0px
.form_checkbox
	margin-top: 0
	padding: 0 15px
	label
		color: #fff !important
		font-size: 13px !important
		font-family: 'Raleway'
		font-weight: 600
.footer_logo
	margin-top: 60px
</style>
