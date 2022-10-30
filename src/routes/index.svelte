<script>
	import Hero from './_Hero.svelte';
	import 'lite-youtube-embed/src/lite-yt-embed.css';
</script>

<svelte:head>
	<title>Meraz '22</title>
</svelte:head>


<div class="section">

	<!-- <h1>Meraz 22</h1> -->

	<div class="video-container">
		<div class="color-overlay"></div>
		<video  autoplay loop muted>
			<source src="assets/bggg.mp4" type="video/mp4">
		</video>
	</div>
	<img style="display: inline-block" class="newmeraz" src="assets/newmeraz.png" alt="" srcset="">
	<button class="btn third">Register</button>
</div>

<!-- <div class="section1">
    
</div>
<div style="height:200px">
  <video  autoplay loop muted>
    <source src="assets/bggg.mp4" type="video/mp4">
  </video>
</div> -->
  <!-- <Hero /> -->
<!-- <div class="full">
<Hero />
<section class='glimpses'>
	<div class="title">
	<h1 style='font-weight: normal'>Meraz'22 Teaser</h1>
	</div>
	<iframe src="https://www.youtube.com/embed/W0VIHUbZ680" title="" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</section>



<section class='glimpses'>
	<div class="title">
	<h1 style='font-weight: normal'>Meraz'19 Glimpses</h1>
	</div>
	<iframe src="https://www.youtube.com/embed/fjtuMhY1KK8" title="" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</section>

<section class='glimpses'>
	<div class="title">
	<h1 style='font-weight: normal'>Meraz'18 Glimpses</h1>
	</div>
	<iframe  src="https://www.youtube.com/embed/uOQbTb4-ejs" title="" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</section>
</div> -->

<style lang="scss">
// 	.full {
// 		background-color: #040406;
// 	}
// 	section {
// 		height: 100vh;
// 		// padding-top: 75px;
// 		scroll-snap-align: start;
// 		scroll-padding-top: 75px;
// 		margin: auto;
// 		display: flex;
// 		flex-direction: column;

// 		.title {
// 			text-align: center;
// 			color: transparent;
// 			font-family: 'Metal Mania';

// 			letter-spacing: 3px;

// 			font-size: 1.3rem;
// 			background-position: -5px;
// 			h1,
// 			a {
// 				background: -webkit-linear-gradient(gold, gold, red);
// 				background-clip: text;
// 				-webkit-background-clip: text;
// 				-webkit-text-fill-color: transparent;
// 			}
// 			h1 {
// 				font-size: 2rem;
// 			}

// 			display: flex;
// 			margin: 0px 30px;
// 			div {
// 				display: flex;
// 				flex-direction: row-reverse;
// 				align-items: center;
// 				flex-grow: 1;
// 			}
// 		}
// 	}	
// iframe{
// 	margin: 1% auto ;
// 	width: 75vw;
// 	height: 80vh;
// }
// .glimpses{
// 	height: 100vh;
// }

// @media screen and (max-width: 900px) {
// 	iframe{
// 		height: 30vh;
// 		width: 90vw;
// 		margin-top: 5vh;
// 		margin-bottom: 0px;
// 	}
// 	.glimpses{
// 		height: 70vh ;
// 		padding : 0px;
// 	}
// }

.newmeraz{
	width: 80%;
	z-index: 2;
}

.section {
  position: relative;
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}

.section h1 {
  text-align: center;
  font-size: 6rem;
  font-family: "Cookie";
  padding: 20px;
  margin: 15px;
  z-index: 1;
  opacity: 0.7;
}



.video-container {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 1;
}

.color-overlay {
  position: absolute;
  top: 0;
  left: 0;
  background-color: black;
  width: 100%;
  height: 100vh;
  opacity: 0.7;
}

//Colours



// Reset and Layout Styles
html, body {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  background: #2c3e50;
  font-family: 'Montserrat', sans-serif;
  font-size: 16px;
}
body {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  align-items: center;
  align-content: center;
}



 


// Basic Button Style
.btn {
	position: absolute;
	bottom: 20%;
	z-index: 3;
  box-sizing: border-box;
  appearance: none;
  background-color: transparent;
  border: 2px solid red;
  border-radius: 0.6em;
  color: red;
  cursor: pointer;
  display: flex;
  align-self: center;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1;
  margin: 20px;
  padding: 1.2em 2.8em;
  text-decoration: none;
  text-align: center;
  text-transform: uppercase;
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;

  &:hover,
  &:focus {
    color: #fff;
    outline: 0;
  }
}




//BUTTON 3
.third {
  border-color: #3498db;
  color: #fff;
  box-shadow: 0 0 40px 40px #3498db inset, 0 0 0 0 #3498db;
  transition: all 150ms ease-in-out;
  
  &:hover {
    box-shadow: 0 0 10px 0 #3498db inset, 0 0 10px 4px #3498db;
  }
}

.section1{
  position: relative;
  width: 100%;
  height: 130vh;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden; 
  background-image: url("assets/bg3.png");
  background-size: contain;
  background-repeat: no-repeat;
}


</style>
