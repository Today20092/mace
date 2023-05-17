---
description: 'Striving to create excellence in your fitness journey with all nautral supplementation, intense value, and unrivaled flavor with a kick.'
paige:
  style: |
    #paige-collections,
    #paige-sections,
    #paige-pages {
        display: none;
    }
    #paige-title {
        font-size: fit-content;
    }
title: 'MACE PRE-WORKOUT'
---

<!-- All styling for this page goes here (just like normal .css file) -->
<style>
/* Styling for the H1 Heading (Main Title) */
h1 {
    line-height: 2;
}

/* Style the supplement facts table */
table {
  border-collapse: collapse;
  margin: 50px auto;
  max-width: 100%;
  width: 600px;
  text-align: center;
}

/* table td {
    text-align: left;
    padding-left: 50px;
} */

table th {
  background-color: #f2f2f200;
}

table th, table td {
  border: 1px solid rgba(0, 0, 0, 0);
  padding: 8px;
  padding-left: 50px;
  text-align: left;
  background-color: rgba(0, 0, 0, 0);

}


/* Alternating row colors */
table tr:nth-child(even) {
  /* background-color: #ffffff; */
  color: #00ff55;
}
/* Everything below here affects the ABOUT US Section */

.aboutuscontainer {
  display: flex;
}

.box {
    display: flex;
    width: 40vw;
    height: 20vw;
    margin: 1vw;
    justify-content: center;
    align-items: center;
    border-radius: 12px;
    background-size: cover;
    background-position: center;
}

.newbox {
    display: flex;
    width: 40vw;
    height: 2vw;
    margin: 1vw;
    justify-content: top;
    align-items: center;
    border-radius: 12px;
    background-size: cover;
    background-position: center;
    flex-direction: column;
}

.newbox h2 {
  font-size: 1.5rem;
  font-weight: bold;
}

.newbox p {
  font-size: 1rem;
  color: #555;
}

/* This affects any screen smaller than 768px, it will overide the width/height for .box */
@media (max-width: 768px) {
  .box {
    width: 45vw;
    height: 40vw;
  }
  /* This changes the mobile version to have the correct spacing on the bottom before the next heading section */
  .newbox {
    margin-bottom: 12vw;
  }
}

.rounded-box {
  display: inline-block;
  padding: 5px;
  border-radius: 12px;
  background-color: black;
    color: rgb(255, 255, 255);
    padding-bottom: 6px;
}
/* For the animation of the About Us Section */
.modern-image {
  transition: transform 0.3s;
}

.modern-image:hover {
  transform: scale(1.1);
  overflow: hidden;
}
/* End of about us section */
    </style>

<!-- This is the main image of the page -->
<p>{{% paige/image alt="Person using battleropes in the gym" breakpoints=true class="object-fit-cover rounded-4" fetchpriority="high" height="20rem" loading="eager" process="webp" src="Main-Photo.jpg" width="100%" %}}</p>

<p class="display-5 fw-bold h2 text-center">What is Mace Preworkout?</p>
<!-- This is the main body paragraph -->
<div class="container-fluid">
    <div class="justify-content-center row">
        <div class="col col-auto col-lg-7 px-0">
            <p class="lead text-center">MACE Preworkout is flavored naturally 🍀, is naturally colored 💧, has a hint of stevia ☘️, and is designed to optimize your performance 🏋️ with a kick. </p>
        </div>
    </div>
</div>
<!-- Table of supplements located here -->
<p class="display-5 fw-bold h2 text-center">What's in it?</p>
<!-- This is the table for the supplementation info -->
    <div style="display: flex; justify-content: center; text-align: center;">
        <table>
            <thead>
            <tr>
                <th>Ingredients 💊</th>
                <th>Quantity (mg) ✅</th>
            </tr>
            </thead>
            <tbody>
            <tr>
                <td>B12 (8333% DV)</td>
                <td>20.00mg</td>
            </tr>
            <tr>
                <td>Piperine Powder</td>
                <td>20.00mg</td>
            </tr>
            <tr>
                <td>L-Carnosine</td>
                <td>20.00mg</td>
            </tr>
            <tr>
                <td>L-Histidine</td>
                <td>60.00mg</td>
            </tr>
            <tr>
                <td>Lions Mane Mushroom</td>
                <td>100.00mg</td>
            </tr>
            <tr>
                <td>Caffeine</td>
                <td>150.00mg</td>
            </tr>
            <tr>
                <td>Turmeric Extract</td>
                <td>250.00mg</td>
            </tr>
            <tr>
                <td>Ashwagandha Powder</td>
                <td>350.00mg</td>
            </tr>
            <tr>
                <td>Alpha GPC</td>
                <td>400.00mg</td>
            </tr>
            <tr>
                <td>Taurine</td>
                <td>1000.00mg</td>
            </tr>
            <tr>
                <td>Beta Alanine</td>
                <td>1600.00mg</td>
            </tr>
            <tr>
                <td>Agmatine Sulfate</td>
                <td>3000.00mg</td>
            </tr>
            <tr>
                <td>L-Citrulline DL-Malate 2:1 Powder</td>
                <td>6000.00mg</td>
            </tr>
            </tbody>
        </table>
    </div>

<p class="display-5 fw-bold h2 text-center">What makes it different?</p>
<div class="container-fluid">
    <div class="justify-content-center row">
        <div class="col col-auto col-lg-7 px-0">
            <p class="lead text-center"><mark>We make sure to give you what you need, when you need it:</mark></p>
            <p class="lead text-center" style="margin-top: 30px;">
                💯 Nitric oxide boosters such as Agmatine Sulfate & L-Citrulline.<br>
                💯 Tumeric for antioxidants & cell support.<br>
                💯 Black Pepper extract for increased absorption of supplements.<br>
                💯 Lions Mane Mushroom & Ashwanganda for superior mind to muscle connection.<br>
                💯 L-Carnosine & Hisidine for increased Beta Alanine absorption.<br>
            </p>  
        </div>
    </div>
</div>

<p class="display-5 fw-bold h2 text-center">Who are we?</p>
<div class="container-fluid">
    <div class="justify-content-center row">
        <div class="col col-auto col-lg-7 px-0">
            <div class="aboutuscontainer">
                <div class="box modern-image" style="background-image: url('ayoub.jpg'); background-position: 30% 50%;"></div>
                <div class="box modern-image" style="background-image: url('juan.jpg');"></div>
                <div class="box modern-image" style="background-image: url('mustafa.jpg');  background-position: 50% 50%;"></div>
            </div>
            <div class="aboutuscontainer">
                <div class="newbox">
                    <h2>Ayoub</h2>
                </div>
                <div class="newbox">
                    <h2>Juan</h2>
                </div>
                <div class="newbox">
                    <h2>Mustafa</h2>
                </div>
            </div>
        </div>
    </div>

</div>

<p class="display-5 fw-bold h2 text-center">When will it be ready?</p>
<div class="container-fluid">
    <div class="justify-content-center row">
        <div class="col col-auto col-lg-7 px-0">
            <p class="lead text-center">MACE pre-workout will be ready as fast as you can make it! We are currently taking pre-orders with a one time discount & <strong>limited edition</strong> sticker for our early supporters.</p>
        </div>
    </div>
</div>

<!-- This section adds the icons on the bottom of the page. -->
<div class="column-gap-3 d-flex display-6 justify-content-center mb-3">
    {{< paige/icon class="bi bi-instagram" name="Instagram" url="https://Instagram.com/MacePreworkout" >}}
</div>
