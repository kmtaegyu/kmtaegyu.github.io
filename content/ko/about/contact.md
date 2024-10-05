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
      text: |-
        <br> <span style="font-size:95%">연락 하는법.</span> <br>
      email: kmtaegyu(at)gmail.com
      #phone: +82-63-270-2406
      address:
        street: 전북대학교 공과대학 7호관 ㅇㅇㅇ호
        city: 전주시
        region: 전라북도
        postcode: '54896'
        country: 대한민국
        country_code: KO
      coordinates:
        latitude: '35.84601324617979'
        longitude: '127.13444961966684'
      directions: ""

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
          phone: 010-9931-9603

    design:
      columns: '3'
---
