---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:

  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text:
      # Contact (add or remove contact options as necessary)
      email: justin.matejka@autodesk.com
      address:
        street: 661 University Ave, Suite 200
        city: Toronto
        region: ON
        postcode: L3X 3G9
        country: Canada
        country_code: CAN
      contact_links:
        - icon: envelope
          icon_pack: fas
          link: mailto:justin.matejka@autodesk.com  # For a direct email link, use "mailto:test@example.org".
        - icon: twitter
          icon_pack: fab
          link: https://twitter.com/JustinMatejka
        - icon: google-scholar
          icon_pack: ai
          link: https://scholar.google.com/citations?user=hl0aVwMAAAAJ
          
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
    design:
      columns: '2'
---
