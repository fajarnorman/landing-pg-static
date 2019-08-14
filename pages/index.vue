<template>
	<div class="wrapper-content">
		<section id="hero-section" class="hero-section">
			<div class="container">
				<div class="description-hero">
					<h1 data-aos="fade-right" data-aos-duration="1000" data-aos-once="true" data-aos-delay="200">
						Ride bike. <br>
						Have fun. <br>
						Feel good.
					</h1>
					<a data-aos="fade-right" data-aos-duration="1000" data-aos-once="true" data-aos-delay="300" href="#" @click.prevent="infoLengkap('info')" id="info-lengkap" class="button button-orange">Info Lengkap</a>
				</div>
				<div class="image-hero">
					<img data-aos="zoom-in" data-aos-duration="1000" data-aos-once="true" data-aos-delay="400" src="~/assets/images/img-sepeda.png" alt="Jarvis eBike">
				</div>
			</div>
		</section>
		<section id="info" class="info-ebike content-padding">
			<div class="container container-custom">
				<div class="why-ebike">
					<h1 class="title" data-aos="fade-up" data-aos-duration="1000" data-aos-once="true" data-aos-delay="200">Kenapa harus sepeda listrik?</h1>
					<p data-aos="fade-up" data-aos-duration="1000" data-aos-once="true" data-aos-delay="300">Sepeda listrik membuat anda sampai tujuan lebih cepat dan lebih ekonomis serta berbuat baik untuk dunia!</p>
				</div>
				<div class="list-info-ebike">
					<ul class="clearfix">
						<li data-aos="fade-right" data-aos-duration="1000" data-aos-once="true" data-aos-delay="400">
							<span>.01</span>
							<h4>Ramah Lingkungan</h4>
							<p>Dengan menggunakan sepeda listrik, konsumsi energi yang dibutuhkan lebih sedikit dibanding dengan kendaraan bermotor.</p>
						</li>
						<li data-aos="fade-right" data-aos-duration="1000" data-aos-once="true" data-aos-delay="700">
							<span>.02</span>
							<h4>Efisien & Minim Perawatan</h4>
							<p>Jarvis dirancang untuk penggunaan sehari-hari dengan menggunakan material yang berkualitas agar tahan lama selama bertahun-tahun.</p>
						</li>
						<li data-aos="fade-right" data-aos-duration="1000" data-aos-once="true" data-aos-delay="1000">
							<span>.03</span>
							<h4>Ekonomis</h4>
							<p>Berkendara dengan Jarvis dapat mengurangi biaya transportasi anda. Anda tidak perlu membayar banyak uang parkir dan biaya BBM.</p>
						</li>
					</ul>
				</div>
			</div>
		</section>
		<section id="spesifications" class="spec-container content-padding bg-grey">
			<div class="container container-custom">
				<div class="spec-list">
					<h1 class="title" data-aos="fade-up" data-aos-duration="1000" data-aos-once="true" data-aos-delay="200">Spesifikasi</h1>
					<ul>
						<li data-aos="fade-up" data-aos-duration="1000" data-aos-once="true" data-aos-delay="400">
							<span>.01</span>
							<h5>Motor</h5>
							<div class="value">350 watt</div>
						</li>
						<li data-aos="fade-up" data-aos-duration="1000" data-aos-once="true" data-aos-delay="600">
							<span>.02</span>
							<h5>Baterai</h5>
							<div class="value">36V, 12Ah</div>
						</li>
						<li data-aos="fade-up" data-aos-duration="1000" data-aos-once="true" data-aos-delay="800">
							<span>.03</span>
							<h5>Kecepatan Maksimum</h5>
							<div class="value">30 Km/hr</div>
						</li>
						<li data-aos="fade-up" data-aos-duration="1000" data-aos-once="true" data-aos-delay="800">
							<span>.04</span>
							<h5>Jarak Maksimum</h5>
							<div class="value">30 Km</div>
						</li>
						<li data-aos="fade-up" data-aos-duration="1000" data-aos-once="true" data-aos-delay="800">
							<span>.05</span>
							<h5>Beban Maksimum</h5>
							<div class="value">150 Kg</div>
						</li>
						<li data-aos="fade-up" data-aos-duration="1000" data-aos-once="true" data-aos-delay="800">
							<span>.06</span>
							<h5>Ukuran Ban</h5>
							<div class="value">14" x 2.125"</div>
						</li>
					</ul>
				</div>
				<span class="jarvis-text-spec">JARVIS</span>
				<img data-aos="fade-left" data-aos-duration="1000" data-aos-once="true" data-aos-delay="200" class="img-spec" src="~/assets/images/img-sepeda-big.png" alt="Jarvis eBike Big">
			</div>
		</section>
		<section id="locations" class="locations content-padding">
			<div class="container container-custom">
				<div class="locations-head">
					<h1 class="title" data-aos="fade-up" data-aos-duration="1000" data-aos-once="true" data-aos-delay="200">Lokasi Dealer</h1>
					<p data-aos="fade-up" data-aos-duration="1000" data-aos-once="true" data-aos-delay="300">Temukan dealer Jarvis di kota terdekat</p>
				</div>
				<ul class="locations-list clearfix" data-aos="fade-up" data-aos-duration="1000" data-aos-once="true" data-aos-delay="400">
					<li><a>Kab. Karawang </a></li>
					<li><a>Kab. Garut </a></li>
					<li><a>Kab. Cianjur</a></li>
					<li><a>Bandung </a></li>
					<li><a>Pekalongan</a></li>
					<li><a>Kab. Batang</a></li>
					<li><a>Kab. Brebes</a></li>
					<li><a>Cirebon </a></li>
					<li><a>Kab. Indramayu </a></li>
					<li><a>Jakarta</a></li>
					<li><a>Palembang </a></li>
					<li><a>Malang</a></li>
					<li><a>Tangerang </a></li>
				</ul>
			</div>
		</section>
		<section id="contactus" class="contactus content-padding">
			<div class="container container-custom">
				<div class="contact-us-content">
					<div data-aos="zoom-in" data-aos-duration="1000" data-aos-once="true" data-aos-delay="200">
						<h1 class="title white">Hemat berkendara dengan Jarvis</h1>
						<p>Hubungi CS kami untuk informasi lebih lanjut</p>
						<a href="https://wa.me/6285288777313" target="_blank" class="button button-orange-white">Kontak Kami</a>
						<div class="sosmed">
							<ul>
								<!-- <li class="facebook">
									<a href="#"><img src="~/assets/images/icon-fb.svg" alt="icon-facebook"></a>
								</li>
								<li class="twitter">
									<a href="#"><img src="~/assets/images/icon-twitter.svg" alt="icon-twitter"></a>
								</li> -->
								<li class="instagram">
									<a target="_blank" href="https://www.instagram.com/jarvis_indonesia/"><img src="~/assets/images/icon-instagram.svg" alt="icon-instagram"></a>
								</li>
								<li class="youtube">
									<a target="_blank" href="https://www.youtube.com/channel/UCwmKsBZPWCMEBRG0qol-zFg?view_as=public"><img src="~/assets/images/icon-yt.svg" alt="icon-yt"></a>
								</li>
							</ul>
						</div>
					</div>
				</div>
			</div>
		</section>
	</div>
