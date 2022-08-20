---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contato
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

  # Contact details (edit or remove options as required)
  email: eliasmccosta@gmail.com
  phone: (21) 998530064
  address:
    street: Rodovia GO-174, Km-45 a direita 3,5km, Zona Rural 
    city: Montividiu
    region: Goiás
    postcode: 75915-000
    country: Brasil
    country_code: PT
  coordinates:
    latitude: -17.441907
    longitude: -51.143049
  office_hours:
    - 'Segunda 7:30 as 17:30'
    - 'Sexta 7:30 as 17:30'


design:
  columns: '2'
---
