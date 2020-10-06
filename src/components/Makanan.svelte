<script>
    let data = [1,2,3,4,5,6,7,8];
</script>
<div class="container">
    <div class="row">
        <div class="text-konten">
            <span>MAKANAN</span>
            <a href="">Lihat Semua</a>
        </div>
    </div>
    <div class="konten">
        <div class="row">
            {#each data as i}
                <div class="card col-md-6 col-lg-3 col-xs-6">
                    <div class="card-konten">
                        <img src="img/KERIPIK1.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            
                            <h6>Keripik Pisang Gerigi</h6>
                            <div class="rating">
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                                <i class="fa fa-star"></i>
                            </div>
                            <div class="harga-jual">
                                Rp.21.500
                            </div>
                        </div>
                    </div>
                </div>
            {/each}
      
        </div>
    </div>
</div>

<style>
    .container{
        margin-top: 80px;
    }
    .konten{
        border-radius: 20px;
        border: 2px solid white;
        box-shadow: 0 0 10px grey;
        padding: 20px;
        color: black;
    }
    .card{
        border: none;
    }

    .text-konten{
        margin-bottom: 10px;
    }

    .text-konten span {
        font-family: 'Oswald', sans-serif;
        font-size: 28px;
        margin-left: 20px;
        padding-bottom: 10px;
    }

    .text-konten a {
        font-size: 22px;
        margin-left: 10px;
        color: gold;
    }

    .card-konten{
        margin-bottom: 20px;
        transition: 1s;
    }
    .card-konten img{
        transition: 1s;
        
    }

    .card-konten img:hover{
        border-top-left-radius: 20px;
        border-top-right-radius: 20px;
    }

    .card-konten:hover{
        cursor: pointer;
        transform: scale(1.05);
        box-shadow: 0 0 10px grey;
        border-radius: 20px;
    }

    .card-body{
        text-align: center;
    }

    .card-body .rating{
        color: gold;
    }
</style>