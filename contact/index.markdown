---
layout: page
title: Contact
description: "Contact Dane Clark Collins using this simple form."
---

<form action="http://getsimpleform.com/messages?form_api_token=273997e82f972c30cbf7e22d5902d822" method="post" class="contact">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='{{ site.url }}/contact/you-are-a-great-person.html' />
  <!-- all your input fields here.... -->
  <label>Your Name:</label>
  <input name='name' type='text' />
  <label>Your Message:</label>
  <textarea name="message"></textarea><br>
  <input type='submit' value='Send Message to Dane...' class="button">
</form>
