---
layout: layouts/page.njk
title: Contact
templateClass: tmpl-post
eleventyNavigation:
  key: Contact
  order: 4
---

<div class="row">
  <div class="col-md-8 offset-md-2">   
    <div class="border rounded bg-light mb-2">
      <form class="p-2" name="contact" method="POST" data-netlify="true" netlify-honeypot="bot-field">
        <label class="visually-hidden">🤖<input name="bot-field"/></label>
        <div class="row">
          <div class="col-md-6 py-1">
            <label for="forename" class="form-label">First name</label>
            <input type="text" class="form-control" id="forename" required>
          </div>
          <div class="col-md-6 py-1">
            <label for="surname" class="form-label">Last name</label>
            <input type="text" class="form-control" id="surname">
          </div>
          <div class="col-12 py-1">
            <label for="email" class="form-label">Email address</label>
            <input type="email" class="form-control" id="email" placeholder="example@you.com" required>
          </div>
          <div class="col-12 py-1">
            <label for="message" class="form-label">Your message</label>
            <textarea rows="5" class="form-control" id="message" placeholder="">
            </textarea>
          </div>
          <div class="d-flex flex-column py-2">
            <button type="submit" class="btn btn-primary">Submit</button>
          </div>
        </div>
      </form>
    </div><!-- border rounded bg-light mb-2 -->
  </div><!-- col-md-8 offset-md-2 -->
</div><!-- row -->
