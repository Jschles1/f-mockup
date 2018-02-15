<template>
  <div class="nav-container">
    <nav>
      <h2>F<span>OWN</span>DERS</h2>
      <ul>
        <li><a href="#signin">Sign in</a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .nav-container {
    background-color: white;

    h2 {
      display: inline;
      color: black;
    }

    span {
      color: skyblue;
    }

    nav {
      width: 95%;
      margin: 0 auto;
      padding: 10px 10px;
      background-color: white;
      color: skyblue;

      ul {
        display: inline;
        li {
          list-style: none;
          float: right;
          line-height: 30px;
          a {
            text-decoration: none;
            color: skyblue;
          }
        }
      }
    }
  }
</style>
