<script>

</script>

<main>
    <nav class="navigation">
        <div id="responsive-nav">
            <ul class="main-nav nav navbar-nav">
                <li class="first"><a href="/">Главная</a></li>
                <li><a href="/">Скидки</a></li>
                <li><a href="/">Кресла</a></li>
                <li><a href="/">Диваны</a></li>
                <li><a href="/">Шкафы</a></li>
                <li><a href="/">Кровати</a></li>
                <li><a href="/">Столы</a></li>
            </ul>
        </div>
    </nav>
</main>

<style>
.navigation {
    margin-left: -1%;
    margin-right: -1%;
  background: #FFF;
  border-bottom: 2px solid #E4E7ED;
  border-top: 3px solid #D10024;
}

.main-nav {
    margin-top: 1%;
    margin-bottom: 1%;
    display: flex;
}

.first {
    padding-left: 13%;
}

.main-nav>li+li {
  margin-left: 30px;
  margin-left: 5%;
}

.main-nav>li>a {
  padding: 20px 0px;
  color: rgb(73, 73, 73);
}

.main-nav>li>a:hover, .main-nav>li>a:focus, .main-nav>li.active>a {
  color: #D10024;
  background-color: transparent;
}

.main-nav>li>a:after {
  content: "";
  display: block;
  width: 0%;
  height: 2px;
  background-color: #D10024;
  -webkit-transition: 0.2s all;
  transition: 0.2s all;
}

.main-nav>li>a:hover:after, .main-nav>li>a:focus:after, .main-nav>li.active>a:after {
  width: 100%;
}

</style>