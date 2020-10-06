<script>
    let data = [1,2,3,4];
</script>

<div class="container">
    <div class="stack">

        <div class="row">
            <div class="text-content">
                <div class="title">
                    PROMO MENARIK
                </div>
                <div class="sub-title">
                    <p>Lorem ipsum, atau ringkasnya lipsum, adalah teks standar yang ditempatkan
                        untuk mendemostrasikan elemen grafis atau presentasi visual seperti font,
                        tipografi, dan tata letak.</p>
                </div>
            </div>
        </div>
        
        <div class="row">
     
    
            {#each data as i}
                <div class="card col-lg-3 col-md-6">
                    <div class="card-konten">
                        <div class="diskon">
                            <span>20%</span>
                        </div>
                        <img src="img/KERIPIK1.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            
                            <h6>Keripik Pisang Gerigi uenak coy</h6>
                            <div class="harga-coret">
                                Rp. 25.000
                            </div>
                            <div class="harga-jual">
                                Rp.21.500
                            </div>
                        </div>
                        <div class="button-promo">
                           <span>Lihat</span>
                        </div>
                    </div>
                </div>
            {/each}
      
        </div>
    </div>
    <div class="botton-semua">
        <a href="#" class="btn btn-danger">Lihat Semua</a>
    </div>
</div>

<style>
    .container{
        position: relative;
        /* height: 700px; */
        width: 100%;
        /* padding-right: 15px;
        padding-left: 15px;
        margin-right: auto;
        margin-left: auto; */
    }
    .stack{
        box-sizing: border-box;
        padding: 10px 20px;
        border-radius: 20px;
        border:3px solid salmon;
        max-height: max-content;
    }

    .text-content{
        margin: 20px 24%;
    }
    .text-content .title{
        text-align: center;
        font-size: 28px;
        font-weight: bold;
        color: red;
    }
    .text-content .sub-title{
        text-align: center;
    }
    .card{
        border: none;
    }
    .card-konten{
        margin-bottom: 35px;
        box-shadow: 3px 3px 10px #B2ACAC;
        border-bottom-left-radius: 20px;
        border-bottom-right-radius: 20px;
        position: relative;
    }
    .diskon{
        padding: 9px;
        right: 0;
        position: absolute;        
        background-color: rgba(255, 0, 0, 0.4);
        border-bottom-left-radius: 20px;
        border-top-left-radius: 8px;
        border-bottom-right-radius: 8px;
    }

    .diskon span{
        font-size: 12px;
        color: white;
    }

    .card-body{
        margin: 8px;
        padding: 0;
        /* border:1px solid #B2ACAC; */
        border-top: none;
        /* box-shadow: 3px 3px 10px #B2ACAC; */
    }
    .card img{
        border: none;
        width: 100%;
        object-fit: cover;
        /* box-shadow: 1px 1px 5px #B2ACAC; */

    }

    .harga-coret{
        text-decoration: line-through;
    }

    .harga-jual{
        color: red;
        font-size: 20px;
        font-weight: bold;
    }
   
    .button-promo {
        display: flex;
        background-color: #FCBA1E;
        padding: 10px;
        border-bottom-left-radius: 20px;
        border-bottom-right-radius: 20px;
    }

    .button-promo span{
        font-weight: bold;
        letter-spacing: 2px;
        color: white;
        text-transform: uppercase;
        margin: 0 auto;
    }
    .botton-semua{
        border: none;
        /* border-radius: 20px; */
        background-color: #aaa;
        box-shadow: 3px 3px 6px red;
        position: absolute;
        bottom: -10px;
        left: 50%;
        margin-left: -50px;
    }

    
</style>