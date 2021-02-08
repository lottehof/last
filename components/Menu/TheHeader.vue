<!-- <template>
    <header>
      <div class="drawer-toggle" role="button" @click="$store.dispatch('nav/toggleSidebar')">
          <div class="bar"></div>
          <div class="bar"></div>
      </div>

        <div class="brand-name" @click="$store.dispatch('nav/toggleSidebar')">
            <nuxt-link to="/">
              Menu
            </nuxt-link>
        </div>



    </header>
</template>

<script>
    import AppLinks from '~/components/Menu/AppLinks'
    export default {
        components: { AppLinks }
    }
</script>

<style scoped>

    header{
      position: absolute;
      display: flex;
      /* grid-template: 90px / auto 1fr 1fr; */
      align-items: center;
      background-color: transparent;
      background-position: top;
      padding: 0 16px;
      height: 100px;
      width: 100vw;
        /* background-image: url("~assets/img/bg2.jpg");
        background-position: center;
        background-size: cover; */

    }
    header:nth-child{
        justify-self: end !important;
    }
    .app-links{
        justify-self: end;
        display: none;
    }
    .brand-name {
        margin: 0px;
        font-size: 18px;
        margin-right: 20px;
        /* width: 200px; */
         font-family: HelveticaNeue;
    }


    .brand-name a {
        text-decoration: none;
        color: white;
    }
    .drawer-toggle .bar {
        width: 70%;
        height: 2px;
        background-color: white;
    }
    .drawer-toggle {
        display: flex;
        justify-self: start;
        flex-direction: column;
        justify-content: space-around;
        height: 20%;
        width: 25px;
        cursor: pointer;
    }


    @media (min-width: 430px) {
      .logo{
        width: 40%;
        margin-right: 30px;
        height: auto;
        margin-left: auto;
        margin-right: auto;
      }

    }

    @media (min-width: 900px) {
      .logo{
        width: 300px;
        margin-right: 30px;
        height: auto;
        margin-left: auto;
        margin-right: auto;
      }
      .drawer-toggle{
        margin-left: 35px;
      }

    }


    /* @media (min-width: 768px) {
        header{
            padding: 0 64px;
        }
        .drawer-toggle {
            display: block;
            height: 30%;
        }
    } */
</style> -->
