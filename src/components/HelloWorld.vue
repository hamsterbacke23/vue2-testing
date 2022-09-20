<template>
  <ul>
    <li><a href="#">Space</a></li>
    <li><a href="#">Space</a></li>
    <li><a href="#">Space</a></li>
    <li>
      <a href="#settings">Settings</a>
      <ul>
        <li><a href="#">Space</a></li>
        <li><a href="#">Space</a></li>
        <li><a href="#">Space</a></li>
      </ul>
    </li>
    <li><a href="#">Space</a></li>
  </ul>
</template>

<style scoped lang="postcss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;500;700&display=swap');

body {
  font-family: 'Roboto';
  padding: 40px;
}

li {
  width: 200px;
  list-style-type: none;
  padding: 0;
  margin: 0 0 20px 0;

  & a {
    border-top: 2px solid #6e6e6e;
    padding-top: 5px;
    display: block;
    text-decoration: none;
    font-weight: 500;
    color: #6e6e6e;

    &:hover,
    &:focus {
      color: #3e3e3e;
      border-color: #3e3e3e;
    }
  }
}

ul {
  margin: 0;
  padding: 0;
  position: relative;

  & ul {
    position: absolute;
  }
}
</style>
