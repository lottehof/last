<template lang="html">
  <div class="total">
    <div class="start">
      <div class="test">
          <img src="@/assets/img/logo2.png" alt="logo" class="logo">

        </div>

    </div>
    <History />
    <AluSloepen />
    <AluSportboot />
    <Information />



    <Instagram />
    <FooterMenu />
    <Footer />





      </div>

</template>

<script>
import History from '@/components/History/History'
import AluSloepen from '@/components/Modellen/AluSloepen'
import AluSportboot from '@/components/Modellen/AluSportboot'
import Instagram from '@/components/Instagram/Instagram'
import FooterMenu from '@/components/Footer/FooterMenu'
import Footer from '@/components/Footer/Footer'
import Information from '@/components/Information/Information'
import TheHeader from '~/components/Menu/TheHeader'
import TheSideNav from '~/components/Menu/TheSideNav'
export default {
  components: {
    History,
    AluSloepen,
    Instagram,
    AluSportboot,
    FooterMenu,
    Footer,
    Information,
  }

}
</script>
<style lang="css" scoped>
.logo{
  position: absolute;
  top: 40px;
  margin-left: auto;
  margin-right: auto;
  width: 150px;
  left: 0;
  right: 0;
  text-align: center;
}
.total{
  width: 100vw;
}
.start{
  /* position: absolute; */
  width: 100vw;
  height: 879px;
  /* top:0; */
  background-image: url("~assets/img/bg2.jpg");
  background-position: center;
  background-size: cover;
}
.test{
  width: 100vw;
  height: 879px;
  /* position: absolute;
  top: 0; */
  background-image: linear-gradient(to bottom, #000000 -7%, rgba(3, 3, 3, 0.99) -6%, rgba(216, 216, 216, 0));
}

@media (min-width: 600px) {
  .logo{
    top: 40px;
    width: 350px;

  }
}


</style>
