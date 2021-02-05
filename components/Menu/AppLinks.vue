<template>
<div class="menuToggle">


<!-- <img src="@/assets/img/logo2.png" alt="Logo"> -->
    <ul class="nav-list">
        <nuxt-link to="/"><li class="nav-item"></i>Home</li></nuxt-link>
        <nuxt-link to="/services"><li class="nav-item"></i>Boten</li></nuxt-link>
        <nuxt-link to="/contact"><li class="nav-item"></i>Informatie</li></nuxt-link>
        <nuxt-link to="/contact"><li class="nav-item"></i>Contact</li></nuxt-link>
    </ul>

    </div>
</template>

<style scoped>
.nav-item{
  font-size: 24px;
  height: 80px;
  width: 90%;
  border-bottom: 2px solid white;
  padding: 30px 0px;
}

.nav-item a, li{
  color: white;
  text-decoration: none;
}

.menuToggle{
  margin-top: 150px;
}

.nav-item:hover {
  border-bottom: 2px solid #B2495D;
}
.nav-item a:hover, li:hover{
    color: #B2495D;
}

@media (min-width: 750px) {
  .nav-item{
    font-size: 26px;
  }
  .menuToggle{
    margin-top: 180px;
  }
}

/* .navlist
{
  position: absolute;
  width: 300px;
  margin: -100px 0 0 -50px;
  padding: 50px;
  padding-top: 125px;
  background: #ededed;
  list-style-type: none;
  -webkit-font-smoothing: antialiased;
}

.navlist li
{
  padding: 10px 0;
  font-size: 22px;
} */

    /* .nav-list {
        list-style: none;
        padding: 0;
        margin: 0;
        position: absolute;

    }
    .nav-item {
        /* margin: 0 10px; */
        /* height: 50px;
        border-bottom: 2px solid white;
        color: white;
        padding: 14px 16px;
        text-decoration: none;
        font-size: 17px;
        display: block; */
    /* } */
    /* .nav-item a {
        text-decoration: none;
        color: #fefefe;
    }
    .nav-item:hover,
    .nav-item:active{
      background-color: #ddd;
color: black;
    } */
    /* @media (max-width: 767px) {
        .nav-list {
            display: block;
        }
        .nav-item{
            margin-top: 16px;
            margin-bottom: 16px;
        }
    }
    @media (min-width: 768px) {
        .nav-list {
            display: flex;
        }
    } */
</style>
