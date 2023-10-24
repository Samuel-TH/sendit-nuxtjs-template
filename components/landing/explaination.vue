<template>
    <div class="lp-section" :data-cms-bind="dataBinding">
        <h1 class="section-header">How the Twin Health program works</h1>
        <div class="three-column">
            <div class="how-it-works__content-block">
                <img
                    src="https://assets-global.website-files.com/61bb94aac2044c184bd14b46/64add609a1d003e93fd8109b_TH-BC-7.jpg">
                <p class="step-header">STEP 1</p>
                <h1 class="how_it_work_header">Schedule a free consultation</h1>
                <div class="how_it_work_description">Speak with a Twin Health enrollment advisor who will assess your
                    eligibility and goals, review the Twin
                    Health program and walk you through the steps to enroll.</div>
            </div>
            <div class="how-it-works__content-block">
                <img
                    src="https://assets-global.website-files.com/61bb94aac2044c184bd14b46/64ade07c28dbe916bac3415a_twin-phone-3col-2.png">
                <p class="step-header">STEP 2</p>
                <h1 class="how_it_work_header">Get verified for the program</h1>
                <div class="how_it_work_description">Download the Twin Health app, set up your health profile and complete a
                    lab test to verify that you’re clinically eligible for the program.</div>
            </div>
            <div class="how-it-works__content-block">
                <img
                    src="https://assets-global.website-files.com/61bb94aac2044c184bd14b46/64c31f9827e7e7c97f2256da_Lifestyle_03.jpeg">
                <p class="step-header">STEP 3</p>
                <h1 class="how_it_work_header">Activate your Whole Body Digital Twin<sup>TM</sup></h1>
                <div class="how_it_work_description">Once verified, you'll meet your Twin Health care team through video
                    visits to help you set up your sensors that include a continuous glucose monitor, blood pressure
                    monitor, smart scale and an activity tracker — all at no cost to you.</div>
            </div>
        </div>
        <div class="additional_text">With your app and sensors in place, your Whole Body Digital Twin is
            activated. It sends you <br>daily guidance on actions you can take to safely reduce or eliminate Type 2 diabetes
            medications and lose weight. <br>Your care team works with you and your primary care provider every step of the
            way.
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
    margin-bottom: 0;
    margin-left: auto;
    margin-right: auto;
    padding: 56px 0;
}

.section-header {
    color: #2c2a29;
    font-family: Montserrat, sans-serif;
    font-size: 32px;
    line-height: 38px;
    text-align: center;
    margin-top: 0;
    margin-bottom: 32px;
}

.three-column {
    width: 100%;
    grid-column-gap: 32px;
    grid-row-gap: 32px;
    grid-template-rows: auto;
    grid-template-columns: 1fr 1fr 1fr;
    grid-auto-columns: 1fr;
    padding-left: 0;
    padding-right: 0;
    display: grid;
}

.how-it-works__content-block {
    max-width: 100%;
    text-align: left;
    background-color: #fff;
    border-radius: 0;
    margin-bottom: 32px;
    margin-left: auto;
    margin-right: auto;
    overflow: hidden;
}

img {
    width: 100%;
    border-radius: 8px;
}

.step-header {
    margin-top: 12px;
    margin-bottom: 8px;
    font-family: Montserrat, sans-serif;
    font-size: 16px;
    font-weight: 600;
    line-height: 22px;
    color: #0085ca;
}

.how_it_work_header {
    color: #2c2a29;
    font-family: Montserrat, sans-serif;
    font-size: 24px;
    font-weight: 600;
    line-height: 34px;
    max-width: 100%;
    margin-top: 0;
    margin-bottom: 8px;
}

.how_it_work_description {
    color: #2c2a29;
    font-family: Montserrat, sans-serif;
    font-size: 16px;
    line-height: 26px;
    font-weight: 400;
}

.additional_text {
    color: #2c2a29;
    font-family: Montserrat, sans-serif;
    font-size: 16px;
    line-height: 26px;
    text-align: center;
    margin-top: 16px;
    font-weight: 400;
}
</style>
  