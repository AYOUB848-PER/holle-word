<html lang="en">

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale-1">
	<title>Assignment solution module 2</title>
</head>
<body>
	<header>
	<h1>Our menu</h1>
	</header>
<div class="row">
	<div class="col-lg-4 col-md-6 col-sm-12">
<section class="box">
	<h3 class="title">Chicken</h3>
	<p>Tender and full flavoured, our simple and easy baked chicken breast recipe uses skinless and boneless chicken breasts baked in the oven until golden and caramelised. For extra flavour, garlic butter mixes through the cooked pan juices to serve your chicken drizzled in the best sauce!</p>
</section>
</div>


<div class="col-lg-4 col-md-6 col-sm-12">
	<section class="box1">
		<h3  class="title">Beef</h3>
		<p>This traditional chili couldn't be any easier. Simply brown lean Ground Beef, add in pantry-friendly ingredients and simmer for 20 minutes. The result? A chili that tastes like it's been cooking for hours. This Beef. It's What's For Dinner. recipe is certified by the American Heart Association.</p>
	</section>
</div>

<div class="col-lg-4 col-md-6 col-sm-12">	
	<section class="box2">
		<h3 class="title">Sushi</h3>
		<p>Sushi is vinegared rice topped with other ingredients. Sashimi, which is slices of raw fish alone, is not sushi because it isn’t accompanied with rice. Originally, sushi was fermented fish with rice preserved in salt, and this was a staple dish in Japan for a thousand years until the Edo Period.</p>
	</section>
</div>
</div>
<style>
	* {
	box-sizing: border-box;
}


body {
	font-family: Verdana, Helvetica, sans-serif;
    margin: 0;
    padding: 0;
}

h1 {
    margin-top: 50px;
    padding: 50px;
    text-align: center;

}


section {
	width: 300px;
	border: 20px solid black;
	float: left;
}


.title {

	float: right;
    border-bottom: 2px solid black;
    border-left: 2px solid black;
    margin: 0;
    padding: 0;
    width: 100px;
    text-align: center;
    font-weight: bold;
    height: 30px;
    padding-top: 5px;
}


.box {
	margin: 10px;
	background-color: ivory;
}

.box h3 {
	background-color: mistyrose;
	padding: 2px;
}

.box p {
	padding: 15px;
}


.box1 {
	margin: 10px;
	background-color: ivory;
	
}

.box1 p {
	padding: 15px;
}

.box1 h3 {
	background-color: sandybrown;
	padding: 2px;
}

.box2 {
	margin: 10px;
	background-color: ivory; 
	
}

.box2 p {
	padding: 15px;
}

.box2 h3 {
	background-color: slategray;
	padding: 2px;
}

.row {
	width: 100%;
	border: none;
	text-align: center;
	margin: 5px;
	position: absolute;
	top: 200px;
}

@media (min-width: 992px) {
    .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
        float: left;

    }
    .col-lg-1 {
        width: 8.33%;
    }
    .col-lg-2 {
        width: 16.66%;
    }
    .col-lg-3 {
        width: 25%;
    }
    .col-lg-4 {
        width: 33.33%;
    }
    .col-lg-5 {
        width: 41.66%;
    }
    .col-lg-6 {
        width: 50%;
    }
    .col-lg-7 {
        width: 58.33%;
    }
    .col-lg-8 {
        width: 66.66%;
    }
    .col-lg-9 {
        width: 74.99%;
    }
    .col-lg-10 {
        width: 83.33%;
    }
    .col-lg-11 {
        width: 91.66%;
    }
    .col-lg-12 {
        width: 100%;
    }
}

@media (min-width: 768px) and (max-width: 991px) {
	.col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
        float: left;
}
	.col-md-1 {
        width: 8.33%;
    }
    .col-md-2 {
        width: 16.66%;
    }
    .col-md-3 {
        width: 25%;
    }
    .col-md-4 {
        width: 33.33%;
    }
    .col-md-5 {
        width: 41.66%;
    }
    .col-md-6 {
        width: 50%;
    }
    .col-md-7 {
        width: 58.33%;
    }
    .col-md-8 {
        width: 66.66%;
    }
    .col-md-9 {
        width: 74.99%;
    }
    .col-md-10 {
        width: 83.33%;
    }
    .col-md-11 {
        width: 91.66%;
    }
    .col-md-12 {
        width: 100%;
    }
@media (max-width: 767px) {
.col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
        float: left;
}
.col-md-1 {
        width: 8.33%;
    }
    .col-sm-2 {
        width: 16.66%;
    }
    .col-sm-3 {
        width: 25%;
    }
    .col-sm-4 {
        width: 33.33%;
    }
    .col-sm-5 {
        width: 41.66%;
    }
    .col-sm-6 {
        width: 50%;
    }
    .col-sm-7 {
        width: 58.33%;
    }
    .col-sm-8 {
        width: 66.66%;
    }
    .col-sm-9 {
        width: 74.99%;
    }
    .col-sm-10 {
        width: 83.33%;
    }
    .col-sm-11 {
        width: 91.66%;
    }
    .col-sm-12 {
        width: 100%;
    }
}

</style>
</body>
</html>
