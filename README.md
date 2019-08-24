# Onedio-Haber-Sitesi
<!DOCTYPE html>
<html>
<head>
	<title>Bootsrap 4 Entegre</title>
	<meta charset="utf8">
	 <meta name="description" content="Free Web tutorials">
	 <meta name="keywords" content="HTML,CSS,XML,JavaScript">
	 <meta name="author" content="John Doe">
	 <meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

	<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">

	<style type="text/css">
		.reklamyazısı{
			position: relative;
			margin-top:215px;
			color: white;
		}


		@media(max-width: 576px){
			.reklamyazısı{
			position: relative;
			margin-top:75px;
			color: white;
		}

		}

		.reklamyazısısag2{
			position: relative;
			margin-top:60px;
			font-size: 12px;

		}

		.border{
			border-color: grey;
			border:0 0 1px 0;
		}
	</style>


</head>
<body>

<nav class="navbar navbar-expand-lg navbar-light bg-white border">
	<div class="container">
		<a href="#"><img src="onediologo.png"></a>

		<button class="navbar-toggler" data-toggle="collapse" data-target="#onediomenuac"><span class="navbar-toggler-icon"></span></button>

		<div class="collapse navbar-collapse" id="onediomenuac">
			<ul class="navbar-nav">
				<li class="nav-item">
					<a href="#" class="nav-link">GÜNDEM</a>
				</li>

				<li class="nav-item">
					<a href="#" class="nav-link">GALERİLER</a>
				</li>

				<li class="nav-item">
					<a href="#" class="nav-link">VİDEOLAR</a>
				</li>

				<li class="nav-item">
					<a href="#" class="nav-link">TESTLER</a>
				</li>

				<li class="nav-item dropdown">
					<a href="#" class="nav-link dropdown-toggle" data-toggle="dropdown">KATEGORİLER</a>

					<div class="dropdown-menu">
						<a href="#" class="dropdown-item"><i class="fa fa-caret-right mr-2" aria-hidden="true"></i>Onedio Özel</a>
						<a href="#" class="dropdown-item"><i class="fa fa-caret-right mr-2" aria-hidden="true"></i>Türkiye</a>
						<a href="#" class="dropdown-item"><i class="fa fa-caret-right mr-2" aria-hidden="true"></i>Dünya</a>
						<a href="#" class="dropdown-item"><i class="fa fa-caret-right mr-2" aria-hidden="true"></i>Yemek</a>
						<a href="#" class="dropdown-item"><i class="fa fa-caret-right mr-2" aria-hidden="true"></i>Eğlence</a>
						<a href="#" class="dropdown-item"><i class="fa fa-caret-right mr-2" aria-hidden="true"></i>İş Dünyası</a>
						<a href="#" class="dropdown-item"><i class="fa fa-caret-right mr-2" aria-hidden="true"></i>Yaşam</a>
						<a href="#" class="dropdown-item"><i class="fa fa-caret-right mr-2" aria-hidden="true"></i>Teknoloji</a>
					</div>
				</li>

				<a href="#"><img src="yemek.png" class="ml-3" style="height: 35px;"></a>
			</ul>
		</div>

		<form class="form-inline">
			<input type="text" placeholder="Ara"  class="form-control form-control-sm" name="">
			<a href="" style="color: black;"><i style="margin-left: -20px;" class="fa fa-search" aria-hidden="true"></i></a>
			<i class="fa fa-sign-in ml-3" aria-hidden="true"></i><span style="font-size: 14px;" class="ml-1"><a href="#" style="text-decoration: none; color: black;">Giriş Yap</a></span>

			<button type="button" class="btn btn-sm ml-2" style="background-color: #3B5998; color: white; font-size: 12px; border:0px; padding-bottom:5px ; width:130px; height: 30px;">
				<i class="fa fa-facebook mr-1" aria-hidden="true"></i>| Facebook ile Giriş</button>


		</form>
	</div>
</nav>



