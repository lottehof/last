<template lang="html">
  <footer class="footer">
  <p class="copyrights1">	&#169; Davy &amp; Orsted </p>
  <div class="legal-information">
  <p><a href="#">Terms &amp; Conditions</a></p>
  <p><a href="#">Privacy Statement</a></p>
  <p><a href="#">Business Portal</a></p>
  </div>
  <p class="copyrights2">	&#169; Davy &amp; Orsted </p>
  </footer>

</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
.footer{
  position: relative;
  height: 130px;
  text-align: center;
}
.legal-information > p > a{
  margin: 20px;
  font-family: FuturaStd;
  font-size: 12px;
  font-weight: 500;
  font-stretch: normal;
  font-style: normal;
  line-height: 2.67;
  letter-spacing: 2px;
  color: #acadaf;
  text-decoration: underline;
}
.copyrights1{
  display: none;
}
.copyrights2{
  position: absolute;
  bottom: 0;
  text-align: center;
  width: 100%;
  font-family: FuturaStd;
  font-size: 14px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 2.29;
  letter-spacing: normal;
  color: #97a0a7;
}

@media (min-width: 927px) {
.footer{
  margin-bottom: 20px;
  width: 100%;

}
.legal-information{
  display: flex;
  width: 80%;
  justify-content: center;
  align-items: center;
}

.copyrights2{
  display: none;
}
.copyrights1{
  display: block;
  text-align: left;
  float: left;
  padding-left: 77px;
  font-family: FuturaStd;
  font-size: 14px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 2.29;
  letter-spacing: normal;
  color: #97a0a7;
}

}
</style>
