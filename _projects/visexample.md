---
layout: project
title: Lonely Souls
short_desc: That gum you like is going to come back in style.	
full_desc: Complications set in — yes, complications. How many times have we heard 'it's simple'. Nothing is simple. We live in a world where nothing is simple. Each day, just when we think we have a handle on things, suddenly some new element is introduced and everything is complicated once again. What is the secret? What is the secret to simplicity, to the pure and simple life? Are our appetites, our desires undermining us? Is the cart in front of the horse?	
design: this visualization uses wind to signify bedtime; rustling to signify pain; circle to signify circle.
category: Project category
---

<article class="post index" role="article">
  <h1 class="post-title">{{ site.description }}</h1>
  <script>
	function showDetails(which_vis){
		var vis = document.getElementById(which_vis);
		vis.classList.toggle("reveal_details");
	};
  </script>
	<div class="item" id="vis1" onclick="showDetails(this.getAttribute('id'))">
		<img src="../assets/images/cancel_vf_1.png">
		<div class="all_text">
			<div class="short_desc">That gum you like is going to come back in style</div>
			<div class="long_desc">Complications set in — yes, complications. How many times have we heard: 'it's simple'. Nothing is simple. We live in a world where nothing is simple. Each day, just when we think we have a handle on things, suddenly some new element is introduced and everything is complicated once again. What is the secret? What is the secret to simplicity, to the pure and simple life? Are our appetites, our desires undermining us? Is the cart in front of the horse?</div>
			<div class="links">markdown links stuff</div>
			<div class="design">A poem as lovely as a tree:
As the night wind blows, the boughs move to and fro.
The rustling, the magic rustling that brings on the dark dream.
The dream of suffering and pain.
Pain for the victim, pain for the inflicter of pain.
A circle of pain, a circle of suffering.
Woe to the ones who behold the pale horse.</div>
		</div>
	</div>
  </article>
