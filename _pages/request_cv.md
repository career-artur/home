---
layout: archive
title: <center>Request CV</center>
permalink: /request_cv/
author_profile: true
---

{% include base_path %}

<!-- modify this form HTML and place wherever you want your form -->
<form action="https://formspree.io/f/xrbqvvnz" method="POST">
  <label for="name">Your Name:</label>
  <textarea id="name" name="name"></textarea>

  <label for="email">Your Email:</label>
  <input type="email" id="email" name="email">

  <label for="company">Company:</label>
  <textarea id="company" name="company"></textarea>

  <label for="message">Your Message:</label>
  <textarea id="message" name="message"></textarea>

  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>