<script>
    let data = [1,2,3,4];
</script>
<div class="container">
    <div class="row">
        <div class="text-konten">
            <span>SERING DILIRIK</span>
        </div>
    </div>

    <div class="konten">
        <div class="row">
            {#each data as i}
                
                <div class="card-section">
                    <div class="card-konten">
                        <img src="img/KERIPIK1.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                
                                <h6>Keripik Pisang Gerigi</h6>
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
        margin-top: 60px;
    }

    .container .konten{
        background-color: salmon;
        /* height: 300px; */
        width: 100%;
        box-shadow: 3px 3px 8px red;
    }

    .text-konten{
        margin-bottom: 10px;
    }

    .text-konten span {
        padding-left: 20px;
        font-family: 'Oswald', sans-serif;
        font-size: 28px;
        padding-bottom: 10px;
    }

    .konten{
        padding: 0 40px;
    }

    .card-section{
        margin: 20px auto;
        width: 22%;
        background-color: rgba(255, 255, 255, 0.77);
        border-radius: 20px;
        border: 1px solid grey;
    }

    .card-konten{
        padding: 10px;
        display: flex;
        flex-direction: column;
    }

    .card-konten img{
        height: 193px;
        border-top-left-radius: 20px;
        border-top-right-radius: 20px;
        object-fit: cover;
    }

</style>