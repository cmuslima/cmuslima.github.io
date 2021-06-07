---
layout: home
title: Awesome Person
permalink: /
navigation: true
navigation_name: Home
description: > # try to keep it the same as _config.yml > description field, which is used as a fallback for pages without description or excerpt.
  The Personal webpage Calarina Muslimani, Graduate Student with the Department of Computing Science at
  the University of Alberta a member of the Intelligent Robot Learning Laboratory.
---

Short description about myself goes here


<button class="tablink" onclick="openPage('Home', this, 'red')">Home</button>
<button class="tablink" onclick="openPage('Research', this, 'green')" id="defaultOpen">Research</button>
<button class="tablink" onclick="openPage('Teaching', this, 'blue')">Teaching</button>
<button class="tablink" onclick="openPage('Outreach', this, 'orange')">Outreach</button>

<div id="Home" class="tabcontent">
  <h3>Home</h3>
  
</div>
<div id="Research" class="tabcontent">
  <h3>Research</h3>
  <p>Some news this fine day!</p>
</div>

<div id="Teaching" class="tabcontent">
  <h3>Teaching</h3>
  <p>Get in touch, or swing by for a cup of coffee.</p>
</div>

<div id="Outreach" class="tabcontent">
  <h3>Outreach</h3>
  <p>Who we are and what we do.</p>
</div>


/* Set height of body and the document to 100% to enable "full page tabs" */
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial;
}

/* Style tab links */
.tablink {
  background-color: #555;
  color: white;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  font-size: 17px;
  width: 25%;
}

.tablink:hover {
  background-color: #777;
}

/* Style the tab content (and add height:100% for full page content) */
.tabcontent {
  color: white;
  display: none;
  padding: 100px 20px;
  height: 100%;
}

#Home {background-color: red;}
#Research {background-color: green;}
#Teaching {background-color: blue;}
#Outreach {background-color: orange;}