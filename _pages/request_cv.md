---
layout: archive
title: <center>Request CV</center>
permalink: /request-cv/
author_profile: true
---

{% include base_path %}

<form action="https://formspree.io/career@schulz-artur.de" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>
  
  <label for="message">Message:</label>
  <textarea id="message" name="message" required></textarea>
  
  <button type="submit">Submit</button>
</form>