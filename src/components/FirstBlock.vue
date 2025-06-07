<template>
    <div class="main-conteiner">
        <div class="hero-blocks">
            <div class="left-block">
                <div class="top-content">
                    <span>The furniture brand for the <br>
                        future, with timeless designs</span>
                    <div class="botton-hero">
                        View collection
                    </div>
                </div>

                <div class="bottom-content">
                    <p>A new era in eco friendly furniture with Avelon, the French luxury retail brand <br>
                        with nice fonts, tasteful colors and a beautiful way to display things digitally <br>
                        using modern web technologies.</p>
                </div>
            </div>

            <div class="right-img">
                <img src="../assets/img/Right Image.png" alt="">
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "FirstBlock"
}
</script>


<style>
.main-conteiner{
    width: 1280px;
    margin: 0 auto;
}

.hero-blocks{
    display: flex;
    margin-top: 60px;
    margin-bottom: 60px;
}

.left-block{
    background-color:#2A254B;
    width: 760px;
    height: 584px;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    padding-left: 60px;
}


/* .top-content{
    margin: 60px 0 0 60px;
} */

.top-content span{
    font-size: 32px;
    color: #FFFFFF;
    font-family: "Fira Sans", sans-serif;
    font-weight: 100;
    font-style: normal;
    line-height: 44.8px;
    
}

.botton-hero{
    background-color: #F9F9F926;
    padding: 16px 32px 16px 32px;
    color: #FFFFFF;
    width: 110px;
    margin-top: 41px;
}

.bottom-content p{
    color: #FFFFFF;
}

</style>