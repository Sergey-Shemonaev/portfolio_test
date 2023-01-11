<script>
    import Header from "./Header.svelte";
    import Footer from "./Footer.svelte";
    import Body1 from "./Body1.svelte";
    import Body2 from "./Body2.svelte";
    import './style.css';

</script>


<div class="wrapper">
    <Header/>

    <section >
        <Body1/>
    </section>

    <section >
        <Body2  />
    </section>
    <Footer/>
</div>




<style>
.wrapper{

}
</style>