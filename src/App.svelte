<script>
  import Header from "./lib/header.svelte";
  import Footer from "./lib/footer.svelte";
  import Section1 from "./lib/section1.svelte";
  import Section2 from "./lib/section2.svelte";

</script>

<body>
  <Header/>
    <main>
      <Section1/>
      <Section2/>
    </main>
    <Footer/>
</body>

<style>
  html{
    overflow: hidden;
  }
  body{
    overflow-y: hidden;
    background: #040D12;
  }
</style>

