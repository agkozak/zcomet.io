---
layout: 	page
title:		Contact Me
permalink:	/contact/
description:    >
  Contact me with questions and information.
---

<form action="https://api.web3forms.com/submit" method="POST">

    <!-- Replace with your Access Key -->
    <input type="hidden" name="access_key" value="874a744f-d425-4d95-b5e6-7fd20160207c">

    <!-- Form Inputs. Each input must have a name="" attribute -->
    <div class="form-group">
      <label for="name">Name:</label>
      <input class="form-control" type="text" name="name" placeholder="Your name (required)" required>
    </div>
    <div class="form-group">
      <label for="email">Email address:</label>
      <input class="form-control" type="email" name="email" placeholder="Your email address (required)" required>
    </div>
    <div class="form-group">
      <label for="message">Message:</label>
      <textarea class="form-control" name="message" placeholder="Your message (required)" rows="10" required></textarea>
    </div>

    <!-- Honeypot Spam Protection -->
    <input type="checkbox" name="botcheck" class="hidden" style="display: none;">

    <!-- Custom Confirmation / Success Page -->
    <input type="hidden" name="redirect" value="https://zcomet.io/thank-you/">

    <button type="submit" class="btn btn-primary">Submit</button>

</form>
