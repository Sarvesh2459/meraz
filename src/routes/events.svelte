<svelte:head>
	<title>Events | Meraz '22</title>
</svelte:head>
<div class="empty">

</div>
<div class="mains">
	<div class="background">
		<a href="/events/cultural"><img class="img1" src="assets/pronite.png"></a>
		<a href="/events/cultural"><img class="img2" src="assets/cultural.png"></a>
		<a href="/events/cultural"><img class="img3" src="assets/scitech.png"></a>
		<a href="/events/cultural"><img class="img4" src="assets/informal.png"> </a>
	</div>

</div>

<style lang="scss">
	.empty{
		height: 100px;
	}
	.mains{
		position: relative;
		top:25%;
		left:20%;
		margin-bottom: 30px;
	}
	.background{
		position: relative;
		display: flex;
		flex-direction:row;
		width:60vw;
		background-color: white;
		padding: 2px;
		padding-bottom: 1px;
		border-radius: 40px;
	}
	.img1{
		border-radius: 40px 0 0 40px;
	}
	.img4{
		border-radius: 0 40px 40px 0 ;
	}
	img{
		padding: 2px;
		width:100%;
	}
	// .img1{
	// 	position: relative;
	// 	left:0%;
	// }
	// .img2{
	// 	position:relative;
	// 	left:25%;
	// }
	// .img3{
	// 	position:relative;
	// 	left:50%;
	// }
	// .img4{
	// 	position:relative;
	// 	left:75%;
	// }
	.poster{
		object-fit:cover;
	}
	@media (max-width: 900px) {
		.empty{
			height: 200px;

		}
		.background{
			width: 80vw;
			
		}
		.mains{
			left:10%;
		}
	}
</style>
