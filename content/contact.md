+++
title = ""
description = ""
date = "2023-07-09"
aliases = ["about-us", "about-hugo", "contact"]
author = "Hugo Authors"
+++


<script>
    function myFunction() {
        document.getElementById("response").innerHTML = "Thanks for reaching out! I will get back to you soon.";
    }
</script>

<div style = "display: flex;">

<form method="post" action="https://forms.un-static.com/forms/491526f9bbc563db0e296fab76a46569a99e8dc0" style = "margin: auto; align-self: center; border-color: purple; border-width: 10px; border-style: double; padding:10rem; padding-top:5rem; margin-top:5rem;">
<h1>Contact Me</h1>
<div style =  "width: 40rem; margin-top:5rem; margin-bottom: 5rem; line-height:3rem; font-family: Times New Roman; font-size: large;" >Feel free to send me a message! I'm happy to answer questions or take requests for new posts.</div>
  <div class="form-group row">
    <label for="name" class="col-4 col-form-label" style = "font-size: smaller;">Name</label>
    <div class="col-8" style = "margin-bottom: 2rem;">
      <div class="input-group">
        <input id="name" name="name" placeholder="Your name here" type="text" required="required" class="form-control" style = "font-size: large; padding:1rem; font-family: Times New Roman; width:40rem;">
      </div>
    </div>
  </div>
  <div class="form-group row">
    <label for="email" class="col-4 col-form-label" style = "font-size: smaller;">E-mail address</label>
    <div class="col-8" style = "margin-bottom: 2rem;">
      <div class="input-group">
        <input id="email" name="email" placeholder="Your e-mail address" type="text" required="required" class="form-control" style = "font-size: large; padding:1rem; font-family: Times New Roman; width:40rem;">
      </div>
    </div>
  </div>
  <div class="form-group row">
    <label for="message" class="col-4 col-form-label" style = "font-size: smaller;">Message</label>
    <div class="col-8" style = "margin-bottom: 0.5rem;">
      <textarea id="message" placeholder = "Type message here" name="message" cols="40" rows="10" required="required" class="form-control" style = "font-size: large; padding:1rem; font-family: Times New Roman; width:40rem;"></textarea>
    </div>
  </div>
  <div class="form-group row">
    <div class="offset-4 col-8">
      <button name="submit" onClick = "myFunction()" type="submit" class="btn btn-primary" style = "font-size: large; padding: 0.5rem; padding-left: 2rem; padding-right: 2rem;  color: white; border-color: purple: border-width:10px; border-radius:10%; background-color: purple; font-family: Georgia;">Send</button>
    </div>
  </div>
  <p id = "response"></p>
</form>

