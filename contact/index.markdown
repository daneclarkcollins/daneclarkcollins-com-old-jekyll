---
layout: page
title: Contact
---

<form action="http://getsimpleform.com/messages?form_api_token=273997e82f972c30cbf7e22d5902d822" method="post">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='{{ site.baseurl }}/contact/you-are-a-great-person.html' />
  <!-- all your input fields here.... -->
  Your Name:<br><input name='name' type='text' /><br>
  Your Message:<br><textarea name="message"></textarea><br>
  <input type='submit' value='Send Message to Dane...' />
</form>