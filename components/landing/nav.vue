<template>
    <div class="nav-bar" :data-cms-bind="dataBinding">
        <div class="logo-container">
            <img class="logo bcn-logo"
                src="https://assets-global.website-files.com/61bb94aac2044c184bd14b46/64c2ef6853bfe9e1f0e78f83_BCN_logo%20wo%20dislcaimer_all%20blue_rgb%20(1).png">
            <img class="logo"
                src="https://assets-global.website-files.com/61bb94aac2044c184bd14b46/64c2f18b3a6f4b4cce3a0db0_Twin%20Health%20Primary%20Logo%20(4).png">
        </div>
        <div class="nav-headline">Life without Type 2 diabetes is possible</div>
        <!-- <LandingCta></LandingCta> -->
    </div>
</template>
<script>
   export default {
      props: [
         'block','dataBinding'
      ]
   }
</script>

<style scoped>
.nav-bar {
    z-index: 100;
    height: auto;
    clear: none;
    background-color: #f6f6f6;
    align-content: stretch;
    justify-content: space-around;
    align-items: center;
    padding: 8px 5%;
    font-family: Inter, sans-serif;
    font-size: 18px;
    display: flex;
    position: -webkit-sticky;
    position: sticky;
    bottom: auto;
}

.logo-container {
    text-align: left;
    flex: none;
    justify-content: flex-start;
    align-self: center;
    align-items: center;
    margin-top: 20px;
    margin-bottom: 20px;
    display: flex;
}

.logo {
    height: 36px;
}
.bcn-logo {
    height: 55px;
    border-right: 1px solid #979797;
    margin-right: 10px;
    padding-right: 10px;
    display: block;
}
.nav-headline {
    color: #25282a;
    text-align: center;
    font-family: Inter, sans-serif;
    font-size: 20px;
    font-weight: 600;
    line-height: 26px;
}
.nav-cta {
    color: #fff;
    font-family: Inter, sans-serif;
    width: 174px;
    height: auto;
    text-align: center;
    flex: 0 auto;
    order: 1;
    justify-content: center;
    align-items: center;
    padding-top: 14px;
    padding-bottom: 14px;
    font-weight: 600;
    display: flex;

    background-color: #0085ca;
    border-radius: 32px;
}
</style>
  