</template>

<script>
import CryptoJS from 'crypto-js'

export default {
	data(){
		return{
			dataLocationsStore: ""
		}
	},
	head: {
		title: 'Jarvis eBike',
		meta: [
			{ hid: 'description', name: 'description', content: 'Ride bike, Have fun, Feel good' },
			{ hid: 'keywords', name: 'keywords', content: 'eBike, Sepeda Listrik, Bike, Sepeda, Jarvis' },
			{ hid: 'author', name: 'author', content: 'Willyanto Wijaya S' },
			{ hid: 'opengraph', name: 'og:title', property: 'og:title', content: 'Jarvis eBike' },
			{ hid: 'robot', name: 'robots', content: 'index, follow' }
		]
	},
	mounted(){
		window.addEventListener('scroll', this.handleScroll);
	},
	destroyed () {
		window.removeEventListener('scroll', this.handleScroll);
	},
	methods:{
		handleScroll (event) {
			// Any code to be executed when the window is scrolled
			if(window.pageYOffset >= 50){
				document.querySelector('header').classList.add('fixed')
			}else{
				document.querySelector('header').classList.remove('fixed')
			}
		},
		infoLengkap(val){
			const yourElement = document.getElementById(val)
			const yCoordinate = yourElement.getBoundingClientRect().top + window.pageYOffset
			const yOffset = -100
			window.scrollTo({
				top: yCoordinate + yOffset,
				behavior: 'smooth'
			})
		}
	}
}
</script>
