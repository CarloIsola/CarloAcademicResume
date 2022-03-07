---
# An instance of the Contact widget.
widget: contact

# Activate this widget? true/false
active: false

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle: null

content:
  autolink: true
  form:
    provider: netlify
    formspree:
      ? id
    netlify:
      captcha: false
  email: test@example.org
  phone: 888 888 88 88
  address:
    street: 450 Serra Mall
    city: Stanford
    region: CA
    postcode: "94305"
    country: United States
    country_code: US
  coordinates:
    latitude: "37.4275"
    longitude: "-122.1697"
  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - Monday 10:00 to 13:00
    - Wednesday 09:00 to 10:00
  appointment_url: https://calendly.com
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: https://twitter.com/Twitter
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: https://zoom.com

design:
  columns: "2"
date: 2022-03-07T18:46:31.425Z
lastmod: 2022-03-07T19:43:08.852Z
---
