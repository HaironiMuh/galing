<style>
	.navbar{
		background-color: white;
		/* background-color: aqua; */
		box-shadow: 3px 3px 10px #FABD0D;
	}

	.search-form{
		margin-left: 20px;
		display: flex;
	}

	.input-search{
		/* background-color: red; */
		flex: 5;
		padding: 0 10px;
		height: 41px;
		border: 1px solid rgba(204, 203, 203, 0.76);
		border-top-left-radius: 20px;
		border-bottom-left-radius: 20px;
		width: 600px;
	}

	/* .form-search input:focus{
		border: 0 solid white;
        outline: none;
    } */
	.input-search input{
		width: 100%;
		background-color: transparent;
		line-height: 41px;
		border: 0 solid transparent;
        outline: none;
    }

	.search-icon{
		width: 50px;
		border: 1px solid rgba(204, 203, 203, 0.76);
		border-top-right-radius: 20px;
		border-bottom-right-radius: 20px;
		margin: auto;
		height: 41px;
		background-color: rgba(224, 224, 224, 0.74);
		display: flex;
	}

	.search-icon i{
		margin: auto;
		color: white;
	}

	.nav-item .nav-link{
		font-family: 'Bebas Neue', cursive;
		color: #FF0045;
		font-size: 24px;
	}
</style>


<nav class="navbar navbar-expand-lg fixed-top">
	<div class="container">
		<a class="navbar-brand" href="#">
			<img src="img/brand.png" height="70px" alt="">
		</a>

		<!-- Form Search -->
		<!-- <form class="form-inline my-2 my-lg-0"> -->
		<form class="search-form">
			<div class="input-search">
				<input type="search" placeholder="Cari Produk ..." aria-label="Search">
			</div>
			<div class="search-icon">
				<i class="fa fa-search"></i>
			</div>
			<!-- <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button> -->
		</form>
		

		<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
		<span class="navbar-toggler-icon"></span>
		</button>
		
		<div class="collapse navbar-collapse" id="navbarSupportedContent">
		
		<ul class="navbar-nav ml-auto">
			
			<li class="nav-item active">
			<a class="nav-link" href="#">Beranda <span class="sr-only">(current)</span></a>
			</li>
			<li class="nav-item dropdown">
			<a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
				Produk
			</a>
			<div class="dropdown-menu" aria-labelledby="navbarDropdown">
				<a class="dropdown-item" href="#">Action</a>
				<a class="dropdown-item" href="#">Another action</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="#">Something else here</a>
			</div>
			</li>
			<li class="nav-item active">
				<a class="nav-link" href="#">Hubungi Kami <span class="sr-only">(current)</span></a>
			</li>
		</ul>
		
		</div>
	</div>
  </nav>