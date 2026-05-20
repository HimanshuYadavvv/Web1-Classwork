<script>
  let { name = "Web1-Classwork" } =
    $props();
</script>

<div>
  <img
    src="https://xeyeti.com/wp-content/uploads/2013/08/20130816-220154.jpg"
    alt="turtle"
  />
  <aside>
    <h3>{name}</h3>
    <ul>
      <li>Hobby 1</li>
      <li>Hobby 2</li>
      <li>Hobby 3</li>
    </ul>
 </aside>
</div>

<style>
  div {
    color: blue;
    display: "flex";
    gap: 1em;
    border: 1px solid white;
    margin-bottom: 1em;
    padding: 1em;
    max-width: 400px;
    text-align: center;
    margin: 0.5 auto;
    
  }
  img{
    max-width: 300px;
    
  }
 
</style>
