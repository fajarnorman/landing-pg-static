<template>
	<div class="loading">
		<h2 class="animate">Loading</h2>
	</div>
</template>
<style lang="scss" scoped>
.loading{
	position: fixed;
    width: 100%;
    height: 100%;
    z-index: 101;
    background: #fff;
    top: 0;
    left: 0;
}
.animate {
	display:flex;
	justify-content: center;
	align-items: center;
	height:100%;
	margin: auto;
	font-family: Helvetica, sans-serif, Arial;
	animation: load 1.2s infinite 0s ease-in-out;
	animation-direction: alternate;
	text-shadow: 0 0 1px white;
}
@keyframes load {
    0%{
        opacity: 0.08;
		filter: blur(5px);
		letter-spacing: 3px;
    }
    100%{

    }
}
</style>
