---
title: Kontakt
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: >-
      Gemeinsam gestalten wir Ihren Garten um.<br>

      Füllen Sie das Kontaktformular aus oder schreiben Sie uns über
      [info@yildiz-gartenbau.de](mailto:info@yildiz-gartenbau.de).


      ***


      ## Unser Standort


      ### Laichingen

      Weite Straße 162<br>

      89150 Laichingen<br>

      0173 8387496 <br>

      [Anfahrt &rarr;](https://goo.gl/maps/snqCm9pToE4endDK8)

    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Ihr Name
        is_required: true
      - input_type: email
        name: email
        label: E-Mail
        default_value: Ihre E-Mail-Adresse
        is_required: true
      - input_type: select
        name: subject
        label: Ich interessiere mich für
        default_value: Bitte auswählen
        options:
          - Garten-Umgestaltung
          - Garten-Neuanlage
          - Garten-Pflege
          - Sonstiges
      - input_type: textarea
        name: message
        label: Nachricht
        default_value: Ihre Nachricht
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Nachricht senden.
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