<div class="container">

	<img class="img-fluid mt-2" src="onedioreklam.PNG" style="width:1110px;">

	<div class="row mt-3">
		<div class="col-md-5">
			<div class="card border-0">	
				<img src="ustsol.PNG">
				<div class="card-img-overlay">
					<h6 class="reklamyazısı"><a href="#" style="color: white; text-decoration: none !important;">Mahkeme Ailenin Bir Ferdi dedi:İtalya'da Hasta Köpeğine Bakmak İsteyen Kadına Ücretli İzin.</a></h6>
				</div>
			</div>	
		</div>
		<div class="col-md-4">
			<div class="card border-0">	
				<img src="ustorta.PNG">
				<div class="card-img-overlay">
					<h6 class="reklamyazısı"><a href="#" style="color: white; text-decoration: none !important;">Mahkeme Ailenin Bir Ferdi dedi:İtalya'da Hasta Köpeğine Bakmak İsteyen Kadına Ücretli İzin.</a></h6>
				</div>
			</div>	
		</div>

		<div class="col-md-3">
			<div class="card border-0 mb-2">	
				<img src="ustsag1.PNG">
				<div class="card-img-overlay">
					<h6 class="reklamyazısı"><a href="#" style="color: white; text-decoration: none !important;">Mahkeme Ailenin Bir Ferdi dedi:İtalya'da Hasta Köpeğine Bakmak İsteyen Kadına Ücretli İzin.</a></h6>
				</div>
			</div>	

			<div class="card border-0">	
				<img src="ustsag2.PNG">
				<div class="card-img-overlay">
					<h6 class="reklamyazısısag2"><a href="#" style="color: white; text-decoration: none !important;">Mahkeme Ailenin Bir Ferdi dedi:İtalya'da Hasta Köpeğine Bakmak İsteyen Kadına Ücretli İzin.</a></h6>
				</div>
			</div>	
		</div>
	</div>	

</div>

