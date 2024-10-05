---
# An instance of the Contact widget.
# Documentation: https://docs.hugoblox.com/getting-started/page-builder/
widget: contact

#https://github.com/JBNU-MACS/JBNU-MACS.github.io/blob/main/content/ko/contact/index.md?plain=1
type: landing

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50
sections:
  title: Contact
  subtitle:

  content:
    # Automatically link email and phone or display as text?
    autolink: true

    # Email form provider
    form:
      provider: netlify
      formspree:
        id:
      netlify:
        # Enable CAPTCHA challenge to reduce spam?
        captcha: false
        email: kmtaegyu@gmail.com
        
  coordinates:
        latitude: '35.84601324617979'
        longitude: '127.13444961966684'

  design:
    columns: '2'
---
