---
layout: default
title: Contact
permalink: /contact/
comments: false
published: true
image: assets/images/pg_opengraph_thumb.jpg
---

<style>
.cta-contact {
  display:none;
}
</style>

<div class="article-post">
<p class="label mb-0">Let's connect</p>
<h1 class="mb-0">Need help with a project?</h1>
<p class="mt-1">If you have a project you need some help with, or would just like to connect, I'd be happy to hear from you. You can use the form below or contact me directly at <a href="mailto:mrpatrickgerman@gmail.com">mrpatrickgerman@gmail.com</a>.</p>

<form action="https://formspree.io/f/xqkggpwa" method="POST">    
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    
<input class="btn btn-dark" type="submit" value="Send">
</form>
<br>
<hr>
</div>

<div class="text-center mt-4 pt-1">
<h2 class="mt-5">Past Projects</h2>
</div>

<!-- Showreel -->
{% include showreel-modal.html %}


<!-- Projects: Media Card -->
<div class="row project-listing">
  {% assign projects = site.projects | sort: 'date' | reverse %}
  {% for project in projects %}
       {% include project-mediacard.html %}
  {% endfor %}
</div>

<!-- End projects -->
