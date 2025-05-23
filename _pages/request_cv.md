---
layout: archive
title: <center>Request CV</center>
permalink: /request-cv/
author_profile: true
---

{% include base_path %}

<!-- modify this form HTML and place wherever you want your form -->
<form
  action="https://formspree.io/f/xrbqvvnz"
  method="POST"
>
  <label>
    Your Name:
    <textarea name="name"></textarea>
  </label>
  <label>
    Your email:
    <input type="email" name="email">
  </label>
  <label>
    Company:
    <textarea name="company"></textarea>
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>