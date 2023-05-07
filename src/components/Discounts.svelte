<script>
    import products from "./Index.svelte"
</script>

<main>
    
        {#each products as {name, price, namefile, category, neww, old_price, sale, hit}}
        {#if sale}
            <div class="product">
                <div class="product-img">
                    <img src={namefile} alt={name}>
                    {#if (neww && sale)}
                    <div class="product-label">
                        <span class="new">НОВИНКА</span>
                        <span class="sale">{sale}</span>
                    </div>
                    {:else if neww}
                    <div class="product-label">
                        <span class="new">НОВИНКА</span>
                    </div>
                    {:else if sale}
                    <div class="product-label">
                        <span class="sale">{sale}</span>
                    </div>
                    {/if}
                </div>
                <div class="product-body">
                    <p class="product-category">{category}</p>
                    <h3 class="product-name"><a href="/">{name}</a></h3>
                    <h4 class="product-price">{price} ₽
                        {#if old_price}
                        <del class="product-old-price">{old_price}</del>
                        {/if}
                    </h4>
                    <div class="product-rating">
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                    </div>
                </div>
                <div class="add-to-cart">
                    <a href="/"><button class="add-to-cart-btn plus"><img src="./icons/shopping-cart.svg" alt =""/> В корзину</button></a>
                </div>
            </div>
        {/if}
        {/each}
  
</main>

<style>
    main {
    margin-left: 6%;
}

</style>