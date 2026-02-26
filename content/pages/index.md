---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Every Emotion, Beautifully Preserved Forever
      color: text-dark
      type: TitleBlock
    subtitle: GERMANY
    text: >
      ***Inspired by real moments and real people, I create digital diaries that
      feel alive forever.***
    actions:
      - type: Link
        label: Instagram
        altText: Instagram
        url: >-
          /https://www.instagram.com/iamuru__?igsh=MTVsaWJpb2Z6amtrbg%3D%3D&utm_source=qr
        showIcon: true
        icon: instagram
        iconPosition: left
        style: secondary
        elementId: ''
    media:
      url: /images/IMG_2137.jpeg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: FOUNDER OF THEURUPHOTOGRAPHY
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: GLOBAL GUJARATI GARBA 2025
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ORGANISED BY MAGICAL EVENTS EUROPE
    text: >
      ***More than a thousand people gathered to celebrate Garba, turning
      Munich’s biggest venue into a home away from home.

      Our storytelling captured the joy, unity, and heartbeat of the
      community.***
    media:
      title: Title of the video
      url: https://youtu.be/EP9gapW_P5Y?si=PAya8sLhme-4JiaL
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
      autoplay: true
      loop: true
      muted: false
    badge:
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection
  - type: FeaturedPostsSection
    title:
      type: TitleBlock
      text: Featured posts
      color: text-dark
      styles:
        self:
          textAlign: center
    posts:
      - >-
        content/pages/blog/how-to-write-a-blog-post-that-will-get-you-more-traffic.md
      - content/pages/blog/five-tips-for-starting-a-startup.md
      - content/pages/blog/what-is-a-design-system.md
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    actions: []
    elementId: ''
    variant: big-list
    colors: bg-light-fg-dark
    hoverEffect: shadow-plus-move-up
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
  - title:
      text: Social Media Management
      color: text-dark
      type: TitleBlock
    subtitle: For Increase Event reach
    text: >
      ***Helping your event reach the right audience, at the right time, with
      the right story.***
    actions: []
    media:
      type: VideoBlock
      title: Title of the video
      url: https://youtu.be/cLNf2zaMtCc?si=81jb1dGqeF7ilKnu
      autoplay: true
      loop: true
      muted: false
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      label: WE PROVIDE
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
    type: GenericSection
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: auto
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: FOR BOOKINGS
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: |
      ***Big events need big storytelling. Book your slot before it fills.***
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
