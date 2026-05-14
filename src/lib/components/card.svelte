<script>
  let { name = "Web1-Classwork" } =
    $props();
</script>

<div>
  <img
    src="https://i.fbcd.co/products/resized/resized-750-500/17-e41fcbc1128035669ae1e1cc212f39a2d684dc6e9994260be8615423ab696d1f.jpg"
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
  }
</style>
