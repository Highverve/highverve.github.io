---
title: Contact
layout: default
filename: contact.md
---

<style>
input
{
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  box-sizing: border-box;
  
  font-family: "Helvetica Neue", sans-serif;
  border: 2px solid skyblue;
  border-radius: 4px;
}
input:focus
{
  background-color: #F2F2F2;
}
  
textarea
{
  width: 100%;
  height: 200px;
  padding: 12px 20px;
  box-sizing: border-box;
  
  font-family: "Helvetica Neue", sans-serif;
  border: 2px solid skyblue;
  border-radius: 4px;
  
  resize: vertical;
}
textarea:focus
{
  background-color: #F2F2F2;
}
  
button
{
  background-color: skyblue;
  border: none;
  border-radius: 4px;
  color: white;
  padding: 16px 32px;
  
  font-weight: bold;
  font-size: 14px;
  text-decoration: none;
  text-transform: uppercase;
  font-family: "Helvetica Neue"
  
  margin: 4px 2px;
  cursor: pointer;
}
  
select
{
  width: 100%;
  padding: 16px 20px;
  border: none;
  border-radius: 4px;
  background-color: #f1f1f1;
  text-transform: uppercase;
}
</style>

# Contact Me

You can email me through this form. I'll reply in a few business days, if necessary.

<div id="contact" align="center">
<form action="https://formspree.io/f/xayzavyk" method="POST">
<input type="name" name="Name" width="100%" placeholder="Name" required><br>
<input type="email" name="Email" width="100%" placeholder="Email" required><br>
<select id="topic" name="Topic" required>
  <option value="">Career Opportunity</option>
  <option value="ca">Feedback / Inquiry</option>
  <option value="usa">General</option>
</select>
<input type="hidden" name="_subject" width="100%" value="Webpage Contact" />
<textarea name="Message" width="100%" placeholder="Message" required></textarea><br>
<button type="submit" align="center">Send</button>
</form>
</div>
