---
layout: layouts/page.njk
title: Contact
description: Get in touch with Midland Cycling Club.
permalink: /contact/
---

## Get in Touch

Have a question about the club or our rides? Drop us a message and we'll get back to you.

<form class="contact-form" name="contact" action="/contact/thanks/" method="POST">
  <div class="form-group">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" required>
  </div>
  <div class="form-group">
    <label for="email">Email</label>
    <input type="email" id="email" name="email" required>
  </div>
  <div class="form-group">
    <label for="message">Message</label>
    <textarea id="message" name="message" required></textarea>
  </div>
  <button type="submit" class="btn btn--primary">Send Message</button>
</form>
