<script>
  import Card from "$lib/components/card.svelte";
</script>

<nav>
  <a href="/">Home</a>
  <a href="/about">about</a>
  <a href="/contact">contact</a>
</nav>

<h1>Web1-class</h1>

<p>Welcome to the Home page</p>

<Card name={"Himanshu"} />
<Card name={"Himanshu"} />
<Card name={"Himanshu"} />

<style>
  p {
    color: red;
    font: bold;
    text-align: center;
  }
  h1 {
    color: rgb(255, 145, 0);
    text-align: center;
    background-color: bisque;
  }
  nav {
    padding: 18px 40px;
    text-align: center;
    background-color: rgba(255, 145, 0, 0.308);
  }
</style>
