<script>
    // import email from '$lib/images/Email.png'
    // // import whatsap from '$lib/images/whatsapp.svg'
    // import telega from '$lib/images/telegram.svg'
    const tel = '+7-(900)-908-72-**';


</script>


<footer>
    <div>Contacts</div>
    <div>
        <button>
            <img src="https://c7.uihere.com/files/391/694/382/iphone-email-box-computer-icons-logo-email.jpg">
            Shemonaev2011@mail.ru
        </button>

        <button>  <img src="https://img01.kupiprodai.ru/122021/1639647595698.png">  {tel} </button>
        <button>  <img src="https://watch-shop24.ru/wp-content/uploads/2020/08/2-telega_master-500x500.jpg">   {tel} </button>

    </div>
</footer>


<style>
    div{
        margin-top: 2em;
    }
     footer{
         /*background-color: rgba(208, 198, 198, 0.1);*/
         margin-top: 1em;
         text-align: center;
         box-shadow: 0px 0px 10px 5px rgba(34, 60, 80, 0.1) ;
         border-radius: 5px;
         color: #0591d3;
     }
     img{
         width: 3.5rem;
         padding: 0 1em;
         border-radius: 200%;
     }
     button{
         background: rgba(208, 198, 198, 0);
         border: none;
         margin: 5px;
         display: flex;
         align-items: center;
         transition: linear 200ms;
     }
     button:hover{
         cursor: pointer;
         transform: scale(1.1);
     }
     div{
         display: flex;
         justify-content: space-evenly;
     }
     a{
        display: flex;
         align-items: center;
     }
</style>