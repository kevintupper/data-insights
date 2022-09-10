---
layout: art-splash
title: The Agile Response Team (ART)
classes: wide
permalink: /flexbox/
date: 2022-07-27 07:29:55

feature_row:
  - title: "Engage ART when"
    excerpt: "<ul><li>you need rapid execution</li><li>from a cross-functional team,</li><li>for a solution that is</li><ul><li>strategic,</li><li>competitive,</li><li>or authorized to deploy.</li></ul></ul>"
  - title: "ART delivers"
    excerpt: "<ul><li>solution ideation,</li><li>architecture designs,</li><li>proofs-of-concept,</li><li>minimum viable products,</li><li>digital transformation, and</li><li>cloud optimization.</li></ul>"
  - title: "Have a qualifying project?"
    excerpt: "Tell us about it and let us help you accelerate its delivery."
    url: "https://aka.ms/engageart"
    btn_label: "Engage ART Now!"
    btn_class: "btn--success btn--large align-center"
---

<style>

.container{
    display:flex;
}

.column-1 {
  flex-shrink: 0; /* shrinks to 0 to apply 70% width*/
  flex-basis: 50%; /* sets initial width to 70% */
}

.box {
//  background-color: rgb(245, 215, 160);
  padding: 24px;
 // border-radius: 12px;
 // border: 2px solid rgb(116, 113, 113);
 // margin: 1rem;
 // box-shadow: 1px 1px 1px #000;
}

@media only screen and (max-width: 900px) {
  .container {
      /* it place the items in vertical direction */
    flex-direction: column;
  }

  .box {
    margin: 0 0 1rem;
  }
}
</style>

ART is a cross-functional team of Cloud Solution Architects with deep connections into Microsoft engineering teams and decades of combined experience in delivering secure, reliable, scalable, and cost-optimized cloud solutions.​​​​​​​  


### Our two objectives


<div class="container">
  <div class="column-1 box">
    <b>Help Microsoft's Federal Civilian customers rapidly unlock the mission-value of the cloud.</b>
  </div>
    <div class="column-2 box">
    <b>Help our teammates scale with access to government-aligned demonstrations and presentations.</b>
    </div>
</div>


1. 
2. Help our teammates scale with access to government-aligned demonstrations and presentations.
  
Through rigorous application of agile processes informed by our guiding principles, our team we will help you deliver on the promise of digital transformation.

When you want results -- Engage ART!

{% include feature_row %}










<style>
        .body {
            padding: 0;
            margin: 0;
        }
  
        .Parent {
            display: flex;
            flex-direction: row;
        }
  
        .child1 {
            width: 50%;
            height: 100vh;
            background-color: green;
            text-align: right;
            color: white;
        }
  
        .child2 {
            width: 50%;
            color: green;
            height: 100vh;
        }
        
        /* add media query for growing and shrinking */
        @media (max-width: 600px) {
          .img {
            flex: 1 1 auto;
          }

    </style>

<div class="Parent">
        <div class="child1">
            <h1>Geeksfo</h1>
            <center>
                <h1>Left</h1>
            </center>
        </div>
        <div class="child2">
            <h1>rgeeks</h1>
            <center>
                <h1>RIGHT</h1>
            </center>
        </div>
    </div>