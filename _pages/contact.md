---
layout: splash
permalink: /contact/
title: "Contact"
excerpt: "Preferred methods of sending your questions, inquires, messages, and love letters to me."
---

<form id="form" onchange="mail(this)">
  <label>Name</label>
  <div class="">
    <input class="form-control" name="name" type="text">
  </div>

  <label>Email address<span class="color-red">*</span></label>
  <div class="">
    <input class="form-control" name="email" type="text">
  </div>

  <div class="col-md-8 col-md-offset-0">
    <textarea rows="4" placeholder="Message" name="activities" class="form-control"></textarea>
  </div>

  <div class="col-md-8 col-md-offset-0">
    <textarea rows="6" class="form-control" name="comment" placeholder="Comment"></textarea>
  </div>
  <p><a id="send" class="btn btn-primary">Create Message</a></p>
</form>
