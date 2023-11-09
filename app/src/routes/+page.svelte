<body>
  <main>
    <input type="text" placeholder="Search for drink" />
    <br />
    <ul>
      <li>Drink 1: Lorem ipsum dolor sit amet...</li>
      <li>Drink 2: Lorem ipsum dolor sit amet...</li>
      <li>Drink 3: Lorem ipsum dolor sit amet...</li>
    </ul>
  </main>

  <footer>
    <a href="/new">Add a new drink</a>
  </footer>
</body>

<style>
  body {
    display: flex;
    height: 100vh;
    flex-direction: column;
    margin: auto;
  }
  main {
    padding: 1em;
    flex-grow: 1;
    text-align: center;
  }
  input {
    width: 100%;
  }
  ul {
    padding: 3em 1em;
  }
  li {
    padding: 0.5em 0;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }

  footer {
    text-align: center;

    padding: 2em;
  }
</style>
