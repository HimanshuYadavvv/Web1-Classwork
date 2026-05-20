<script>
  let { name = "Web1-Classwork" } = $props();
</script>

<div>
  <img
    src="https://static.wikia.nocookie.net/pyruslords/images/7/77/Pikachu.png/revision/latest?cb=20131216222538"
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

<div>
  <img
    src="https://cdn.pixabay.com/photo/2021/12/26/17/31/pokemon-6895600_1280.png"
    alt="kid"
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
    color: rgb(248, 163, 4);
    display: flex;
    gap: 1em;
    border: 1px solid white;
    margin-bottom: 1em;
    padding: 1.5rem;
    max-width: 500px;
    text-align: center;
    margin: 2rem auto;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
    border: 2px solid #ccc;
    border-radius: 12px;
    background: rgb(114, 11, 11);
  }
  img {
    max-width: 300px;
  }
</style>
