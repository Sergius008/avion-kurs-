<template>
    <header>
        <div class="navigation">
            <div class="top-navigation">
                <span class="material-symbols-outlined">
                    search
                </span>

                <h1>Avion</h1>
                
                <div class="right-navigation">
                    <span class="material-symbols-outlined shopping_cart">
                    shopping_cart
                    </span>

                    <span class="material-symbols-outlined">
                    account_circle
                    </span>
                </div>
            </div>
          
        </div>
    </header>
</template>

<script>
export default {
    name: "HeaderTop",

}
</script>

<style >
.navigation{
    width: 1386px;
    margin: 0 auto;
}
.top-navigation{
    display: flex;
    justify-content: space-between;
    border-bottom: 2px solid #D9D9D9;
    padding: 20px 0 20px 0;
}

h1{
    font-size: 24px;
    color: #22202E;
    font-family: Arial, Helvetica, sans-serif;
}

.shopping_cart{
    margin-right: 16px;
}



.navi-item a{
    text-decoration: none;
    color: #726E8D;
    font-size: 22px;

}
</style>