<script>
    import { onMount } from "svelte";

    let myDiv = null;
    onMount(()=>{
        document.addEventListener('scroll',()=>{
            console.log(myDiv.style.bottom)
            myDiv.style.bottom = (window.scrollY * 3 - 1000)+'px';
            myDiv.style.height = `calc(auto + ${window.scrollY * 400}px)`;
            myDiv.style.opacity = .4;
        });
    })
</script>


<div  bind:this={myDiv}
        class="parallax-container"
        style='bottom:-1000em; opacity : 0; '
>
    <h2>My Skills</h2>
    <section>
        <div>
            <img src="/images/icon_html.png" alt="">
            <span>HTML5</span>
        </div>

        <div>
            <img src="/../src/lib/images/icon_css.png" alt="">
            <span>CSS3</span>
        </div>
        <div>
            <img src="/../src/lib/images/icon_scss.png" alt="">
            <span>SCSS</span>
        </div>
        <div>
            <img src="/../src/lib/images/icon_js.png" alt="">
            <span>Java Script</span>
        </div>
        <div>
            <img src="/../src/lib/images/icon_git.png" alt="">
            <span>Git</span>
        </div>
    </section>

</div>

<style>
    .parallax-container{
        display: flex;
        flex-direction: column;
        align-items: center;
        position: fixed;
        width: 100%;
        padding: 1em;
        background-color:rgba(0, 0, 0, 0.1);;
    }
    h2{
        margin: 1em 0;
        font-family: 'Rubik Mono One', cursive;
        font-style: italic;
        font-weight: 900;
        font-size: 45px;
        line-height: 45px;
        text-align: center;
        color: #fff;
        text-shadow: 10px 10px 30px #5651ea, -10px -10px 30px #525be1;
        -webkit-text-stroke: 2px #fafafa;
        -webkit-text-fill-color: #11a1ea;
        letter-spacing: 5px;
    }
    section{
        width: 100%;
        /*position: absolute;*/
        display: flex;
        justify-content: space-evenly;

    }
    div{
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    span{
        margin: 1em 0;
        font-family: 'Arial';
        color: #ffffff;
    }
    img{

    }
    img:hover{
        transform: scale(1.2 , 1.2);
        transition: .5s linear;
    }


</style>
