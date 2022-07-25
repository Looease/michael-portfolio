---
title: Projects.
description: My overview.
tags: projects
layout: layouts/base.njk
# eleventyExcludeFromCollections: true

---
<style>

.container{
    display: flex;
    width: 100%;
    justify-content: space-around;
    font-family: sans-serif;

}

.links{
    width: 90%;
    list-style: none;
    color: #999999;
}

a{
text-decoration: none;
color: #999999;

}
a:visited {
color: #999999;
}

a:hover {
color: #999999;
}

a:active {
color: #999999;
}

.project-link{
    padding-top: 10px;
    padding-bottom: 10px;

}

.image-container{
    width: 70%;
    display: flex;
    flex-wrap: wrap;
}

.image-link {
   float: left;
    width:  300px;
    height: 300px;
    object-fit: cover;
    padding: 1%;
}

@media screen and (max-width: 915px) {
   footer{
    display:none;
   }

   .image-container{
    width: 70%;
   }
   .image-link{
    width: 100%;
   }

}

</style>
 
<main class="container" id="container"> 

<div class="link-container">
<ul class="links">
<li class="project-link"><a href="/">Home</a></li>
<li class="project-link"><a href="/projects">Work</a></li>
<li class="project-link"><a href="/projects/bracket-redesign">Bracket Re-Design</a></li>
<li class="project-link"><a href="/projects/individual-park-design">Individual Park Design</a></li>
<li class="project-link"><a href="/projects/black-and-decker-vaccum-redesign">Black & Decker Vaccum Re-Design</a></li>
<li class="project-link"><a href="/projects/gresham-furniture-design">Gresham Furniture Design</a></li>
<li class="project-link"><a href="/projects/rugby-shoulder-pad-redesign">Rugby Shoulder Pad Re-Design</a></li>
<li class="project-link"><a href="/projects/ventilation-fan-design">Ventilation Fan Design</a></li>
<li class="project-link"><a href="/projects/hiking-micro-generator">Hiking Micro Generator</a></li>
<li class="project-link"><a href="/projects/product-representation">Product Representation</a></li>
<li class="project-link"><a href="/projects/face-mask-design">Face Mask Design</a></li>

</ul>



</div>

<div class="image-container">
<div>

<div >
<a href="/projects/bracket-redesign">
    <img src="../../img/projects/BracketPhoto.png" class="image-link"/>
</a>
</div>

<div class="image-link">
<a href="/projects/individual-park-design">
<img src="../../img/projects/ClimbingFrame.jpg" class="image-link" />
</a>
</div>

<div class="image-link">
<a href="/projects/black-and-decker-vaccum-redesign">
<img src="../../img/projects/Vacuum.png" class="image-link" />
</a>
</div>


<div class="image-link">
<a href="/projects/gresham-furniture-design">
<img src="../../img/projects/GreshamChairFinalRender.png" class="image-link" />
</a>
</div>

<div class="image-link">
<a href="/projects/rugby-shoulder-pad-redesign">
<img src="../../img/projects/ShoulderPadDesign.png" class="image-link" />
</a>
</div>


<div class="image-link">
<a href="/projects/ventilation-fan-design">
<img src="../../img/projects/VentFan.png" class="image-link"/>
</a>
</div>

<div class="image-link">
<a href="/projects/product-representation">
<img src="../../img/projects/NikeBottle.png" class="image-link" />
</a>
</div>

<div class="image-link">
<a href="/projects/face-mask-design">
<img src="../../img/projects/FaceMaskDesign.png" class="image-link" />
</a>
</div>


</main>



