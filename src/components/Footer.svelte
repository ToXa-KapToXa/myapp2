<script>

</script>

<main>
    <footer>
        <div class="footer">
            <h3 class="footer-title">О нас</h3>
            <p>Магазин поддержанной мебели.</p>
            <ul class="footer-links">
                <li><a href="/">Москва</a></li>
                <li><a href="/">+999-99-99-99</a></li>
                <li><a href="/">email@email.com</a></li>
            </ul>
        </div>
        <div class="footer footer2">
            <h3 class="footer-title">Категории</h3>
            <ul class="footer-links">
                <li><a href="/">Кресла</a></li>
                <li><a href="/">Диваны</a></li>
                <li><a href="/">Шкафы</a></li>
                <li><a href="/">Кровати</a></li>
                <li><a href="/">Столы</a></li>
            </ul>
        </div>
    </footer>
</main>

<style>
    footer {
        background: #15161D;
        color: #B9BABC;
        margin-left: -1%;
        margin-right: -1%; 
        height: 200px; 
        display: flex;
    }

    .footer {
        /* margin-left: 10%; */
        padding-left: 12%;
    }

    .footer .footer-title {
        padding-top: 10px;
        color: #FFF;
        text-transform: uppercase;
        font-size: 18px;
        margin: 0px 0px 10px;
    }

    .footer-links li+li {
        margin-top: 10px;
    }

    .footer-links li a {
        color: #B9BABC;
    }

    .footer-links li a:hover {
        color: #D10024;
    }

    .footer2 {
        padding-left: 30%;
    }
</style>