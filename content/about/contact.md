---
# An instance of the Contact widget.
# Documentation: https://docs.hugoblox.com/getting-started/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Get in touch
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # # Email form provider
  # form:
  #   provider: formspree
  #   formspree:
  #     id: e0868b92-63aa-4d1f-bd79-07a165b6cbe3  # Web3Forms API Key
  #   netlify:
  #     captcha: false
<div class="mb-3">
  <form action="https://api.web3forms.com/submit" method="POST">
    <input type="hidden" name="access_key" value="e0868b92-63aa-4d1f-bd79-07a165b6cbe3">
    <input type="hidden" name="subject" value="New Contact Form Submission">
    <input type="checkbox" name="botcheck" style="display: none;">
    
    <div class="form-group form-inline">
      <label class="sr-only" for="inputName">Name</label>
      <input type="text" name="name" class="form-control w-100" id="inputName" placeholder="Name" required>
    </div>
    
    <div class="form-group form-inline">
      <label class="sr-only" for="inputEmail">Email</label>
      <input type="email" name="email" class="form-control w-100" id="inputEmail" placeholder="Email" required>
    </div>
    
    <div class="form-group">
      <label class="sr-only" for="inputMessage">Message</label>
      <textarea name="message" class="form-control" id="inputMessage" rows="5" placeholder="Message" required></textarea>
    </div>
    
    <button type="submit" class="btn btn-primary px-3 py-2">Send</button>
  </form>
</div>


design:
  columns: '1'
---
