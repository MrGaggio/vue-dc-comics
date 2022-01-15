<template>
  <div class="container">
    <div class="logo">
      <img src="../assets/img/dc-logo.png" alt="" />
    </div>
    <div class="navbar">
      <ul>
        <li>
          <a href="">CHARACTERS</a>
        </li>
        <li>
            <a href="">COMICS</a>
        </li>
        <li>
            <a href="">MOVIES</a>
        </li>
        <li>
            <a href="">TV</a>
        </li>
        <li>
            <a href="">GAMES</a>
        </li>
        <li>
            <a href="">COLLECTIBLES</a>
        </li>
        <li>
            <a href="">VIDEOS</a>
        </li>
        <li>
            <a href="">FANS</a>
        </li>
        <li>
            <a href="">NEWS</a>
        </li>
        <li>
            <a href="">SHOP</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>

export default {
    name: 'Header',
    components: {
        
    }
}
</script>

<style lang="scss">
    .container {
        display: flex;
    }
    .navbar {
        display: flex;
        margin-left: 330px;
        align-items: center;
    }
    ul {
        list-style: none;
        display: flex;
        
        li a {
        display: block;
        font-size: 12px;
        text-decoration: none;
        font-family: "Greta Sans Medium","Greta Sans Regular",Arial,sans-serif;
        font-weight: 600;
        padding: 1em;
        transition: all 0.6s;
        color: #464652;
        }

    }
</style>

