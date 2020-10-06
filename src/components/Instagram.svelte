<script>
    let data = [1,2,3,4,5];
</script>

<div class="container">
    <div class="row">
        <div class="text-konten">
            <span>INSTAGRAM GALLERY</span>
        </div>
    </div>
    <div class="row">
        <div class="instagram-galery">
            {#each data as i }
                <div class="img-card">
                    <img src="img/KERIPIK2.jpg" alt="">
                </div>
            {/each}
        </div>
    </div>
</div>

<style>
    .container{
        background-color: rgba(255,215,0,0.82);
        margin-top: 60px;
        padding-bottom: 10%;;
        box-shadow: 0 0 10px gold;
    }

    .text-konten{
        font-weight: bold;
        font-size: 38px;
        color: white;
        margin: 20px auto;
        letter-spacing: 5px;
        font-family: 'Bangers',cursive;
    }

    .instagram-galery{
        padding: 20px;
        display: flex;
        justify-content: space-evenly;
    }


    .img-card{
        flex: 2;
    }

    .img-card img{
        width: 210px;
        object-fit: cover;
    }

</style>