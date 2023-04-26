---
title: Contact
layout: default
filename: contact.md
---

# Get in Touch

<style> 
input
{
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  box-sizing: border-box;
  
  border: 2px solid skyblue;
  border-radius: 4px;
}
  
textarea
{
  width: 100%;
  height: 200px;
  padding: 12px 20px;
  box-sizing: border-box;
  
  border: 2px solid skyblue;
  border-radius: 4px;
  
  resize: vertical;
}
  
input[type=button], input[type=submit], input[type=reset]
{
  background-color: skyblue;
  border: none;
  border-radius: 4px;
  color: white;
  padding: 16px 32px;
  
  text-decoration: none;
  text-transform: uppercase;
  
  margin: 4px 2px;
  cursor: pointer;
  font-weight: bold;
  font-size: 14px;
}
  
input:focus
{
  background-color: #F2F2F2;
}
textarea:focus
{
  background-color: #F2F2F2;
}
</style>

<div id="contact">
<form action="https://formspree.io/f/xayzavyk" method="POST">
<input type="email" name="Email" width="100%" placeholder="Your email" required><br>
<input type="hidden" name="_subject" width="100%" value="Webpage Contact" />
<textarea name="Message" width="100%" placeholder="Your message" required></textarea><br>
<button type="submit" align="center">Send</button>
</form>
</div>
