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

  # Email form provider
  form:
    provider: formspree
    formspree:
      id: e0868b92-63aa-4d1f-bd79-07a165b6cbe3  # Web3Forms API Key
    netlify:
      captcha: false

design:
  columns: '1'
---
