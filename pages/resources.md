---
title: Resources
permalink: /resources/
---

<style>
/*--------------------------------------------------------------
DAVID: START OF ISSUES PAGE CARDS FLEXBOX LAYOUT AND STYLES
--------------------------------------------------------------*/
/* refrain from using pure img selector as it changes the MSE logo size */

#resources-container > div > div > a > img {
    display: block;
    border: 0;
    max-width: 180px;
    max-height: auto;
    padding: 1em;
    border-radius: 15px 15px 0px 0px;
}

.card {
    flex: 1 0 500px;
    box-sizing: border-box;
    margin: 1em 0.5em;
    background: white;
    margin-bottom: 1em;
    border: 0.13em solid rgba(0,0,0,.1);
    border-radius: 15px;
    /* box-shadow: 2px 2px 6px 0px  rgba(0,0,0,0.3); */
}

.card a {
    color: inherit;
    text-decoration: none; /* no underline */
}

.card p,
.card-content h5 {
    padding: 1em;
    margin-top: 0.5em;
    margin-bottom: .5em;
    /* font-weight: bold; */
    color: inherit;
    text-decoration: none;
}

.card:hover {
    transition: all 0s ease-out;
    box-shadow: 0px 4px 8px rgba(38, 38, 38, 0.2);
    top: -4px;
    border: 2px solid #cccccc;
    background-color: white;
}

.card a:hover {
    color: black;
    text-decoration: none; /* no underline */
}

/* Flexbox stuff */

.cards {
    display: flex;
    flex-wrap: wrap;
    margin: 0 auto;
    /* padding: 0 1em; */
    text-align: center;
 }

@media screen and (min-width: 40em) {
  .card {
    max-width: calc(50% -  1em);
  }
}

@media screen and (min-width: 60em) {
  .card {
    max-width: calc(33% - 1em);
  }
}

@media screen and (min-width: 52em) {
  .img {
    max-width: 52em;
  }
}

@media screen and (max-width : 480px) {
	.card { 
    max-width: 100%; }
}

/*--------------------------------------------------------------
DAVID: END OF ISSUES PAGE CARDS FLEXBOX LAYOUT AND STYLES
--------------------------------------------------------------*/
</style>

<div id="resources-container">
<h1 style="text-align:center"><b>Resources</b></h1>
<div class="cards">
    <div class="card">
        <a href="/resources/key-environmental-statistics.pdf" target="_blank">  
            <div class="card-content">
            <h5>Key Environmental Statistics 2020</h5>
            </div>
          <img src="/images/key-environmental-statistics.png" alt="" style="width:300px;">
        </a>
    </div>
    <div class="card">
        <a href="/resources/zero-waste-masterplan.pdf" target="_blank">  
            <div class="card-content">
            <h5>Zero Waste Masterplan</h5>
            </div>
        <img src="/images/zero-waste-masterplan.png" alt="" style="width:max-content;">
