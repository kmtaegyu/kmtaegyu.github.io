---
# An instance of the Contact widget.
widget: contact

type: landing

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

sections:
  - block: contact
    content:
      title: Contact
      subtitle: ''

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

      # Coordinates for the map
      coordinates:
        latitude: '35.84601324617979'
        longitude: '127.13444961966684'

design:
  columns: '2'
---
