<script>
    import logo from '$lib/images/svelte_logo_icon.svg' ;
    import github from '$lib/images/github.png';
</script>



<header>
    <div class="corner">
        <a href="https://github.com/sveltejs/kit">
            <img src={logo} alt="GitHub" />
        </a>
    </div>



    <div class="corner">
        <a href="https://github.com/Sergey-Shemonaev?tab=repositories">
            <img src="https://sun1-92.userapi.com/s/v1/if1/wlRNm15g3WxqCHb-QNZKM-i3uU6ZsYA-3z2BjVnM5hNqD3xpWKq5KRmwS_0I0EdlA0w_d_2C.jpg?size=200x200&quality=96&crop=0,37,820,820&ava=1"
                 alt="GitHub" />
        </a>
    </div>
</header>

<style>
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 2em;
        /*position: fixed;*/
        width: 100%;
        /*z-index: 1;*/
        /*box-shadow: 0px 0px 10px 5px rgba(34, 60, 80, 0.2) inset;*/

        /*background-color: #d0a6ff;*/
        /*background-color: #b0b3be;*/
    }

    /*.corner a {*/
    /*    display: flex;*/
    /*    align-items: center;*/
    /*    justify-content: center;*/
    /*    width: 100%;*/
    /*    height: 100%;*/
    /*}*/
    img{
        width: 4em;
        margin: .5em ;
        box-shadow: 0 0 5px 5px ;
        border-radius: 50px;
        transition: linear 1.1s
    }
    img:hover{
        transform: scale(.8);
    }



    /*header:hover{*/
    /*      !*transform: scale(1.01);*!*/
    /*      box-shadow: 0px 0px 15px 10px rgba(34, 60, 80, 0.2) inset;*/
    /*      !*transition: linear 1s;*!*/
    /*      border-radius: 5px;*/
    /*  }*/

    /*.corner {*/
    /*    width: 10em;*/
    /*    height: 10em;*/
    /*}*/

    /*.corner img {*/
    /*    width: 2em;*/
    /*    height: 2em;*/
    /*    object-fit: contain;*/
    /*}*/

    /*nav {*/
    /*    display: flex;*/
    /*    justify-content: center;*/
    /*    --background: rgba(255, 255, 255, 0.7);*/
    /*}*/

    /*svg {*/
    /*    width: 2em;*/
    /*    height: 3em;*/
    /*    display: block;*/
    /*}*/

    /*path {*/
    /*    fill: var(--background);*/
    /*}*/

    /*ul {*/
    /*    position: relative;*/
    /*    padding: 0;*/
    /*    margin: 0;*/
    /*    height: 3em;*/
    /*    display: flex;*/
    /*    justify-content: center;*/
    /*    align-items: center;*/
    /*    list-style: none;*/
    /*    background: var(--background);*/
    /*    background-size: contain;*/
    /*}*/

    /*li {*/
    /*    position: relative;*/
    /*    height: 100%;*/
    /*}*/

    /*li[aria-current='page']::before {*/
    /*    --size: 6px;*/
    /*    content: '';*/
    /*    width: 0;*/
    /*    height: 0;*/
    /*    position: absolute;*/
    /*    top: 0;*/
    /*    left: calc(50% - var(--size));*/
    /*    border: var(--size) solid transparent;*/
    /*    border-top: var(--size) solid var(--color-theme-1);*/
    /*}*/

    /*nav a {*/
    /*    display: flex;*/
    /*    height: 100%;*/
    /*    align-items: center;*/
    /*    padding: 0 0.5rem;*/
    /*    color: var(--color-text);*/
    /*    font-weight: 700;*/
    /*    font-size: 0.8rem;*/
    /*    text-transform: uppercase;*/
    /*    letter-spacing: 0.1em;*/
    /*    text-decoration: none;*/
    /*    transition: color 0.2s linear;*/
    /*}*/

    /*!*a:hover {*!*/
    /*!*    color: var(--color-theme-1);*!*/
    /*!*}*!*/
</style>
