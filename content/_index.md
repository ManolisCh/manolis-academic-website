---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Preferably contact me via email. Twitter and LinkedIn will work as well but I do not check them very often. 
      # Contact (add or remove contact options as necessary)
      email: m.chiou@bham.ac.uk
      address:
        street: University of Birmingham 
        city: Birmingham
        postcode: 'B15 2SE'
        country: United Kingdom
        country_code: UK
       
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
