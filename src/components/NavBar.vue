<template>
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/about">About</a></li> 
            <li><a href="/product">Products</a></li>
            <li><a href="/admin">Admin</a></li>
            <li><a href="/contact">Contact</a></li>
        </ul>
</template>
<script>
export default {
    name: 'NavBar',

}
</script>
<style>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: black;
    text-align: center;
  }
  
  li {
    float: left;
  }
  
  li a {
    display: block;
    color: beige;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }
  
  li a:hover:not(.active) {
    background-color: #111;
  }
  
  .active {
    background-color:red;
  }
</style>