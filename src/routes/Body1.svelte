<script>


</script>

<section>
    <div >
        <p>Шемонаев Сергей</p>
    </div>
    <div>
        <img src="https://sun9-12.userapi.com/impf/38LAR0IkdICOkLg1izwUvh3VuBnN7ZFbEGxHpA/7od8-VqOxBQ.jpg?size=1280x960&quality=96&sign=34bc5ef59442afc90a6e1c5bd959dcaa&type=album">
    </div>

</section>
<div class="animation">
  <h3> Мои Проекты</h3>
    <div class="product">
       <a href="https://codepen.io/Sergey-Shemonaev/pen/LYdYjdb">Пробная верстка</a>
        <a href="https://codepen.io/Sergey-Shemonaev/pen/KKQrYbE">Вертикальные вкладки CSS</a>
        <a href="https://codepen.io/Sergey-Shemonaev/pen/xxYNjmJ">Input</a>
    </div>
</div>

<style>

    section{
        padding: 2em ;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        width: 100%;
    }

    p {
        font-family: 'Rubik Mono One', cursive;
        font-style: italic;
        font-weight: 900;
        font-size: 64px;
        line-height: 67px;
        text-align: center;
        color: #fff;
        /*text-shadow: 10px 10px 30px #8b00e8, -10px -10px 30px #8f0eaf;*/
        -webkit-text-stroke: 2px #fafafa;
        -webkit-text-fill-color: #11a1ea;
        letter-spacing: 5px;
    }
    img{
        width: 40em;
        border-radius: 250%;
        opacity: .9;
        box-shadow: 0 0 10px 10px;
        opacity: .5;

    }
    .animation{
        width: 100%;
        margin: 2em 0;
        font-family:  Monotype Corsiva, cursive;
        font-style: italic;
        font-weight: 900;
        font-size: 4.5em;
        line-height: 45px;
        text-align: center;
        color: #fafafa;
        text-shadow: 10px 10px 30px #5651ea, -10px -10px 30px #525be1;
        -webkit-text-stroke: .1px #d9d9d9;
        -webkit-text-fill-color: #11a1ea;
        letter-spacing: 5px;
    }
    a{
        display: block;
        margin-top: 1em;
        font-size: 1em;
    }

   .product{
        margin-top: 2em;
       position: relative;
       animation:  rotation 10s infinite;
   }


    @-webkit-keyframes rotation {
        from {-webkit-transform: rotateY(0deg);}
        to {-webkit-transform: rotateY(360deg);}
    }

    /*@-keyframes product {*/
    /*    from {transform: rotate(0deg);}*/
    /*    to {transform: rotate(360deg);}*/
</style>
