<template>
  <div class="container">
    <header class="flex-container">
        <div class="social-block">
        <ul>
          <li><a href="https://vk.com/thedeadraibbons"><i class="fa fa-vk"></i></a></li>
          <li><a href="https://www.instagram.com/thedeadraibbons/"><i class="fa fa-instagram"></i></a></li>
          <li><a href="https://www.youtube.com/channel/UCShGCQN8WlKt7VeFKa7vnrA"><i class="fa fa-youtube-play"></i></a></li>
        </ul>
      </div>
      <div class="links-block">
        <ul>
        <li>
      <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li>
      <nuxt-link to="/about">About</nuxt-link>
        </li>
        <li>
      <nuxt-link to="/music">Music</nuxt-link>
        </li>
        <li>
      <nuxt-link to="/gallery">Gallery</nuxt-link>
        </li>
        <li>
      <nuxt-link to="/contact">Contact</nuxt-link>
        </li>
</ul>
      </div>
    </header>
    <nuxt/>
    <footer>
    <div class="footer">   
     &copy; {{2018}} by TDR
    </div>
  </footer>
  </div>
</template>

    <style>
    h1, h2 {
      font-family: 'Charmonman', sans-serif
    }
    a{
    color:white
    }

    .container {
      margin: 0 auto;
      width: 1000px
    }
    .fa-facebook:hover {
    color:#3B5998
    }
    .fa-vk:hover {
    color:#4c75a3
    }
    .fa-instagram:hover {
    color:#ffc0cb
    }
    .fa-youtube-play:hover{
    color: #ff0000
    }
    .flex-container {
    display: flex;
    flex-direction: row;
    }

    .social-block, .links-block {
      display: inline-block;
    }

    .social-block > ul > li{
    display: inline-block;
    margin-right: 30px;
    }
    .links-block > ul > li {
    display: inline-block;
    margin-left: 30px
    }
    .links-block > ul > li a {
    text-decoration: none;
    text-transform: uppercase
    }

    .nuxt-link-exact-active {
      color: #27D3B4
    }

    .links-block {
      padding-right: 50px;
    }

    .footer {
      display: inline;
      padding: 1px;
      background-color: #ffffff
}


    </style>

    <script>
    export default {
      data (){
        return
        year:new Date().getFullYear()
      }
    }
    </script>
    

