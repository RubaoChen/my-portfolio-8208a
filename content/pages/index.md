---
title: Home
layout: PageLayout
sections:
  - type: HeroSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: We do fishing differently
    subtitle: Fresh. Better. Faster.
    text: 'We’re local, seasonal fisherman, supporting fishing restrictions.'
    actions:
      - type: Button
        label: Join adventure
        showIcon: true
        icon: arrowRight
        style: primary
        url: /
    media:
      type: ImageBlock
      url: /images/my picture.jpeg
      altText: Hero image
    backgroundImage: null
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-32
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-e
    backgroundSize: inset
    title: Tableau Dashboard
    subtitle: Visit @RubaoChen on Tableau Public
    actions:
      - type: Button
        label: visit all
        url: 'https://public.tableau.com/app/profile/rubao.chen'
        style: primary
        iconPosition: right
        icon: arrowRight
        showIcon: true
    backgroundImage:
      type: BackgroundImage
      url: /images/屏幕快照 2023-01-06 22.55.20-4b38ed9f.png
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 85
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-20
          - pb-96
          - pr-9
          - pl-9
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    media:
      type: ImageBlock
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
  - type: FeatureHighlightSection
    colors: colors-d
    backgroundSize: full
    title: Customer Segmentation
    text: |
      We’re local, seasonal fisherman, supporting fishing restrictions.
    actions:
      - type: Link
        label: Join adventure
        url: 'https://www.stackbit.com/'
        showIcon: true
        icon: arrowRight
    backgroundImage:
      type: BackgroundImage
      url: /images/hero-3.webp
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 90
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-72
          - pr-4
          - pl-4
        justifyContent: flex-start
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: ContactSection
    colors: colors-d
    title: Join our club
    text: >
      We will notify you every time a shipment is heading to your neighborhood,
      and you could immediatly let us know if you want in or not
    form:
      type: FormBlock
      elementId: sign-up-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: full
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: Submit form
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-4
          - pb-4
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
addTitleSuffix: true
metaTags: []
---
