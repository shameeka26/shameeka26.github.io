<!doctype html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<link rel="stylesheet" type="text/css" href="style.css">
	<title>Tibia - Ship Route Calculator</title>
</head>

<body>
	<section id="form">
		<div id="form-inner">
			<div id="left-col">
				<img src="tibia-logo.png">
				<form>
					<input type="text" name="departure-city" placeholder="miasto startowe" maxlength="25">
					<input type="text" name="arrival-city" placeholder="miasto docelowe" maxlength="25">
					<button>WYSZUKAJ POŁĄCZENIE</button>
				</form>
			</div>
			<div id="right-col">
				<h2>Znalezione połączenia</h2>
				<hr>
				<ul class="routes">
					<li class="best route-row ">
						<ul class="route-inner ">
							<li class="route-number">1</li>
							<li class="route-details"><span class="departureCity">Venore  </span> - <span class="arrivalCity">Carlin</span></li>
							<li class="route-price"><img src="coin.svg">130gp</li>
							
						</ul>
					</li>
					<li class="route-row ">
						<ul class="route-inner ">
							<li class="route-number">2</li>
							<li class="route-details"><span class="departureCity">Venore  </span> - Edron - <span class="arrivalCity">Carlin</span></li>
							<li class="route-price"></li>
							
						</ul>
					</li>
					<li class="route-row ">
						<ul class="route-inner ">
							<li class="route-number">3</li>
							<li class="route-details"><span class="departureCity">Venore  </span> - Thais - <span class="arrivalCity">Carlin</span></li>
							<li class="route-price"></li>
							
						</ul>
					</li>
					<li class="route-row ">
						<ul class="route-inner ">
							<li class="route-number">4</li>
							<li class="route-details"><span class="departureCity">Venore  </span> - Ankrahmun - <span class="arrivalCity">Carlin</span></li>
							<li class="route-price"></li>
							
						</ul>
					</li>
					<li class="route-row ">
						<ul class="route-inner ">
							<li class="route-number">5</li>
							<li class="route-details"><span class="departureCity">Venore  </span> - Lidsadsdasassdsadsssssssssssssssssssberty Bay - Yalahar - <span class="arrivalCity">Carlin</span><</li>
							<li class="route-price"></li>
							
						</ul>
					</li>
					
					
					
					
				</ul>
				
			</div>


		</div>
	</section>








	<script type="text/javascript" src="scripts.js"></script>
</body>

</html>
