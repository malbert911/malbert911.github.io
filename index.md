---
layout: page
full_logo: true
title: 
subtitle: 
description: Matthew Albert's personal website.
sitemap:
  priority: 1.0
---

<div id="particles-js"></div>

<script src="/assets/css/particles.min.js"></script>

<style>
  @media only screen and (min-width: 600px) {
    .grid-container {
      display: grid;
      grid-gap: 70px;
      grid-template-columns: 2fr 1fr;
      grid-template-rows: auto 1fr;
      grid-template-areas:
      'title image'
      'description image';
    }
    .one {
      grid-area: title;

    }
    .two {
      grid-area: image;
    }
    .three {
      grid-area: description;
    }
  }
  @media only screen and (min-width: 800px) {
    .grid-container {
    grid-template-columns: 3fr 1fr;
    }
  
  }

</style>

<div class="grid-container">
<p id="describe-text" class="one">Hey, my name is Matthew!</p>
<img id="about-img" class="two" src="/assets/img/profile.jpg">
<br>
<p class="three">
This is my personal website, home to some of my projects. Have a look around in <a href="/projects">projects</a> to see them. Check out <a href="/posts">posts</a> to see the same projects in more detail. <a href="mailto:matthew.albert911@gmail.com" target="_blank">Feel free to contact me for any questions!</a></p> 

</div>




<script>
  particlesJS.load('particles-js', 'assets/particles.json', function() {
  console.log('callback - particles.js config loaded');
});
  </script>