<!-- <p>The Zero Waste Masterplan sets a new waste reduction target for Singapore – to reduce the waste sent to Semakau Landfill each day by 30% by 2030. This will help to extend Semakau Landfill’s lifespan beyond 2035, when it is estimated to reach capacity. Find out what other efforts we are pursuing to build climate, resource and economic resilience in Singapore!</p> -->
        </a>
    </div>
    <div class="card">
        <a href="/resources/climate-action-plan.pdf" target="_blank">  
            <div class="card-content">
                <h5> Climate Action Plan (2020) </h5>
            </div>
          <img src="/images/cap2020.png" alt="" style="width:300px;">
        </a>
    </div>
    <div class="card">
        <a href="/resources/capmitigation.pdf" target="_blank">  
            <div class="card-content">
                <h5> Climate Action Plan (Mitigation) </h5>
            </div>
          <img src="/images/climate-action-plan.jpg" style="width:300px;">
        </a>
    </div>
    <div class="card">
        <a href="https://www.nccs.gov.sg/docs/default-source/publications/a-climate-resilient-singapore-for-a-sustainable-future.pdf" target="_blank">  
            <div class="card-content">
                <h5>Climate Action Plan (Adaptation)</h5>
                <!-- The latest publications of Singapore’s Climate Action Plan provides an update and summary of Singapore’s mitigation and adaptation plans. It sets out how Singapore intends to reduce greenhouse gas emissions and increase our energy efficiency to meet our 2030 climate pledge, and how Singapore may be affected by climate change and our strategy to prepare for them. -->
            </div>
        <img src="/images/climate-action-plan2.png" alt="" style="width:300px;"> 
        </a>
    </div>
    <div class="card">
        <a href="/resources/capsummary.pdf" target="_blank">  
            <div class="card-content">
                <h5> Climate Action Plan (Summary) </h5>
            </div>
          <img src="/images/capsummary.png" alt="" style="width:300px;">
        </a>
    </div>
    <div class="card">
        <a href="/resources/ssb.pdf" target="_blank">  
            <div class="card-content">
                <h5>Sustainable Singapore Blueprint</h5>
            </div>
        <img src="/images/ssb-logo.jpeg" style="width:300px;">
        </a>
    </div>
    <div class="card">
        <a href="https://www.towardszerowaste.gov.sg/resources/" target="_blank">  
            <div class="card-content">
                <h5>Towards Zero Waste (Infographics, Videos)</h5>
            </div>
        <img src="/images/towards-zero-waste.png" alt="" style="width:300px;">
        </a>
    </div>
    <div class="card">
        <a href="/resources/environmentally-friendly-events-guidelines.pdf" target="_blank">  
            <div class="card-content">
                <h5>Guide for Environmentally-Friendly Events</h5>
            </div>
        <img src="/images/events-resources.png" alt="" style="width:300px;">
        </a>
    </div>
    <div class="card">
        <a href="https://www.nea.gov.sg/corporate-functions/resources/educational-materials/posters" target="_blank">  
            <div class="card-content">
                <h5>NEA Educational Materials on the Environment</h5>
            </div>
        <img src="/images/nea-resources-poster.png" alt="" style="width:300px;"> 
        <p style="text-align: center; font-size: 0.8em;">e.g. Infographics & Posters on Climate Action, Energy, Dengue, etc</p>
        </a>
    </div>
    <div class="card">
        <a href="https://www.pub.gov.sg/getinvolved/schools/resources/" target="_blank">  
            <div class="card-content">
                <h5>PUB Resources for Schools</h5>
            </div>
        <img src="/images/pub-resources.png" alt="" style="width:300px;"> 
        </a>
    </div>
    <div class="card">
        <a href="https://www.sfa.gov.sg/tools-and-resources" target="_blank">  
            <div class="card-content">
                <h5>SFA Resources & Tools</h5>
            </div>
        <img src="/images/sfa-resources.png" alt="" style="width:300px;"> 
        </a>
    </div>
    <div class="card">
        <a href="https://www.cgs.gov.sg/resources" target="_blank">  
            <div class="card-content">
                <h5>Clean & Green Singapore</h5>
            </div>
        <img src="/images/cgs-resources.jpeg" style="width:300px;">
        <p style="text-align: center; font-size: 0.8em;">Posters, Infographics, Educational Guides</p>
        </a>
    </div>
    <div class="card">
        <a href="https://www.nea.gov.sg/corporate-functions/resources" target="_blank">  
            <div class="card-content">
                <h5>NEA Resources</h5>
            </div>
        <img src="/images/nea-resources.png" alt="" style="width:300px;">
        <p style="text-align: center; font-size: 0.8em;">Posters, Infographics, Educational Guides</p>
        </a>
    </div>
    <div class="card">
        <a href="https://www.nea.gov.sg/our-services/waste-management/3r-programmes-and-resources/waste-minimisation-and-recycling" target="_blank">  
            <div class="card-content">
                <h5>3R Guidebooks</h5>
            </div>
        <img src="/images/3r-resources.png" alt="" style="width:300px;">
        <p style="text-align: center; font-size: 0.8em;">For implementing programmes in hotels, industrial estates, offices, malls, & events</p>
        </a>
    </div>
    <div class="card">
        <a href="https://data.gov.sg/" target="_blank">  
            <div class="card-content">
                <h5>Statistics from Data.gov.sg</h5>
            </div>
        <img src="/images/data-resources.png" alt="" style="width:300px;">
        </a>
    </div>
</div>
<!-- container end dic -->
</div>
