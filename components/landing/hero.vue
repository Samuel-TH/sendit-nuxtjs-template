<template>
    <div class="container lp-section" :data-cms-bind="dataBinding">
        <div class="row lp-hero-banner">
            <div class="col">
                <h1 class="main-headline">Reclaim your health</h1>
                <p class="sub-headline">Life without Type 2 diabetes is possible. Now you can safely
                    reduce or eliminate Type 2 diabetes medications and shed unwanted weight with<br>the Twin Health
                    program. <br><br>Twin Health is a new pilot program* offered by Blue Care Network.</p>
                    <!-- <LandingCta></LandingCta> -->
            </div>
            <div class="col">
                <iframe
                    style="height: 300px; width: 530px"
                    src="https://player.vimeo.com/video/851460585?loop=false&amp;autoplay=false&amp;muted=false&amp;gesture=media&amp;playsinline=true&amp;byline=false&amp;portrait=false&amp;title=false&amp;speed=true&amp;transparent=false&amp;customControls=true"
                    allowfullscreen="true"
                    allow="autoplay; fullscreen; picture-in-picture; encrypted-media; accelerometer; gyroscope"
                    title="Player for Twin Health Member Testimonials" data-ready="true" tabindex="-1"></iframe>
            </div>

        </div>
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
.lp-section {
    max-width: 1200px;
    margin: 56px auto 0;
    padding-left: 0;
    padding-right: 0;
    display: block;
    padding: 56px 0;
}

.lp-hero-banner {
    width: 100%;
    grid-column-gap: 64px;
    justify-content: center;
    align-items: center;
    margin-left: auto;
    margin-right: auto;
    padding: 0 32px;
    display: flex;
}

.main-headline {
    color: #2c2a29;
    text-align: left;
    font-size: 48px;
    font-weight: 600;
    line-height: 64px;
}

.sub-headline {
    color: #2c2a29;
    font-size: 18px;
    font-weight: 400;
    line-height: 28px;
    text-align: left;
    flex: 0 auto;
    display: inline;
}</style>
  