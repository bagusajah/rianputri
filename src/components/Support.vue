<template>
	<div id="support">
		<!-- <h1 class="uk-heading-line uk-text-center uk-h1 uk-padding-small title" uk-scrollspy="cls:uk-animation-slide-top-small"><span>Supported</span></h1> -->
		<h2>Support Us</h2>
		<div class="wrapper">
			<div class="uk-responsive-width uk-visible@l">
				<ul class="uk-list uk-responsive-width">
				 </ul>
			</div>
			<div class="uk-responsive-width uk-hidden@l">
				<ul class="uk-list uk-responsive-width">
					<li></li>
				    <li></li>
				    <li></li>
				</ul>
			</div>

			<p class="copyright">Rian & Putri &copy; 2020</p>
		</div>
	</div>
</template>

<script>
export default {

  name: 'Support',
}
</script>

<style lang="css" scoped>
	#support {
        background-color: #c1ebf7;
    } 
    .wrapper {
    	padding-bottom: 5px;
    }
    .copyright {
    	font-weight: bold;
    }

	@media screen and (max-width: 1024px) {
		li {
			font-size: 14px;
			margin-left: 15px;
			margin-right: 15px;
		}
	}
</style>