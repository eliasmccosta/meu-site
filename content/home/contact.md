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
    street:  Rua Ceará, Nº 1441 Setor Zacarias Campelo 
    city: Pedro Afonso - TO
    region: Tocantins
    postcode: 77710-000
    country: Brasil
    country_code: PT
  coordinates:
    latitude: -8.98742
    longitude: -48.16104
  office_hours:
    - 'Segunda 7:00 as 17:00'
    - 'Sexta 7:00 as 17:00'


design:
  columns: '2'
---