<div class="container mt-4">
	<div class="row">
		<div class="col-md-5">
			<h6>Haberler</h6>
			<hr>

			<div class="card border-0">
				<div class="row">
					<div class="col-md-6">
						<img src="in-love.png" style="position: absolute;width: 40px;margin:-15px 0 0 -15px;">
						<img src="haberler1.JPG" style="width: 200px ; ">
					</div>
					<div class="col-md-6">
						<h4 style="font-size: 22px; margin-left: -25px;">İçerik Başlığı Burada</h4>
						<h6 style="font-size: 20px;margin-left: -25px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>
					</div>

					<div class="col-md-6 mt-3">
						<img src="in-love.png" style="position: absolute;width: 40px;margin:-15px 0 0 -15px;">
						<img src="haberler1.JPG" style="width: 200px ; ">
					</div>
					<div class="col-md-6 mt-3">
						<h4 style="font-size: 22px; margin-left: -25px;">İçerik Başlığı Burada</h4>
						<h6 style="font-size: 20px;margin-left: -25px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>
					</div>

					<div class="col-md-6 mt-3">
						<img src="in-love.png" style="position: absolute;width: 40px;margin:-15px 0 0 -15px;">
						<img src="haberler1.JPG" style="width: 200px ; ">
					</div>
					<div class="col-md-6 mt-3">
						<h4 style="font-size: 22px; margin-left: -25px;">İçerik Başlığı Burada</h4>
						<h6 style="font-size: 20px;margin-left: -25px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>
					</div>

					<div class="col-md-6 mt-3">
						<img src="in-love.png" style="position: absolute;width: 40px;margin:-15px 0 0 -15px;">
						<img src="haberler1.JPG" style="width: 200px ; ">
					</div>
					<div class="col-md-6 mt-3">
						<h4 style="font-size: 22px; margin-left: -25px;">İçerik Başlığı Burada</h4>
						<h6 style="font-size: 20px;margin-left: -25px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>
					</div>

					<div class="col-md-6 mt-3">
						<img src="in-love.png" style="position: absolute;width: 40px;margin:-15px 0 0 -15px;">
						<img src="haberler1.JPG" style="width: 200px ; ">
					</div>
					<div class="col-md-6 mt-3">
						<h4 style="font-size: 22px; margin-left: -25px;">İçerik Başlığı Burada</h4>
						<h6 style="font-size: 20px;margin-left: -25px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>
					</div>
				</div>
			</div>
		</div>

		<div class="col-md-4">
			<h6>Galeriler</h6>
			<hr>

			<div class="card border-0">
				<img src="galeriler1.JPG">
				<h4 style="font-size: 22px;margin-left: 20px;">İçerik Başlığı Burada</h4>
				<h6 style="font-size: 20px;margin-left: 20px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>
				<span class="ml-3"><i class="fa fa-facebook" style="color: #3B5998;" aria-hidden="true"></i><small class="ml-2">1.1 b</small><i class="fa fa-whatsapp ml-2" style="color:green;" aria-hidden="true"></i><small class="ml-2">975</small><small class="ml-2" style="color: grey;">1 Ağustos 2019</small></span>
			
					<img src="galeriler1.JPG" class="mt-3">
				<h4 style="font-size: 22px;margin-left: 20px;">İçerik Başlığı Burada</h4>
				<h6 style="font-size: 20px;margin-left: 20px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>
				<span class="ml-3"><i class="fa fa-facebook" style="color: #3B5998;" aria-hidden="true"></i><small class="ml-2">1.1 b</small><i class="fa fa-whatsapp ml-2" style="color:green;" aria-hidden="true"></i><small class="ml-2">975</small><small class="ml-2" style="color: grey;">1 Ağustos 2019</small></span>

					<img src="galeriler1.JPG" class="mt-3">
				<h4 style="font-size: 22px;margin-left: 20px;">İçerik Başlığı Burada</h4>
				<h6 style="font-size: 20px;margin-left: 20px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>
				<span class="ml-3"><i class="fa fa-facebook" style="color: #3B5998;" aria-hidden="true"></i><small class="ml-2">1.1 b</small><i class="fa fa-whatsapp ml-2" style="color:green;" aria-hidden="true"></i><small class="ml-2">975</small><small class="ml-2" style="color: grey;">1 Ağustos 2019</small></span>

					<img src="galeriler1.JPG" class="mt-3">
				<h4 style="font-size: 22px;margin-left: 20px;">İçerik Başlığı Burada</h4>
				<h6 style="font-size: 20px;margin-left: 20px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>
				<span class="ml-3"><i class="fa fa-facebook" style="color: #3B5998;" aria-hidden="true"></i><small class="ml-2">1.1 b</small><i class="fa fa-whatsapp ml-2" style="color:green;" aria-hidden="true"></i><small class="ml-2">975</small><small class="ml-2" style="color: grey;">1 Ağustos 2019</small></span>

					<img src="galeriler1.JPG" class="mt-3">
				<h4 style="font-size: 22px;margin-left: 20px;">İçerik Başlığı Burada</h4>
				<h6 style="font-size: 20px;margin-left: 20px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>
				<span class="ml-3"><i class="fa fa-facebook" style="color: #3B5998;" aria-hidden="true"></i><small class="ml-2">1.1 b</small><i class="fa fa-whatsapp ml-2" style="color:green;" aria-hidden="true"></i><small class="ml-2">975</small><small class="ml-2" style="color: grey;">1 Ağustos 2019</small></span>




			</div>
		</div>

		<div class="col-md-3">
			<h6>Videolar</h6>
			<hr>

			<div class="card border-0">
				<img src="videolar1.JPG">
				<h4 class="mt-3" style="font-size: 22px;margin-left: 20px;">İçerik Başlığı Burada</h4>
				<h6 style="font-size: 20px;margin-left: 20px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>

				<img src="videolar1.JPG">
				<h4 class="mt-3" style="font-size: 22px;margin-left: 20px;">İçerik Başlığı Burada</h4>
				<h6 style="font-size: 20px;margin-left: 20px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>

				<img src="videolar1.JPG">
				<h4 class="mt-3" style="font-size: 22px;margin-left: 20px;">İçerik Başlığı Burada</h4>
				<h6 style="font-size: 20px;margin-left: 20px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>

				<img src="videolar1.JPG">
				<h4 class="mt-3" style="font-size: 22px;margin-left: 20px;">İçerik Başlığı Burada</h4>
				<h6 style="font-size: 20px;margin-left: 20px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>

				<img src="videolar1.JPG">
				<h4 class="mt-3" style="font-size: 22px;margin-left: 20px;">İçerik Başlığı Burada</h4>
				<h6 style="font-size: 20px;margin-left: 20px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>
				i
				<img src="videolar1.JPG">
				<h4 class="mt-3" style="font-size: 22px;margin-left: 20px;">İçerik Başlığı Burada</h4>
				<h6 style="font-size: 20px;margin-left: 20px;"><small>İçerik Detayına Burada Yer Verebilirsiniz...</small></h6>
			</div>
		</div>
	</div>
</div>










<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
<script>
// Example starter JavaScript for disabling form submissions if there are invalid fields
(function() {
	"use strict";
	window.addEventListener("load", function() {
		var form = document.getElementById("needs-validation");
		form.addEventListener("submit", function(event) {
			if (form.checkValidity() == false) {
				event.preventDefault();
				event.stopPropagation();
			}
			form.classList.add("was-validated");
		}, false);
	}, false);
}());
</script>
</body>
</html>
