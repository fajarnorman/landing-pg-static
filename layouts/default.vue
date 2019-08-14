<template>
	<div>
		<nav-header />
		<nuxt />
		<nav-footer />
	</div>
</template>

<script>
import NavHeader from '~/components/NavHeader.vue'
import NavFooter from '~/components/NavFooter.vue'

export default {
	components: {
		NavHeader, NavFooter
	},
	mounted(){
		// window.fcWidget.init({
		// 	token: "dfdd9fa0-084a-4e3f-8ae7-e082cd8c7c83",
		// 	host: "https://wchat.freshchat.com"
		// });
	},
	methods:{
		// getLocation() {
		// 	navigator.permissions.query({
		// 		name: 'geolocation'
		// 	}).then(function(result) {
		// 		if(result.state == 'granted'){
		// 			alert(result.state)
		// 		}else if(result.state == 'prompt'){
		// 			alert(result.state)
		// 			if("geolocation" in navigator) {
		// 				navigator.geolocation.getCurrentPosition(function(position) {
		// 					console.log(position)
		// 				});
		// 			}
		// 		}else if(result.state == 'denied'){
		// 			alert(result.state)
		// 		}
		// 		result.onchange = function() {
		// 			alert(result.state)
		// 		}
		// 	});
		// },
		// showPosition(position) {
		// 	console.log("Latitude: " + position.coords.latitude +
		// 	"<br>Longitude: " + position.coords.longitude)
		// }
	}
}
</script>
