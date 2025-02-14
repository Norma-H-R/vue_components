<template>

    <nav class="navbar">
      <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/">Home</a></li>
        <li><a href="/">Home</a></li>
        <li><a href="/">Home</a></li>
        <li><a href="/demo">Demo</a></li>
      </ul>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'NavBar',
    props: {
      msg: String
    }
  }
  </script>
  
  <style scoped>
  .navbar {
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: #333;
    padding: 10px 0;
    height: 60px;
  }
  .navbar ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    display: flex;
    color: white;
    justify-content: space-around;
  }
  .navbar li {
    flex: 1;
    text-align: center;
  }
  .navbar a {
    color: white;
    text-decoration: none;
    display: block;
    padding: 10px 0;
  }
  .navbar a:hover {
    text-decoration: underline;
  }
  </style>