<template>
	<header>
		<div class="container">
            <div class="clearfix">
				<div class="logo" data-aos="fade-down" data-aos-once="true" data-aos-duration="1000">
                    <nuxt-link to="/">
                        <img src="~/assets/images/logo.png" alt="Logo - Jarvis">
                    </nuxt-link>
                </div>
				<div class="hamburger-menu" v-bind:class="{ change: isResponsive }" @click.prevent="isResponsive = !isResponsive">
					<div class="bar1"></div>
					<div class="bar2"></div>
					<div class="bar3"></div>
				</div>
				<div class="mobile-first" v-bind:class="{ active: isResponsive }">
					<div class="menu" data-aos="fade-down" data-aos-once="true" data-aos-duration="1000" data-aos-delay="300">
						<ul class="list-menu">
							<li><a class="menu-anchor" data-attribute="spesifications" href="spesifications">SPESIFIKASI</a></li>
							<li><a class="menu-anchor" data-attribute="locations" href="locations">DEALER</a></li>
							<li><a class="menu-anchor" data-attribute="contactus" href="contactus">KONTAK</a></li>
							<li><a href="#" @click.prevent="FAQTrigger()">BANTUAN</a></li>
						</ul>
					</div>
					<ul class="download-menu" data-aos="fade-down" data-aos-once="true" data-aos-duration="1000" data-aos-delay="500">
						<li class="download"><a href="https://play.google.com/store/apps/details?id=bike.jarvis.android&hl=in" target="_blank" class="button transparent">Download</a></li>
					</ul>
				</div>
            </div>
		</div>
	</header>
</template>

<script>
export default {
	data(){
		return{
			isResponsive: false,
		}
	},
	mounted(){
		document.querySelectorAll('.menu-anchor').forEach(anchor => {
			anchor.addEventListener('click', function (e) {
				e.preventDefault()
				if(document.getElementById(this.getAttribute('href'))){
					document.querySelectorAll('.menu-anchor').forEach(input => {
						input.classList.remove('active')
					})
					e.target.classList.add('active')
					const yourElement = document.getElementById(this.getAttribute('href'))
					const yCoordinate = yourElement.getBoundingClientRect().top + window.pageYOffset
					const yOffset = -100
					window.scrollTo({
						top: yCoordinate + yOffset,
						behavior: 'smooth'
					})
				}
			});
		});
	},
	methods:{
		FAQTrigger(){
			if (window.fcWidget.isOpen() != true) {
				window.fcWidget.open()
			}
		}
	}
}
</script>

