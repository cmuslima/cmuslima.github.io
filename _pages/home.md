---
layout: home
title: Awesome Person
permalink: /
navigation: true
navigation_name: Home
description: > # try to keep it the same as _config.yml > description field, which is used as a fallback for pages without description or excerpt.
  The Personal webpage of Awesome Person, Graduate Student with the Department of Computing Science at
  the University of Alberta a member of the Intelligent Robot Learning Laboratory.
---

Write an extended autobiography here. It's your opportunity to show off your research, goals and accomplishments.

You can use Markdown syntax to create sections, links and place images in your content.   


<button class="tablink" onclick="openPage('Home', this, 'red')">Home</button>
<button class="tablink" onclick="openPage('News', this, 'green')" id="defaultOpen">News</button>
<button class="tablink" onclick="openPage('Contact', this, 'blue')">Contact</button>
<button class="tablink" onclick="openPage('About', this, 'orange')">About</button>

<div id="Home" class="tabcontent">
  <h3>Home</h3>
  
</div>

<div id="News" class="tabcontent">
  <h3>News</h3>
  <p>Some news this fine day!</p>
</div>

<div id="Contact" class="tabcontent">
  <h3>Contact</h3>
  <p>Get in touch, or swing by for a cup of coffee.</p>
</div>

<div id="About" class="tabcontent">
  <h3>About</h3>
  <p>Who we are and what we do.</p>
</div>
